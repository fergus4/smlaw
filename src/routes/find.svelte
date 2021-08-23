<script>
    //import { fly, fade} from 'svelte/transition';
    //import { quintOut } from 'svelte/easing';
    import bMap from '../../static/images/GMapBabylon.jpg';
    import bOffice from '../../static/images/office_big.jpg';
    import hMap from '../../static/images/GMapHamptonBays.jpg';
    import hOffice from '../../static/images/OfficeEast.jpg';
</script>

<svelte:head>
    <title>Find Us</title>
</svelte:head>


<main > 
    
    <coInfo>
        <h3>Shannon Macleod, P.C.</h3>
        <p><u>Tel</u>: (631) 482-1800</p>
        <p><u>Fax</u>: (631) 482-1799</p>
    <p>Email: <a href="mailto:shannon@smacleodlaw.com">shannon@smacleodlaw.com</a></p>
    <h3>Two Locations</h3>
 	<container>
        <b>975 Sunrise Highway<br>West Babylon, NY 11704</b>
        <b>186 W. Montauk Highway<br>Suite D4<br>Hampton Bays, NY 11946</b>
    </container>
    </coInfo>
    
    <content>
        <img alt="West Babylon Office" src="{bOffice}" style="float:right; width: 150px;">
        <h3>Main Office</h3>
        <h3>Centrally Located on Long Island</h3>
        <p><b>975 Sunrise Highway<br>West Babylon, NY 11704</b></p><br>
        <p><i>(Click Map to open Google Maps)</i></p>
        <a target="_blank" href="https://www.google.com/maps/place/975+Sunrise+Hwy,+West+Babylon,+NY+11704"><img border="0" alt="West Babylon Map" src="{bMap}" width="100%" style="margin-top: 5px;"></a>
        <!--<img alt="West Babylon Map" src="{bMap}" style="width: 100%;">-->
    </content>

    <content>
        <img alt="Hampton Bays Office" src="{hOffice}" style="float:right; width: 150px; position: relative;">
        <h3>Satellite Office</h3>
        <h3>East End of Long Island</h3>
        <p><b>186 W. Montauk Highway<br>Suite D4<br>Hampton Bays, NY 11946</b></p><br>
        <p><i>(Click Map to open Google Maps)</i></p>
        <a target="_blank" href="https://www.google.com/maps/place/186+W+Montauk+Hwy,+Hampton+Bays,+NY+11946"><img border="0" alt="Hampton Bays Map" src="{hMap}" width="100%" style="margin-top: 5px;"></a>
        <!--<img alt="Hampton Bays Map" src="{hMap}" style="width: 100%; position: relative;">-->
    </content>

</main>


<style>
    main {
        overflow: hidden;
        flex: 0 0 auto;
        margin: 0 auto;
        width: 100%;
    }
    
    h3 {
        font-family: Georgia, "Times New Roman", Times, serif;
        font-size:larger;
        font-weight: bold;
        font-style: italic;
        width: 100%;
        padding: 0;
        margin: 0;
        color: #686868;
        text-align: center;
        line-height: .6cm;
        
    }
    p {
        padding: 0;
        margin: 0;
        line-height: .5cm;
        font-weight: bold;
    }
    content h3 {
        text-align: left;
    }
    
    content {
        font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif;
        display: block;
        background-color: rgba(255, 255, 255, .7);
        border: black 1px solid;
        border-radius: 6px;
        margin: 0 auto;
        width: 90%;
        max-width: 600px;
        margin: 10px auto;
        padding: 10px;
        text-align: left;
    }

    coInfo {
        display: block;
        background-color: rgba(255, 255, 255, .7);
        border: black 1px solid;
        border-radius: 6px;
        margin: 0 auto;
        width: 90%;
        max-width: 600px;
        margin: 10px auto;
        padding: 10px ;
        text-align: center;
    }
    container {
        display: flex;
        justify-content: space-around;
        margin: 0 5px;
        padding: 5px 10px;
        line-height: .5cm;
        text-align: left;
        }
    a {
        color: blue;
    }
    
</style>