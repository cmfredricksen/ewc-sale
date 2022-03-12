<script>
	import Nav from './nav.svelte';
</script>

<header>
	<h1><a class="indigo" href="/">Ely Watercolor Club</a> &ap; Annual Sale 2022</h1>
	<Nav />
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
		padding: 0.5rem;
		align-items: baseline;
		/* border-bottom: 2px solid var(--clr-indigo); */
		color: var(--clr-indigo);
		background-color: var(--clr-gold);
		background-blend-mode: darken;
	}

	.indigo {
		color: var(--clr-indigo);
		text-decoration: none;
		font-family: var(--font-headings);
		font-size: 3.25rem;
	}

	.indigo:hover {
		color: var(--clr-magenta);
	}

	@media (max-width: 720px) {
		header {
			flex-direction: column;
			padding: 0.5rem;
			align-items: center;
			text-align: center;
		}

		h1 {
			padding: 0.75rem 0.5rem;
			margin-bottom: 1rem;
		}
	}
</style>
