<script>
  import DisplayData from './lib/DisplayData.svelte';
	import Navbar from './lib/Navbar.svelte';
</script>

<Navbar/>
<div class="app">
	<DisplayData/>
</div>
<footer>
	<p>MC Arena by github.com/elecarno, <a href="https://discord.gg/dvNcM2zK8Q">join the discord to play</a> </p>
</footer>

<style>
  .app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}
</style>
