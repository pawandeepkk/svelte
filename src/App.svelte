<script>
  import Card from "./components/generic/Card.svelte";
  let src = "/logo.svg";
</script>

<!-- HTML -->
<img class="logo" {src} alt="OSSA's logo" />
<Card />

<style>
  .logo {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }
</style>
