<script>
	import '../../static/global.css';
	import Header from '$lib/header.svelte';
	import Footer from '$lib/footer.svelte';
</script>

<svelte:head>
	<title>Ely Watercolor Club &ap;</title>
</svelte:head>

<Header />
<div class="wrapper">
	<slot />
</div>
<Footer />

<style>
	.wrapper {
		width: 96vw;
		margin: 0 auto;
		/* background: var(--clr-green-dk); */
		background: linear-gradient(var(--clr-indigo), var(--clr-green-dk));
		color: var(--clr-white);
		min-height: 50vh;
	}

	/* @media (max-width: 720px) {
		.wrapper {
			width: 100vw;
			background-color: var(--clr-green-dk);
		}
	} */
</style>
