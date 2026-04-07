<script>
  let name = 'World';
</script>

<main>
  <h1>Hello, {name}!</h1>
  <input bind:value={name} placeholder="Enter a name" />
</main>

<style>
  main { font-family: sans-serif; text-align: center; padding: 2rem; }
  h1 { color: #ff3e00; }
  input {
    margin-top: 1rem; padding: 0.5rem; font-size: 1rem;
    border: 2px solid #ff3e00; border-radius: 4px;
  }
</style>