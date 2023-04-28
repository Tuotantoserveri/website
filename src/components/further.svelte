<main id="about">
	<div class="wrapper">
		<h1><u>Usein kysyttyä</u></h1>
		<p class="lead">
			Onko sinulla mielessä jokin muu asia? <a href="mailto:hei@tuotantoserveri.fi" class="main-orange"
				>Laita meille sähköpostia →</a
			>
		</p>

		<div class="grid">
			<div class="box">
				<h3>Tuotantoserveri?</h3>
				<p class="answer">
					Surkee läppä (tietäjät tietää)
				</p>
			</div>
			<div class="box">
				<h3>Kuka ihme lähti tekee tätä?</h3>
				<p class="answer">
					Arvaa (tai selvitä)
				</p>
			</div>
			<div class="box">
				<h3>Pitääkö olla huolissaan?</h3>
				<p class="answer">
					Tuskinpa (toivottavasti)
				</p>
			</div>
		</div>

		<h1><u>Yhteistyökumppanit</u></h1>
		<p class="lead">
			Tulisitko sinäkin mukaan meidän toimintaan? <a href="mailto:hei@tuotantoserveri.fi" class="main-orange"
				>Laita meille sähköpostia →</a
			>
		</p>
		<div style="display: flex; align-items: center; gap: 3rem; flex-wrap: wrap; max-width: 90vw">
			
		</div>
	</div>
</main>

<style>
	main {
		height: max-content;
		background-color: black;
		color: white;
		display: flex;
		justify-content: center;
		padding-top: 3rem;
		padding-bottom: 7rem;
	}

	h1 {
		margin: 0;
		font-size: 4rem;
		width: 90vw;
	}

	p {
		font-size: 1.8rem;
	}

	.answer {
		margin-block-start: 0em;
		margin-block-end: 0em;
		font-size: 1.1rem;
	}

	.lead {
		width: 90vw;
		line-height: 3.5rem;
		font-size: 1.8rem;
	}

	.grid {
		display: grid;
		grid-template-columns: 30vw 30vw 30vw;
		grid-template-rows: auto;
		gap: 24px 24px;
		margin-bottom: 72px;
		margin-top: 48px;
	}

	.box {
		display: flex;
		flex-direction: column;
		gap: 8px;
		border: 2px solid var(--main-orange);
		padding: 1rem;
	}

	h2 {
		font-size: 2.5rem;
		margin: 0;
		margin-block-end: 0em;
	}

	.m-hidden {
		display: flex;
	}

	.m-shown {
		display: none !important;
	}

	h3 {
		margin-block-start: 0em;
		margin-block-end: 0em;
		font-size: 1.3em;
	}

	@media (max-width: 850px) {
		.grid {
			grid-template-columns: 90vw;
		}
		.m-hidden {
			display: none !important;
		}
		.m-shown {
			display: flex;
		}
	}
</style>
