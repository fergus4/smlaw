<script>
    export let pan;
</script>


<style>
   a {
        background-color: rgba(0, 0, 0, .5);
        border: none;
        color: white;
        padding: 10px 10px;
        text-align: center;
        text-decoration: none;
        display: block;
		float: left;
        font-size: 16px;
        width: 25%;
        }
        a:hover {
            background-color: rgba(100, 100, 100, .5);
        }
       
        nav {
            display: flex;
            width: 100%;
            position:relative;
		    padding: 0;  
            margin: 0;    
        }
</style>
<!--
<nav>
    <button on:click="{() => (pan = 0)}">Home</button>
    <button on:click="{() => (pan = 1)}">About Us</button>
    <button on:click="{() => (pan = 2)}">Services</button>
    <button on:click="{() => (pan = 3)}">Find Us</button>
</nav>

<nav>
    <button on:click=<a sveltekit:prefetch href="/">>Home</button>
    <button on:click="<a sveltekit:prefetch href="/about">">About Us</button>
    <button on:click="{() => (pan = 2)}">Services</button>
    <button on:click="{() => (pan = 3)}">Find Us</button>
</nav>
-->
<nav>
    <a sveltekit:prefetch href="/">Home</a>
    <a sveltekit:prefetch href="/about">About Us</a>
    <a sveltekit:prefetch href="/services">Services</a>
    <a sveltekit:prefetch href="/find">Find Us</a>    
</nav>
