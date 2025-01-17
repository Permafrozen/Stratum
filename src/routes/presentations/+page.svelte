<script>
  import { onMount } from "svelte";
  import "../app.postcss";

  onMount(async () => {
    const Reveal = (await import("reveal.js")).default;
    const deck = new Reveal();
    deck.initialize();
  });
</script>

<div class="reveal">
  <div class="slides">
    <section>
      <h1>My Presentation</h1>
    </section>
    <section>
      <h2>Slide 2</h2>
    </section>
  </div>
</div>

<style>
  @import "reveal.js/dist/reveal.css";
  @import "reveal.js/dist/theme/black.css";
</style>
