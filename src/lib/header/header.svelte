<script>
        import SML_Logo from './SMLogo_long.png'
        import marble from './marble1.jpg';
        export let hHeight;
</script>

<header style="background-image: url({marble}); width: 100%; min-width: 100%; " bind:clientHeight={hHeight}>
        <img alt="Shannon Macleod, P.C." src="{SML_Logo}" >
</header>

<style>
   header {
        padding: 0;
        margin: 0;
        width:100%;
        flex: none;
        position: relative;
    }

    img {
        padding: 0;
        margin: 0;
	width: 80%;
	max-width: 700px;
        min-width: 480px;
        float: left;
	}
	
</style>