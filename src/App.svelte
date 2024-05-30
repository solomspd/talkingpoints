<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div class="talkingpoints">
    <div class="input">
      <input type="file" multiple />
    </div>
    <div class="output">
      <h1>Transcribed</h1>
    </div>
  </div>
</main>

<style>
  .talkingpoints {
    display: flex;
  }
  
  .input {
    flex: 1;
    padding: 1em;
  }
  
  .output {
    flex: 1;
    padding: 1em;
  }

  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
