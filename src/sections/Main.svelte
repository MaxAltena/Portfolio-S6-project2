<script>
	import { link } from "svelte-routing";
	import { fly, fade } from "svelte/transition";
	import ProductShowcase from "../components/ProductShowcase.svelte";
	import { name, semester, fullName } from "../utils/stores";

	let delay = 0;
	let animation = { y: 40, duration: 250 };
</script>

<main class="container" out:fade="{{ duration: 300 }}">
	<div class="small-medium-only" role="presentation">
		<h1>
			<a href="#top" name="top">.</a>
			{$name} {$semester}
		</h1>
		<small>{$fullName}</small>

		<hr />
	</div>

	<h1 in:fly="{{ ...animation, delay: (delay = 0) }}">
		<a href="#opdracht" name="opdracht">.</a>
		Opdracht
	</h1>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">
		PIDZ1 wil een systeem maken wat diverse problemen van ZZP’ers in de zorg aanpakt. De oplossing hiervoor is WijPIDZ,
		een platform met verschillende componenten. Vandaar gingen wij, De Sigaar2, als ICT & Media Design’ers op onderzoek
		uit hoe we deze componenten gingen bedenken en ontwerpen.
	</p>

	<h2 in:fly="{{ ...animation, delay: (delay += 50) }}">Probleemstelling</h2>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">
		Er zijn verschillende problemen die bijdrage aan de behoefte om onderling met elkaar te communiceren en kennis te
		delen. Denk hierbij aan de volgende punten:
		Contact met collega’s, verbinding met zorginstellingen en bemiddelaars, dezelfde onderwerpen op social media. Deze
		problemen zijn uit onderzoek gekomen dat PIDZ heeft gedaan en waarna deze resultaten zijn gedeeld met ons.
	</p>

	<h2 in:fly="{{ ...animation, delay: (delay += 50) }}">Design challenge</h2>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">Ontwerp een web oplossing voor experts en ZZP’ers in de zorg die
		aangesloten zijn bij PIDZ om onderling kennis te kunnen delen en in contact te stellen over onderwerpen waar ze hulp
		bij nodig hebben.</p>

	<h2 in:fly="{{ ...animation, delay: (delay += 50) }}">Doelstelling</h2>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">
		Het doel van dit project is om een component te ontwerpen dat in het WijPIDZ platform komt te staan. Dit component
		zal design guidelines van het PIDZ platform volgen. Verder zal het component moeten worden uitgewerkt en getest zijn
		als een ontwerp en uiteindelijk als er tijd voor is ook als een product.
	</p>

	<hr in:fly="{{ ...animation, delay: (delay += 50) }}" />

	<h1 in:fly="{{ ...animation, delay: (delay += 50) }}">
		<a href="#producten" name="producten">.</a>
		Producten
	</h1>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">
		Weten hoe de producten tot stand zijn gekomen? Bekijk dan even de aanpak in
		<a href="leeswijzer/" use:link>de leeswijzer.</a>
	</p>

	<ProductShowcase {animation} {delay} />

	<hr in:fly="{{ ...animation, delay: (delay += 50) }}" />

	<h1 in:fly="{{ ...animation, delay: (delay += 50) }}">
		<a href="#reflectie" name="reflectie">.</a>
		Reflectie
	</h1>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">
		Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quo, distinctio fugiat. Nostrum eaque saepe odio ut
		dignissimos consequatur magnam sequi, mollitia in laboriosam, eum optio vel maxime nisi et eligendi.
	</p>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea in iusto inventore corporis amet dolor quidem
		tempore vitae nostrum nulla! Neque quia quaerat voluptatem optio aliquid, eligendi rem ipsa accusamus?
	</p>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias illum praesentium sed repellat minima suscipit
		nihil reprehenderit porro, ex assumenda harum, voluptatem tempora iste. Excepturi repellat doloribus voluptates
		aut velit.
	</p>
</main>

<style>
	main {
		padding-top: 100px;
		padding-bottom: 50px;
		display: flex;
		flex-direction: column;
		align-items: baseline;
	}

	.small-medium-only {
		display: none;
		width: 100%;
	}

	h1,
	h2 {
		position: relative;
	}

	h1 {
		margin: 0;
		color: var(--accent);
		transition: color var(--transition-speed) var(--transition-timing);
		font-size: 1.5em;
	}

	h2 {
		margin: 0;
		margin-top: 1rem;
		color: var(--accent);
		transition: color var(--transition-speed) var(--transition-timing);
		font-size: 1.25em;
	}

	h2::before {
		content: "⤴️";
		display: inline-block;
		transform: rotate(90deg);
		margin-right: 0.25rem;
	}

	a[name] {
		position: absolute;
		top: -100px;
		opacity: 0;
		pointer-events: none;
	}

	p {
		margin: 0;
		margin-top: 0.5rem;
		color: var(--on-primary);
		transition: all var(--transition-speed) var(--transition-timing);
		word-spacing: 1px;
		text-align: justify;
	}

	@media only screen and (max-width: 425px) {
		main {
			padding-top: 200px;
		}
	}

	@media only screen and (max-width: 770px) {
		.small-medium-only {
			display: block;
		}
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
