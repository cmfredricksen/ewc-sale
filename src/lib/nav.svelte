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
		color: var(--clr-green-dk);
	}
</style>
