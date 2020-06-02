<script>
	export let product;
</script>

{#if product.link === 'kritische-vragen'}
	<h2>Aanleiding</h2>
	<p>

	</p>
	<h2>Aanpak</h2>
	<p>

	</p>
	<h2>Conclusie</h2>
	<p>

	</p>
	<h2>Verantwoording</h2>
	<p></p>
{:else if product.link === 'probleemanalyse'}
	<h2>Aanleiding</h2>
	<p>

	</p>
	<h2>Aanpak</h2>
	<p>

	</p>
	<h2>Conclusie</h2>
	<p>

	</p>
	<h2>Verantwoording</h2>
	<p>

	</p>
{:else if product.link === 'projectplan'}
	<h2>Aanleiding</h2>
	<p>

	</p>
	<h2>Aanpak</h2>
	<p>

	</p>
	<h2>Conclusie</h2>
	<p>

	</p>
	<h2>Verantwoording</h2>
	<p>

	</p>
{:else}
	<p>Huh, product niet gevonden? Probeer het later nog eens!</p>
{/if}

<style>
	h2 {
		margin: 0;
		color: var(--accent);
		transition: color var(--transition-speed) var(--transition-timing);
		font-size: 1.25em;
	}

	p {
		margin: 0;
		margin-top: 0.5rem;
		margin-bottom: 1rem;
		color: var(--on-primary);
		transition: all var(--transition-speed) var(--transition-timing);
		word-spacing: 1px;
		text-align: justify;
	}

	a {
		cursor: pointer;
		color: var(--on-primary);
		transition: color calc(var(--transition-speed) / 2) var(--transition-timing);
		text-decoration: none;

		padding: 4px;
		position: relative;
	}

	a::after {
		content: "";
		position: absolute;
		bottom: 0;
		left: 0;
		right: 0;
		width: 100%;
		height: 4px;
		border-radius: 4px;
		background: var(--accent);
		z-index: -1;
		transition: height calc(var(--transition-speed) / 2) var(--transition-timing),
			background var(--transition-speed) var(--transition-timing);
	}

	a:hover::after,
	a:active::after {
		height: 100%;
	}

	a:hover,
	a:active {
		color: var(--primary);
	}
</style>
