<script>
  import Count from './Count.svelte';
  import Feature from './Feature.svelte';
  import Image from './Image.svelte';
</script>

<main>
  <h1>Git Test</h1>
  <Count />
  <Feature />
  <Image />
</main>

<style>
  main {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 40px;
    padding: 1em;
    width: 600px;
    min-height: 100vh;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
