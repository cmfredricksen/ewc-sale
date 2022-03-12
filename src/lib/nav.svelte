<script>
	const links = [
		{
			title: 'Home',
			path: '/'
		},
		{
			title: 'About',
			path: '/about'
		},
		{
			title: 'Directions',
			path: '/directions'
		}
	];
</script>

<nav>
	{#each links as link}
		<a href={link.path}>{link.title}</a>
	{/each}
</nav>

<style>
	a {
		margin: 0 1rem;
		color: var(--clr-indigo);
		text-decoration: none;
	}

	a:hover {
		color: var(--clr-magenta);
		font-weight: bold;
	}

	@media (max-width: 720px) {
		a {
			font-size: 1.2em;
		}
	}
</style>
