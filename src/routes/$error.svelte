<script>
export let status;
export let error;
</script>

<main>
  <h1>{status}</h1>
  <p>Something went wrong!</p>
  <pre>{error.stack}</pre>
</main>