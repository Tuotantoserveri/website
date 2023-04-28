<main id="about">
	<div class="wrapper">
		<h2><span class="main-orange">Erittäin laadukkaita</span> palveluita</h2>
		<p class="lead">
			hihihaa en tiiä mitä kirjotan tähä :(
		</p>
	</div>
</main>

<style>
	main {
		min-height: 100vh;
		height: max-content;
		background-color: black;
		color: white;
		display: flex;
		justify-content: center;
		padding-top: 10rem;
	}

	h2 {
		margin: 0;
		font-size: 4rem;
		max-width: 70vw;
	}

	p {
		font-size: 1.8rem;
	}

	.feature {
		margin-block-start: 0em;
		margin-block-end: 0em;
	}

	.lead {
		max-width: 70vw;
		line-height: 3.5rem;
        font-size: 2.4rem;
	}

	.grid {
		display: grid;
		grid-template-columns: 35vw 35vw;
		grid-template-rows: auto;
		gap: 54px 48px;
		margin-bottom: 72px;
        margin-top: 48px;
	}

	.box {
		display: flex;
		flex-direction: column;
		gap: 16px;
	}

	h3 {
		font-size: 2.5rem;
		margin: 0;
		margin-block-end: 0em;
	}

    .m-hidden {
        display: flex;
    }

    .m-shown {
        display: none!important;
    }

    @media (max-width: 850px) {
        .grid {
            grid-template-columns: 70vw;
        }
        .m-hidden {
            display: none!important;
        }
        .m-shown {
            display: flex;
        }
        p {
            font-size: 1.2rem;
        }
        .lead {
            font-size: 1.6rem;
            line-height: 2.5rem;
        }
        h2 {
            font-size: 3rem;
        }
    }

</style>
