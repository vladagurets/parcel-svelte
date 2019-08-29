<script>
  import Counter from './Counter.svelte'
  export let title;
</script>

<style>
  h1 {
    font-style: italic;
  }
</style>

<h1>{title}!</h1>
<Counter/>