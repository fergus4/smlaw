<script>
    //import { fade } from 'svelte/transition';
    //import { quintOut } from 'svelte/easing';
    import SML_icon from "../../static/images/icons/android-icon-48x48.png";
    import shannon_head from "../../static/images/shannon_head_big.jpg";
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>


<main > 

    <coInfo>
        <container>
            <p><u>Phone</u>: (631) 482-1800</p> <p><u>Fax</u>: (631) 482-1799</p>
        </container>
    <p>Email: <a href="mailto:shannon@smacleodlaw.com">shannon@smacleodlaw.com</a></p>
    <h3>Two Locations</h3>
 	<container>
        <add><b>975 Sunrise Highway<br>West Babylon, NY 11704</b></add>
        <add><b>186 W. Montauk Highway<br>Suite D4<br>Hampton Bays, NY 11946</b></add>
    </container>
    </coInfo>
    
    <content>
        <img alt="SML Icon" src="{SML_icon}" style="margin-top: 13px; margin-right: 10px; float:left;">
        <img alt="Shannon Macleod" src="{shannon_head}" style="float:right;">
        
        <h3>Professional and Sympathetic at a difficult time.</h3><br><p>Shannon Macleod, Esq. is dedicated and committed to providing effective and professional service to her clients.  Her expertise in the area of Medicaid issues will provide a guiding hand through a traumatic and difficult time in your family's lives.  Choosing to have her on your side throughout the Medicaid process will prove to be the right choice at a time when you need to make decisions that will provide peace of mind to you and your family.</p>
        <h3>Focusing on Elder Law issues:</h3>
        <ul><li>Medicaid Planning/Estate Planning</li>
            <li>Asset Protection</li>
            <li>Nursing Home Placement</li>
            <li>Wills and Trusts</li>
            <li>Probate</li>
            <li>Real Estate</li>
        </ul>
    </content>
</main>


<style>

    main {
        height: auto;
    }
    
    ul {
        margin: 0;
    }
    h3 {
        font-family: Georgia, "Times New Roman", Times, serif;
        font-size: x-large;
        font-weight: bold;
        font-style: italic;
        width: 100%;
        padding: 0;
        margin: 0;
        margin-top: 10px;
        color: #686868;
        text-align: center;
        line-height: .7cm;
        white-space: pre-wrap;
        
    }
    p {
        padding: 0;
        margin: 0;
        line-height: .5cm;
        font-weight: bold;
        white-space: pre-wrap;
    }
    content h3 {
        text-align: left;
        
    }
    content ul li {
        font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif;
        font-size: medium;
        font-weight: bold;
        padding: 0;
        margin: 0;
        color: black;
    }
    content {
        font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif;
        display: block;
        background-color: rgba(255, 255, 255, .7);
        border: black 1px solid;
        border-radius: 6px;
        margin: 10px auto;
        width: 90%;
        max-width: 600px;
        padding: 10px;
        text-align: left;
    }
    coInfo {
        display: block;
        background-color: rgba(255, 255, 255, .7);
        border: black 1px solid;
        border-radius: 6px;
        margin: 0px auto;
        margin-top: 10px;
        width: 90%;
        max-width: 600px;
        padding: 10px;
        text-align: center;
    }
    container {
        display: flex;
        justify-content: space-around;
        padding: 5px 5px;
        line-height: .5cm;
        text-align: left;
        
        }
    add {
        padding: 5px;
    }
    a {
        color: blue;
    }
    
</style>