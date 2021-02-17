<script>
  let count = 0;

  const up = () => (count += 1);
</script>

<button on:click={up}>Increase Count ({count})</button>
