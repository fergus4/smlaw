<script>
    //import { fade } from 'svelte/transition';
    //import { fly } from 'svelte/transition';
    //import { quintOut } from 'svelte/easing';
    import shannon_head from '../../static/images/shannon_head_big.jpg';
    //import rochelle_head from 'images/RochelleHead.jpg';

</script>

<svelte:head>
	<title>About Us</title>
</svelte:head>


<!--<main in:fly="{{ x: 2000, duration: 2000 }}" out:fly="{{ x: 2000, duration: 2000 }}"> -->
    <main>
    <content>
        <img alt="Shannon Macleod" src="{shannon_head}" style="float:left;padding-right: 10px;">
        <h3>Shannon Macleod, Esq.</h3><p>Shannon received her Bachelors of Science in Psychology from Fordham University in 1997.  Straight from Fordham University, Shannon began working in the accounting department of an Extended Care Facility.  She was promoted within her five-year tenure at the extended care facility from Accounting Clerk to Accounts Receivable Manager/Medicaid Coordinator.  Her duties at the facility included supervising all patient accounts, performing financial interviews for in-house patients and potential admissions, preparing Medicaid applications, and recording and tracking daily census records.</p><p>In 1999, Shannon entered the evening program at St. John's University's School of Law.  She also took a position as a paralegal in 2000 with a Long Island law firm representing over 150 nursing homes within New York State.  As a paralegal, and then in 2004 as an attorney, Shannon concentrated her practice on health care collection and reimbursement recovery issues.  For eight years, Shannon counseled and represented the firm's nursing home clients on all aspects relating to Medicaid reimbursement.</p><p>In 2008, while remaining of counsel to one of the largest law firms on Long Island, Shannon Macleod began her own practice.  She has combined her vast knowledge of the Medicaid system and her experience with the nursing home industry to provide her clients with individualized legal and professional representation.</p><p>Shannon is a member of the Elder Law sections of both the New York State and Suffolk County Bar Associations.</p>
    </content>
<!--
    <content>
        <img alt="Rochelle Verron" src="{rochelle_head}" style="float:right;">
        <h3>Rochelle L. Verron, Esq.</h3><p>Rochelle first joined the firm in January of 2010.  In 2013, Rochelle graduated from John Jay College of Criminal Justice with an undergraduate degree in Criminal Justice.  Inspired by her work in the legal field, she went on to attend Touro Law School located in Central Islip, Long Island, New York as a part-time evening student. During her time at Touro Law, she received three CALI Awards: Top Legal Advocate, Estate Litigation, and Federal Income Tax. Rochelle was a member of the Touro Moot Court Honors Board where she served as the Competition Editor.</p><p>In 2018, while working full time at the firm, she earned her juris doctorate, cum laude.  In addition to her cum laude honors, Rochelle was the recipient of two distinguished awards at Touro Law School for Special Legal Service to the Community and Moot Court Honors Board.</p><p>Rochelle focuses her practice in the area of Elder Law, Estate Planning, Estate Administration, and Guardianships.  Rochelle is certified to serve as an Article 81 guardian, court evaluator, counsel to the alleged incapacitated person, and counsel to guardian in the Supreme and Surrogate Courts of Nassau and Suffolk Counties.</p><p>Rochelle has been published in the Suffolk Lawyer concentrating on topics surrounding elder law and how to maintain a balanced life. Rochelle served as co-author of “Diminished Mental Capacity” printed in the New York Law Journal.</p><p>Rochelle is a member of the Suffolk County Bar Association, New York State Bar Association, and Suffolk County Elder Law Committee. Rochelle lives in Amityville, New York with her husband, and pug named Benji.</p>
    </content>
-->
</main>


<style>
    main {
        top: 0
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
    
    
</style>