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
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem veniam blanditiis, natus velit nihil in! Ex,
		maiores blanditiis in impedit quisquam dolor ratione odit ducimus obcaecati itaque suscipit natus sunt!
	</p>

	<h2 in:fly="{{ ...animation, delay: (delay += 50) }}">Probleemstelling</h2>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">
		Lorem, ipsum dolor sit amet consectetur adipisicing elit. Neque perferendis hic minus expedita laboriosam
		repellat molestias sint, fugiat unde, nemo, ad laborum itaque doloremque. Quidem unde ipsum incidunt consectetur
		pariatur?
	</p>

	<h2 in:fly="{{ ...animation, delay: (delay += 50) }}">Hoofdvraag</h2>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">Goeie vraag 🤷‍♂️</p>

	<h2 in:fly="{{ ...animation, delay: (delay += 50) }}">Doelstelling</h2>

	<p in:fly="{{ ...animation, delay: (delay += 25) }}">
		Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maiores autem, iusto libero iure, reprehenderit
		facilis ut qui molestias ullam, fugiat obcaecati animi possimus quibusdam cum mollitia eligendi ad sit ea!
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
