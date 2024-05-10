<script>
  import Header from "$lib/Header.svelte";
  import Card from "$lib/Card.svelte";
</script>

<Header />

<main>
  <Card name="brick" src="/unpainted-brick.jpg" price="$20" />

  <Card name="white brick" src="/white-brick.jpg" price="$20" />

  <Card name="rough" src="/rough.jpg" price="$20" />
</main>

<footer>
  <p>&copy; Craighead Diocesan School 2024</p>
</footer>

<style>
  main {
    display: flex;
    justify-content: space-evenly;
    background-color: #051318;
  }

  footer {
    background-color: #051318;
    display: flex;
    justify-content: center;
    padding: 5rem 0;
    font-size: 1rem;
    font-family: "Russo One", sans-serif;
    color: #89979c;
  }
</style>
