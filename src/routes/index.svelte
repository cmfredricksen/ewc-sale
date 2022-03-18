<svelte:head>
	<title>Ely Watercolor Club | Home</title>
</svelte:head>

<div class="info">
	<h2>Wednesday July 20 - Sunday July 24 2022</h2>
	<h2>10am - 4pm</h2>
	<div class="location">
		<h2>401 N. Pioneer Rd.</h2>
		<p><a href="/directions">directions</a></p>
	</div>
</div>

<div class="gallery">
	<img class="img-size" src="/images/monet.jpg" alt="painting" title="Claude Monet" />
	<img class="img-size" src="/images/kandinsky.jpg" alt="painting" title="Vassily Kandinsky" />
	<img class="img-size" src="/images/cassett.jpg" alt="painting" title="Mary Cassett" />
	<img class="img-size" src="/images/kahlo.jpg" alt="painting" title="Frieda Kahlo" />
	<img class="img-size" src="/images/manet.jpg" alt="painting" title="Edouard Manet" />
	<div class="info-box img-size">
		<h2>Please Join Us!</h2>
		<h3>100's of Paintings by Local Artists!</h3>
		<p>Cards & Paintings are all Original and one of a kind!</p>

		<h2>Featuring Art by:</h2>
		<ul>
			<li>Sandy Brandley</li>
			<li>Bonnie Dufresne</li>
			<li>Nancy Ensley</li>
			<li>Chris Fredricksen</li>
			<li>Scott King</li>
			<li>Sue Mischke</li>
			<li>Cecilia Rolando</li>
			<li>Holly Rom</li>
			<li>Claire Taylor</li>
			<li>John Weidermann</li>
		</ul>

		<h2>Location:</h2>
		<h3>Ely Arts & Heritage Center at Pioneer Mine</h3>
		<p>401 N. Pioneer Road</p>
		<a href="/directions">directions</a>
		<p>We accept cash, checks & credit cards.</p>
	</div>
</div>

<style>
	h2 {
		color: var(--clr-gold);
		margin-bottom: 1rem;
	}

	h3 {
		margin-bottom: 1rem;
	}
	.info {
		text-align: center;
		padding: 1.5rem 0;
	}

	.location {
		display: flex;
		align-items: baseline;
		justify-content: center;
	}

	.location a {
		margin: 0 1rem;
		font-size: small;
	}

	p {
		margin-bottom: 1rem;
		margin-top: 1rem;
	}

	.gallery {
		display: flex;
		flex-wrap: wrap;
		margin: 0 auto;
		justify-content: space-around;
	}

	img {
		width: 100%;
		margin: 2rem;
		box-shadow: 2px 2px 1px #000;
	}

	.img-size {
		width: 40%;
	}

	.info-box {
		margin: 2rem;
	}

	li {
		list-style: none;
		margin: 0.5rem 0;
		font-family: var(--font-accent);
	}

	@media (max-width: 720px) {
		.img-size {
			width: 90%;
		}

		.info {
			padding: 1.5rem 0 0;
		}
	}
</style>
