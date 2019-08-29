<script>
  let count = 0;

  function increment () {
    count++;
  }
</script>
<style>
  button {
    cursor: pointer;
    font-size: 20px;
    border-radius: 4px;
  }
</style>

<span>
  You pressed <strong>{count}</strong> times!
</span>
<button on:click={increment}>+</button>