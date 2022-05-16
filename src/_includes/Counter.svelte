<script context="module">
  export const frontMatter = {
    title: "Seriously Svelte",
    layout: "layout",
    hydrate: "eager",
  };
</script>

<script>
  let count = 0;

  function add() {
    count += 1;
  }
</script>

<h2>TEST</h2>

<p>You've had {count} glasses of water 💧</p>
<button on:click={add}>Add one</button>
