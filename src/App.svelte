<script>
  import { onMount } from 'svelte'
  import { createScene } from './scene'

  let canvas
  onMount(() => createScene(canvas))
</script>

<main>
  <canvas bind:this={canvas}></canvas>
</main>

<style>

</style>
