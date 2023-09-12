<script>
  import '../app.css'
  import Footer from '$lib/Footer.svelte'
</script>

<main>
  <slot />
</main>

<Footer/>
<style>
  main {
    margin: auto;
    max-width: 1200px;
  }
</style>
