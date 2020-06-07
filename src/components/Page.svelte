<script>
	export let product;
</script>

{#if product.link === 'kritische-vragen'}
	<h2>Aanleiding</h2>
	<p>
		Om het probleem van de opdrachtgever beter te begrijpen en daardoor een beter probleemanalyse op te kunnen stellen worden er kritische vragen opgesteld.
	</p>
	<h2>Aanpak</h2>
	<p>
		Om kritische vragen op te stellen wordt er gekeken naar welke informatie er nodig is om aan de slag te gaan met het project.
	</p>
	<h2>Uitvoering</h2>
	<p>
		De opgestelde kritische vragen zijn per mail met de hele groep opgestuurd. De meeste vragen heeft de opdrachtgever beantwoord behalve enkele vragen die niet goed geformuleerd waren of die niet duidelijk waren.
	</p>
	<h2>Conclusie</h2>
	<p>
		Hieronder geselecteerde vragen die beantwoorden waren in de mail en een sessie om vragen te stellen.
	</p>
	<ol>
		<li>
			<strong>Is er al een beeld bij hoe het delen van kennis zou moeten worden weergeven? Zo ja, in wat voor format? Denk hierbij aan Reddit, Stackoverflow, Slack of een forum. Deze informatie is nodig zodat het product niet afwijkt van de verwachtingen van PIDZ.</strong>
			<span>De opdrachtgever heeft graag beargumenteerd advies hierover.</span>
		</li>
		<li>
			<strong>Mogen we 10 vragen die gesteld worden door de ZZP’ers? Deze informatie is nodig om er rekening mee te kunnen houden hoelang en wat de context van de vragen zijn en hoe de ZZP'ers op een andere manier het antwoord hadden kunnen beantwoorden.</strong>
			<span>Hier had de opdrachtgever geen duidelijk antwoord op. Deze antwoorden zijn tevens gevonden in facebook groepen.</span>
		</li>
		<li>
			<strong>Hoe wordt de communicatie nu gedaan (Whatsapp, mail, andere platformen)? En wat zijn de voor- en nadelen hiervan? Deze informatie is nodig om erachter te komen hoe formeel en op welke manier de informatie met elkaar gecommuniceerd wordt.</strong>
			<span>Momenteel is er geen vaste plek waar de ZZP'ers zich bevinden. Er zijn groepen op facebook en bijvoorbeeld zzp-forums.</span>
		</li>
		<li>
			<strong>Hoe breed is het veld waarin de zzp-ers zich bevinden waarvoor de applicatie bedoeld is (mantelzorg, ggz, thuiszorg)? Deze informatie is nodig zodat we weten of we categorieën moeten toevoegen in het ontwerp.</strong>
			<span>Er zijn verschillende rollen binnen PIDZ. Zo zijn er helpenden, verzorgenden, verpleegkundigen, gespecialiseerde verpleegkundigen en begeleiders. De opdrachtgevers zijn verpleeg- en verzorgingshuizen, ziekenhuizen, GGZ en de thuis- en gehandicaptenzorg.</span>
		</li>
		<li>
			<strong>In welke maten moet er rekening gehouden worden wat betreft integratie van dit onderdeel binnen het WijPIDZ platform? Deze informatie kunnen we gebruiken omdat dit invloed kan hebben op het ontwerp.</strong>
			<span>Er moet aan de PIDZ-huisstijl worden voldaan.</span>
		</li>
		<li>
			<strong>Op welke manier worden inkomsten gegenereerd met dit platform? Voorbeelden en waarom. (reclames, lease, kickback, ads, etc.) Deze informatie kunnen wij gebruiken zodat we kunnen nadenken over een marketing en business aspect over het product.</strong>
			<span>De opdrachtgever heeft graag beargumenteerd advies hierover.</span>
		</li>
		<li>
			<strong>Is het platform bedoeld voor alle devices (mobiel, tablet, pc)?</strong>
			<span>Ja.</span>
		</li>
	</ol>
	<h2>Verantwoording</h2>
	<p>Vragen zijn opgesteld samen met Dylano Hartman en Mark Hendriks.</p>
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
