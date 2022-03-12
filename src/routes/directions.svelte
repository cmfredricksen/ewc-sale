<svelte:head>
	<title>Ely Watercolor Club | Directions</title>
</svelte:head>

<div class="directions">
	<h2>How to find us!</h2>

	<h2>401 N. Pioneer Road, Ely MN</h2>

	<div class="map-box">
		<div class="mapouter">
			<div class="gmap_canvas">
				<iframe
					width="600"
					height="500"
					id="gmap_canvas"
					src="https://maps.google.com/maps?q=401%20N.%20Pioneer%20Rd&t=&z=13&ie=UTF8&iwloc=&output=embed"
					frameborder="0"
					scrolling="no"
					marginheight="0"
					marginwidth="0"
					title="map"
				/><a href="https://putlocker-is.org">putlocker</a><br /><style>
					.mapouter {
						position: relative;
						text-align: right;
						height: 500px;
						width: 600px;
					}
				</style><a href="https://www.embedgooglemap.net">add google maps html</a><style>
					.gmap_canvas {
						overflow: hidden;
						background: none !important;
						height: 500px;
						width: 600px;
					}
				</style>
			</div>
		</div>
	</div>
</div>

<style>
	.directions {
		padding: 2rem 1.5rem;
	}

	h2 {
		margin-bottom: 1rem;
	}

	@media (max-width: 720px) {
		.directions {
			padding: 2.5rem 0.5rem;
		}

		h2 {
			text-align: center;
		}
		.map-box {
			text-align: center;
			overflow: auto;
			margin-top: 2.5rem;
			padding-bottom: 95%;
			position: relative;
			height: 0;
		}
		.map-box iframe {
			text-align: center;
			left: 0;
			top: 0;
			height: 100%;
			width: 100%;
			position: absolute;
		}
	}
</style>
