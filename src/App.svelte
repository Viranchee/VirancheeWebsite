<script>
  import Tailwindcss from "./Components/Tailwindcss.svelte";

  export let name;
</script>

<main>
  <Tailwindcss />
  <h1 class="font-bold text-green-500">Title</h1>
  <h1>Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
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
