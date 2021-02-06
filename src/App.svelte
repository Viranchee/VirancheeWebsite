<script>
  import Body from "./Components/Body.svelte";
  import Footer from "./Components/Footer.svelte";
  import Header from "./Components/Header.svelte";
  import Tailwindcss from "./Components/Tailwindcss.svelte";

  export let name;
</script>

<main>
  <Tailwindcss />
  <Header />
  <Body {name} />
  <Footer />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }
  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
