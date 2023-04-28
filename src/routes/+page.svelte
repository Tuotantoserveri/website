<script>
    import Hero from "../components/hero.svelte"
    import Nav from "../components/nav.svelte";
    import About from "../components/about.svelte"
    import Further from "../components/further.svelte"
    import Link from "../components/Link.svelte";
</script>

<svelte:head>
  <!-- HTML Meta Tags -->
  <title>Tuotantoserveri</title>
  <meta name="description" content="Tuotantoserveri">

  <!-- Google / Search Engine Tags -->
  <meta itemprop="name" content="Tuotantoserveri">
  <meta itemprop="description" content="Tuotantoserveri">
  <meta itemprop="image" content="/bannerdimmed.png">

  <!-- Facebook Meta Tags -->
  <meta property="og:url" content="https://tuotantoserveri.fi">
  <meta property="og:type" content="website">
  <meta property="og:title" content="Tuotantoserveri">
  <meta property="og:description" content="Tuotantoserveri">
  <meta property="og:image" content="/bannerdimmed.png">

  <!-- Twitter Meta Tags -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Tuotantoserveri">
  <meta name="twitter:description" content="Tuotantoserveri">
  <meta name="twitter:image" content="/bannerdimmed.png">
</svelte:head>

<Nav/>
<Hero/>
<About />
<Further />



<footer>
    <div>
        <img class="img-container" src="/wide2.png">
        <p>hei@tuotantoserveri.fi</p>
        <p>etunimi.sukunimi@tuotantoserveri.fi</p>
    </div>
    
        
    
</footer>

<style>
    footer {
        display: flex;
        background-color: #000000;
        justify-content: flex-start;
        align-items: flex-end;
        color: #ffffff;
        flex-wrap: wrap;
        padding-left: 2rem;
        padding-right: 2rem;
        padding-bottom: 1.2rem;
        border-style: solid none none none;
        border-width: 10px;
        border-color: #FF9943;

    }

    footer > div {
        background-color: #000000;
        padding: 10px 25px 25px 25px;
        border-style: none solid solid solid;
        border-width: 5px;
        border-color: #FFE484;
        border-radius: 0px 0px 15px 15px;
    }

    footer > div > p {
      margin-block-start: 0.7em;
        line-height: 1.5;
        margin-block-end: 0em;
    }
    
    .img-container {
        max-height: 70px;
        height: 70%;
        width: auto;
    }
    
    
</style>
