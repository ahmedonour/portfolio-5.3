<script>
  import Loader from "./lib/loader.svelte";
  import HeroCircle from "./lib/home/heroCircle.svelte";
  import Navbar from "./lib/home/navbar.svelte";
  import HeroText from "./lib/home/heroText.svelte";
  import HeroSocialIcons from "./lib/home/heroSocialIcons.svelte";
</script>

<svelte:head>
  <link
    href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&family=Plaster&display=swap"
    rel="stylesheet"
  />
</svelte:head>
<main>
  <Navbar />
  <!-- <Loader /> -->
  <div class="herosection">
    <HeroSocialIcons />
    <HeroText />
    <HeroCircle />
  </div>
</main>

<style scoped>
  .herosection {
    height: calc(100vh - 100px );
    display: grid;
    place-items: center;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(3, 1fr);
  }
  main {
    background-color: #5200ff;
    width: 100vw;
    height: 100vh;
   
  }
  @media screen and (max-width: 414px){
    .herosection{
      height: 80vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: space-around;
    }
  }
</style>
