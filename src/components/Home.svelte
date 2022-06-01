<script>
    import {darkmode} from '../store/Store.js';
</script>
<section class="home">
    <div class="sidebar">

    </div>
    <div class="textHome">
        <div><p class="especialFont">
         {$darkmode?'<body class="darkmode">':'<body>'}   
        </p></div>
        <div><p class="especialFont tab">&lt;h1 class="myName"&gt;</p></div>
        <div class="tab-2">
            <h2 class="bold">HI IM</h2>
            <h1 class="bold">JOHN GUALTEROS</h1>
            <h2 class="bold">SOFTWARE DEVELOPER</h2>
        </div>
        <div><p class="especialFont tab">&lt;/h1&gt;</p></div>
        <div><p class="especialFont tab">&lt;p class="thatIAm"&gt;</p></div>
        <div class="tab-2">
            <h3>I am Fullstack Developer And Autodidact</h3>
        </div>
        <div><p class="especialFont tab">&lt;/p&gt;</p></div>
        <div><p class="especialFont tab">&lt;button class="downloadCv"&gt;</p></div>
        <div class="tab-2">
            <button>Donwload Cv</button>
        </div>
        <div><p class="especialFont tab">&lt;/button&gt;</p></div>
    </div>
</section>
<style>
    .home{
        width: 100%;
        height:100vh;
        display: grid;
        grid-template-columns: 10% auto;
    }
    .textHome{
        height: 100vh;
        display: grid;
    }
    .sidebar{
        background-color: #53f4f4;
        height: 100vh;
    }
    button{
        border: 2px solid var(--color-primary);
        border-radius: 5px;
        background-color:transparent;
        color: var(--color-primary);
        font-size: 1.1em;
        font-weight: bold;
        padding: 5px;
        transition: all .5s ease-in-out;
        cursor: pointer;
        margin: 10px 0;
    }
    button:hover{
        background-color: var(--color-primary);
        color: var(--color-light);
        transition: all .5s ease-in-out;
    }
</style>