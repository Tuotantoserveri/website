<script>
    import Link from "/src/components/Link.svelte"
</script>

<div class="top-bar">
    <div class="concluded">
        <p>Tämä sivusto on keskeneräinen. Jos sinulla on kysymyksiä, ota rohkeasti yhteyttä!</p>
    </div>
    <nav>
        <img class="img-container" src="/wide1.png">
        <div class="button-box">
            <Link target="#">linkki tähän</Link>
            <span class="button"><a href="mailto:hei@tuotantoserveri.fi">Ota yhteyttä!</span>
        </div>


    </nav>
</div>

<style>
    
    .top-bar {
        position: fixed;
        display: flex;
        top: 0;
        z-index: 1;
        flex-direction: column;
    }
    
    .concluded {
        width: 100%;
        background-color: #ffc501;
        height: max-content;
    }
    
    .concluded > p {
       margin: 0;
       text-align: center;
       font-weight: 500;
       padding: 0.5rem;
    }
    
    nav {
        background-color: black;
        height: max-content;
        width: 100vw;
        top: 0;
        padding:0.5rem;
        padding-right: 2rem;
        box-sizing: border-box; 
        line-height: 2rem;
        color: white;
        align-items: center;
        z-index: 1;
        display: flex;
    }
    
    .button > a {
        color: black;
    }
    
    a {
        text-decoration: none;
        font-weight: 700;
    }

    h2 {
        margin: 0;
        font-size: 5vmin;
        line-height:5vmin; 
    }
    

    .button {
        display: inline-flex;
        justify-content: center;
        background: var(--main-orange);
        color: black;
        border-radius: 2.5px;
        padding: 0.5rem;
        transition: ease 0.25s;
        cursor: pointer;
        user-select: none;        
        margin:0;
        line-height: 1rem;
    }
    
    .button:hover {
        transform: translateX(-0.25em);
    }

    .button:active {
        transform: scale(0.98);
    }

    .button-box {
        display:flex;
        justify-content:end;
        flex-grow: 4;
        gap:1.5rem;
        font-size:1.25rem;
    }

    .img-container {
        max-height: 70px;
        height: 70%;
        width: auto;
    }
</style>
