<script>
	import Card from './Card.svelte';
</script>

<main>
	<h1>The Museum of Dogs</h1>
  	<p>This website contains images of different types of pure 
		bred dogs. Visit the link to discover more breeds and 
		more information at the <a href = "https://www.akc.org/">AKC</a></p>
	<Card />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>