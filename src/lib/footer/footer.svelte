
<script>
    import marble from './marble1.jpg';
    export let fHeight;
</script>

<footer style="background-image: url('{marble}'); min-width: 100%; " bind:clientHeight={fHeight}>
    <container>
        <iContainer><lab><u>Phone</u>:</lab> <info> 631-482-1800</info></iContainer>
        <iContainer><lab><u>Fax</u>: </lab> <info> 631-482-1799</info></iContainer>
        <iContainer><lab><u>Email</u>: </lab> <info> shannon@smacleodlaw.com</info></iContainer>
    </container>
    <container>
        <company>Site Created by Babylon Apps </company>
    </container>
</footer>

<style>
    footer {
        flex: none;
        bottom:0;
        width:100%;
        position: fixed;
       
    }
    
    container {
        text-align: center;
        display: flex;
        justify-content: space-between;
        margin-left: 5px;
        margin-right: 5px;
    }
    lab {
        
    }
    info {
        margin-left: 10px;
        
    }
    iContainer {
        text-align: center;
        padding: 0;
        margin: 0;
        
        color: white;
        padding: 2px
    }
    
    company {
        font-size: smaller;
        color: rgb(14, 179, 137);
        margin: auto;
        text-align: center;
    }
</style>