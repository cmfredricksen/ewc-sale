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
	<img class="img-size" src="/images/Diane-Levar.jpg" alt="painting" title="Diane Levar" />
	<img class="img-size" src="/images/Scott-King.jpg" alt="painting" title="Scott King" />
	<img class="img-size" src="/images/Cecilia-Rolando.jpg" alt="painting" title="Cecilia Rolando" />
	<img class="img-size" src="/images/chris-fredricksen.jpg" alt="painting" title="Chris Fredricksen" />
	<img class="img-size" src="/images/Bonnie-Dufresne.jpg" alt="painting" title="Bonnie Dufresne" />
	<div class="info-box img-size">
		<h2>Please Join Us!</h2>
		<h3>100's of Paintings by Local Artists!</h3>
		<p>All Paintings are Original and one of a kind!</p>
		<p>Greeting Cards & Gift Bags also available!</p>
		<p></p>

		<h2>Featuring Art by:</h2>
		<ul>
			<li>Sandy Brandley</li>
			<li>Bonnie Dufresne</li>
			<li>Chris Fredricksen</li>
			<li>Scott King</li>
			<li>Sue Mischke</li>
			<li>Cecilia Rolando</li>
			<li>Holly Rom</li>
			<li>Claire Taylor</li>
			<li>John Weidemann</li>
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

	.info h2 {
		color: var(--clr-white);
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
		justify-content: space-evenly;
	}

	img {
		width: 100%;
		height: auto;
		margin: 2rem 1rem;
		box-shadow: 2px 2px 1px #000;
	}

	.img-size {
		width: 42%;
		height: auto;
	}

	.info-box {
		margin: 2rem 1rem;
	}

	li {
		list-style: none;
		margin: 0.5rem 0;
		font-family: var(--font-accent);
	}
	
	@media (max-width: 1068px) {
		.img-size {
			width: 85%;
		}
	}

	@media (max-width: 720px) {
		.img-size {
			width: 90%;
		}

		.info {
			padding: 1.5rem 0 0;
		}

		.info-box {
			margin: 1rem;
		}
	}
</style>
