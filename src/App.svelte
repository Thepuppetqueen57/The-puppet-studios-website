<script>
  function cbosbarbarians() {
    window.location.href = 'https://thepuppet57.141412.xyz/tps/cbos';
  }

  function navigateToInfo() {
    window.location.href = 'https://thepuppet57.141412.xyz/tps/info.html';
  }
</script>

<main>
  <div id="some-bad-id-cuz-idk-what-to-name-these">
    <h1 class="bigboytext">The Puppet Studios!</h1>
    <div class="button-container">
      <button class="booton" on:click={navigateToInfo}>Info</button>
      <button class="booton" on:click={cbosbarbarians}>C-Bos</button>
    </div>
  </div>
</main>

<style lang="scss">
  $purple: #370664;
  $purpletext: #420068;
  $lightgray: #b6b6b6;

  :global(body), :global(html) {
    overflow: hidden;
    height: 100%;
    margin: 0;
    background-color: black;
    font-family: Arial, Helvetica, sans-serif;
  }

  main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  .bigboytext {
    color: $purpletext;
    margin-bottom: 5px;
  }

  .button-container {
    display: flex;
    gap: 10px;
    justify-content: center;
    align-items: center;
    margin-top: 10px;
  }

  .booton {
    color: $lightgray;
    background-color: $purple;
    width: 90px;
    height: 40px;
    border: none;
    border-radius: 10px;
    transition: 0.3s;
    cursor: pointer;
  }

  .booton:hover {
    transform: scale(1.1);
    background-color: darken($purple, 3);
  }
</style>