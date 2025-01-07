<script lang="ts">
  import { base } from "$app/paths";
  let { children } = $props();
</script>

<nav>
  <a href="{base}/">home</a> <br />
  <a href="{base}/dotfiles">dotfiles</a> <br />
  <a href="{base}/presentations">presentations</a> <br />
</nav>

{@render children()}
