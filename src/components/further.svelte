<main id="about">
	<div class="wrapper">
		<h2><u>Meidän tiimi</u></h2>
		<p class="lead">
			Kaikki meidät saa kiinni yhteisestä sähköpostista, tai sitten jokaisen omasta: <a href="mailto:hei@tuotantoserveri.fi" class="main-orange"
			>hei@tuotantoserveri.fi</a
			>
		</p>

		<div class="grid">
			<div class="box">
				<h3>Henkilö 1</h3>
				<p class="answer">
					kdgjs
				</p>
			</div>
			<div class="box">
				<h3>Henkilö 2</h3>
				<p class="answer">
					jefdkf
				</p>
			</div>
			<div class="box">
				<h3>Henkilö 3</h3>
				<p class="answer">
					juuuuu
				</p>
			</div>
			<div class="box">
				<h3>Henkilö 4</h3>
				<p class="answer">
					kukkuu
				</p>
			</div>
		</div>

		<h2><u>Asiakkaat</u></h2>
		<p class="lead">
			tähän joku nerokas teksti <a href="mailto:hei@tuotantoserveri.fi" class="main-orange"
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
		grid-template-columns: 22.5vw 22.5vw 22.5vw 22.5vw;
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
		text-align: center;
	}

	h2 {
		font-size: 2.5rem;
		margin: 0;
		margin-block-end: 0em;
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
