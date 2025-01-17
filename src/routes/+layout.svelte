<script>import "../app.css";
import { base } from "$app/paths";
let { children } = $props();</script>

<nav>
  <a href="{base}/">home</a>
  <a href="{base}/dotfiles">dotfiles</a>
  <a href="{base}/presentations">presentations</a>
</nav>

{@render children()}
