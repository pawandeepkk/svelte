<script>
  import Card from "./components/generic/Card.svelte";
  import Header from "./components/layout/Header.svelte";
</script>

<!-- HTML -->
<Header />

<Card>
  <div class="text1">
    <p>
      Almost every business in the country is a small business.
      <b>Who knew?</b>
    </p>
  </div>

  <div class="text2">
    <p>
      They provide services that make our day to day lives work & are the
      lifeblood of our economy.
    </p>
  </div>
</Card>

<style>
  p {
    color: white;
  }

  .text1 {
    text-align: left;
    font-family: serif;
    max-width: 200px;
    padding-left: 100px;
    font-size: 25px;
  }

  .text2 {
    max-width: 200px;
    padding-right: 100px;
    font-size: 25px;
  }
</style>
