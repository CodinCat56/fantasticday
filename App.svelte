<script>
  let MOTD = "Have a fantastic Sun Shiny day";
  let name = "";
  let img1 = "https://corgiscorgiscorgis.github.io/hewwo.gif";
</script>

<style>
  .MOTD {
    font-family: "Comic Sans MS";
    text-align: center;
  }
  .corgibox {
    width: 250px;
    height: 200px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
    height: 50%;
  }
  main {
    background-color: purple;
  }
</style>

<main>
  &nbsp;
  <input bind:value={name} placeholder="enter your name">
	<h1 class="MOTD"> {MOTD}, {name}! </h1>
  <img class="corgibox" src="{img1}" alt="corgi popping out of amazon box" > 
  &nbsp;
</main>