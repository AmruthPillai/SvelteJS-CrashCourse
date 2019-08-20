<script>
  let bro = "Bro";

  const clickEvent = () => {
    bro = "Dude!";
  };
</script>

<h1>{bro}</h1>

<button on:click={clickEvent}>Click Me</button>
