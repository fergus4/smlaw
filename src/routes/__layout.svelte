<script>
	import Header from '$lib/header/header.svelte';
    import Nav from "$lib/nav/nav.svelte";
    import Footer from "$lib/footer/footer.svelte";
	
	import Home from './index.svelte';
	import About from './about.svelte';
	import Services from './services.svelte';
	import Find from './find.svelte';
	//import bench from '../../static/images/bench3.jpg';
	import '../app.css';
	let hHeight;
	let fHeight;
	let cHeight;
	//$: pHeight = 400 - 50 - 200 + 'px';
	$: pHeight = cHeight - hHeight - 80 + 'px';
	
	//const slides = [
	//	Home,
	//	About,
	//	Services,
	//	Find
	//];

	let currentComponent = 0;
</script>

<style>

    page {
		display:flex;
  		flex-direction: column;
		min-height: 100vh;
		min-width: 100%;
		overflow: hidden;
	}
	
	 
	/*
	 sContainer {
  		overflow-x: scroll;
  		overflow-y: hidden;
  		white-space: nowrap;
	}
	*/
	slot {
		display: flex;
		width: 100%;
		height: 100vh;
        position:relative;
		padding: 0;  
        margin: 0;    
	}
	panel {
		overflow-y: auto;
		overflow-x: hidden;
		height: var(--panel-height);
	}
</style>

<page  bind:clientHeight={cHeight}>
	
	
<Header bind:hHeight={hHeight}/>

<Nav bind:pan={currentComponent} />

<!--
<panel style="--panel-height:{pHeight}">
	<slot></slot>
</panel>
-->
<!--	
	<sContainer>
		<Home />
		<About />
  	</sContainer>
	-->
  
	<panel style="--panel-height:{pHeight}">
		<!-- <svelte:component this={slides[currentComponent]} /> -->
		<slot></slot>
	</panel>

<Footer  bind:fHeight={fHeight}/>

</page>


