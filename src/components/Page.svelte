<script>
	import Image from "./Image.svelte";

	export let product;
</script>

{#if product.link === 'kritische-vragen'}
	<h2>Aanleiding</h2>
	<p>
		Om het probleem van de opdrachtgever beter te begrijpen en daardoor een beter probleemanalyse op te kunnen
		stellen worden er kritische vragen opgesteld.
	</p>
	<h2>Aanpak</h2>
	<p>
		Om kritische vragen op te stellen wordt er gekeken naar welke informatie er nodig is om aan de slag te gaan met
		het project.
	</p>
	<h2>Uitvoering</h2>
	<p>
		De opgestelde kritische vragen zijn per mail met de hele groep opgestuurd. De meeste vragen heeft de
		opdrachtgever beantwoord behalve enkele vragen die niet goed geformuleerd waren of die niet duidelijk waren.
	</p>
	<h2>Conclusie</h2>
	<p>Hieronder geselecteerde vragen die beantwoorden waren in de mail en een sessie om vragen te stellen.</p>
	<ol>
		<li>
			<strong>
				Is er al een beeld bij hoe het delen van kennis zou moeten worden weergeven? Zo ja, in wat voor format?
				Denk hierbij aan Reddit, Stackoverflow, Slack of een forum. Deze informatie is nodig zodat het product
				niet afwijkt van de verwachtingen van PIDZ.
			</strong>
			<br />
			<span>De opdrachtgever heeft graag beargumenteerd advies hierover.</span>
		</li>
		<li>
			<strong>
				Mogen we 10 vragen die gesteld worden door de ZZP'ers? Deze informatie is nodig om er rekening mee te
				kunnen houden hoelang en wat de context van de vragen zijn en hoe de ZZP'ers op een andere manier het
				antwoord hadden kunnen beantwoorden.
			</strong>
			<br />
			<span>
				Hier had de opdrachtgever geen duidelijk antwoord op. Deze antwoorden zijn tevens gevonden in facebook
				groepen.
			</span>
		</li>
		<li>
			<strong>
				Hoe wordt de communicatie nu gedaan (Whatsapp, mail, andere platformen)? En wat zijn de voor- en nadelen
				hiervan? Deze informatie is nodig om erachter te komen hoe formeel en op welke manier de informatie met
				elkaar gecommuniceerd wordt.
			</strong>
			<br />
			<span>
				Momenteel is er geen vaste plek waar de ZZP'ers zich bevinden. Er zijn groepen op facebook en
				bijvoorbeeld zzp-forums.
			</span>
		</li>
		<li>
			<strong>
				Hoe breed is het veld waarin de zzp-ers zich bevinden waarvoor de applicatie bedoeld is (mantelzorg,
				ggz, thuiszorg)? Deze informatie is nodig zodat we weten of we categorieën moeten toevoegen in het
				ontwerp.
			</strong>
			<br />
			<span>
				Er zijn verschillende rollen binnen PIDZ. Zo zijn er helpenden, verzorgenden, verpleegkundigen,
				gespecialiseerde verpleegkundigen en begeleiders. De opdrachtgevers zijn verpleeg- en verzorgingshuizen,
				ziekenhuizen, GGZ en de thuis- en gehandicaptenzorg.
			</span>
		</li>
		<li>
			<strong>
				In welke maten moet er rekening gehouden worden wat betreft integratie van dit onderdeel binnen het
				WijPIDZ platform? Deze informatie kunnen we gebruiken omdat dit invloed kan hebben op het ontwerp.
			</strong>
			<br />
			<span>Er moet aan de PIDZ-huisstijl worden voldaan.</span>
		</li>
		<li>
			<strong>
				Op welke manier worden inkomsten gegenereerd met dit platform? Voorbeelden en waarom. (reclames, lease,
				kickback, ads, etc.) Deze informatie kunnen wij gebruiken zodat we kunnen nadenken over een marketing en
				business aspect over het product.
			</strong>
			<br />
			<span>De opdrachtgever heeft graag beargumenteerd advies hierover.</span>
		</li>
		<li>
			<strong>Is het platform bedoeld voor alle devices (mobiel, tablet, pc)?</strong>
			<br />
			<span>Ja.</span>
		</li>
	</ol>
	<h2>Verantwoording</h2>
	<p>Vragen zijn opgesteld samen met Dylano Hartman en Mark Hendriks.</p>
	<!-- Document: https://docs.google.com/document/d/1B72THVl9YhjZ31yR2HV3yRjraJ3dRZxR8hy1BSFYTHg/ -->
{:else if product.link === 'individuele-analyse'}
	<h2>Aanleiding</h2>
	<p>Om de opdracht goed te analyseren is er een individuele analyse gemaakt. Zo konden gedachtes van mijn hoofd naar (digitaal) papier worden geschreven om deze te vast te leggen. Dit heeft ieder groepslid individueel gedaan om zo onze eigen kijk op de opdracht op te schrijven.</p>
	<h2>Aanpak</h2>
	<p>Om een goede eerste probleemanalyse te doen moet er gekeken worden naar: de opdracht, de probleemstelling, het doel, de onderzoeksaspecten, de uitvoering van het project, de aanpak van het project, het gewenste eindresultaat en de oplossing voor het probleem.</p>
	<h2>Uitvoering</h2>
	<p>Ik ben begonnen met de opzet te pakken van het vorige project, dus de vragen zoals; wat is de probleemstelling, wat is het doel en wat wordt de aanpak van het project. Deze beantwoord en een verhaaltje van gemaakt om het een doorlopend verhaal te maken. Als je het verhaaltje wilt lezen kan dat in dit <a href="https://docs.google.com/document/d/12m4le8-qWBinYBItjhjvGriKU2Cqo-Csh8lO5WTwolY/" target="_blank" rel="noopener">document</a>.</p>
	<h2>Conclusie</h2>
	<p>Er zijn verschillende problemen die bijdrage aan de behoefte om onderling met elkaar te communiceren en kennis te delen. Denk hierbij aan de volgende punten:</p>
	<ul>
		<li>Contact met collega's. ZZP'ers voelen zich weinig verbonden met andere ZZP'ers. Ze zoeken dit wel, bijvoorbeeld door elkaar te treffen op sociale media, WhatsApp-groepen, netwerkborrels of anderszin.</li>
		<li>Verbinding met zorginstellingen en bemiddelaars. ZZP'ers voelen zich niet aangesloten bij een team.</li>
		<li>Dezelfde onderwerpen. Op sociale media zoals Facebook(groepen) gaat het vaak om steeds dezelfde onderwerpen, zoals de opstart van een bedrijf.</li>
	</ul>
	<p>Deze problemen zijn uit onderzoek gekomen dat PIDZ heeft gedaan en waarna deze resultaten zijn gedeeld met ons.</p>
	<p>Het doel van dit project is om een component te ontwerpen dat in het WijPIDZ platform komt te staan. Dit component zal design guidelines van het PIDZ platform volgen. Verder zal het component moeten worden uitgewerkt en getest zijn als een ontwerp en uiteindelijk als er tijd voor is ook als een product.</p>
	<h2>Verantwoording</h2>
	<p>Volledige uitgevoerd door mijzelf.</p>
	<!-- Document: https://docs.google.com/document/d/12m4le8-qWBinYBItjhjvGriKU2Cqo-Csh8lO5WTwolY/ -->
{:else if product.link === 'projectplan'}
	<h2>Aanleiding</h2>
	<p>Om het traject inzichtelijker te maken voor de opdrachtgever en de onderwijsinstelling is er een projectplan gemaakt waarbij het duidelijk moet worden voor iedereen wat er de komende 9 weken zou worden gedaan. Niet alleen handig voor andere, maar ook zeker voor jezelf en je groep.</p>
	<h2>Aanpak</h2>
	<p>Door ieder groepslid een eigen stukje te laten doen kan het document sneller gerealiseerd worden. Hierna wordt er met de groep overheen gekeken om zo voor iedereen duidelijke te krijgen wat het project gaat inhouden en hoe er te werk wordt gegaan.</p>
	<h2>Uitvoering</h2>
	<p>Ik ben bezig geweest met een klein stukje over het bedrijf waarna ik verder ben gegaan aan de onderzoeksvragen en tussenproducten van het project. Daarna ben ik nog bezig geweest met het opschrijven van mogelijk risico's bij dit project voortvloeiend vanuit de opdrachtgever (PIDZ) en de COVID-19 situatie. Als laatste is er een scope gemaakt om aan te geven wat er wel en niet wordt gedaan. Uiteindelijk heb ik nog een document gemaakt die presenteerbaar is aan de opdrachtgever en andere belanghebbende en deze is <a href="https://drive.google.com/file/d/1W3pQmaGTDD5zAzJbFJD6kxCq9ikSFPGc/" target="_blank" rel="noopener">hier</a> te vinden.</p>
	<Image imgURL="https://i.gyazo.com/17c2a92ba8880c5d0814fe70da46102c.jpg" imgALT="Projectplan document" linkURL="https://drive.google.com/file/d/1W3pQmaGTDD5zAzJbFJD6kxCq9ikSFPGc/" />
	<h2>Conclusie</h2>
	<p>De opdracht, probleemstelling en het doel van het project zijn redelijk hetzelfde gebleven als in de <a href="https://portfolio.maxaltena.com/S6/project2/individuele-analyse/">individuele analyse</a>. De onderzoeksvragen en de tussenproducten zijn daarnaast wel wat bijgescherpt door de behoefte van de opdrachtgever waar de volgende punten uitkwamen:</p>
	<ul>
		<li><strong>Wat doet de concurrentie?</strong> - Met deze vraag wordt er te weten gekomen wat de concurrentie al heeft en wat er mist. Dit zal gedaan worden door middel van een concurrentie analyse. Vanaf dit punt kunnen er concepten worden bedacht die aansluiten bij de gebruiker, door het onderzoek gedaan door PIDZ, en die meer bieden dan wat de concurrent heeft, door het de concurrentie analyse.</li>
		<li><strong>Wat zijn USP's van de concepten?</strong> - Om de waarde van het product in te kunnen schatten, zijn de USP's van de concepten erg belangrijk te analyseren. Hierbij kan ook al gekeken worden naar een mogelijk business model.</li>
		<li><strong>Wat gaat het product inhouden?</strong> - Om te weten wat het product is, moet er gekeken worden wat het product inhoudt door middel van proof of concepts. Hiermee kan er een design specificatie worden gemaakt waarmee er prototypes kunnen worden gemaakt.</li>
		<li><strong>Is het product duidelijk voor de gebruiker?</strong> - Om te verifiëren of het product zinvol is worden de prototypes getest door middel van gebruikerstesten. Hieruit komt een testrapport waarmee er verbeteringen kunnen worden doorgevoerd en een advies kan worden gegeven over mogelijk vervolgstappen.</li>
	</ul>
	<h2>Verantwoording</h2>
	<p>
		Gemaakt samen met Dylano Hartman en Mark Hendriks. Waar ik aan heb gewerkt: "Het bedrijf", "Onderzoeksvragen en tussenproducten", "Risico's" en "Scope". Ontwerp van document en uiteindelijke oplevering gedaan door	mijzelf.
	</p>
	<!-- Document: https://docs.google.com/document/d/1_JQpZ9trWjq_z4eL6in5pw7py-tElKngKVSJSM3Tukk/ -->
	<!-- Product: https://drive.google.com/file/d/1W3pQmaGTDD5zAzJbFJD6kxCq9ikSFPGc/ -->
{:else if product.link === 'concurrentie-analyse'}
	<h2>Aanleiding</h2>
	<p>
		Om te weten te komen wat het uiteindelijke component in het WijPIDZ product voor het delen van kennis gaat
		inhouden en wat voor vorm deze zal hebben zal een concurrentie analyse worden gedaan. Met deze analyse wordt
		gekeken naar welke verschillende vormen er zijn, wat de voor- en nadelen hiervan zijn en waar rekening mee moet
		worden gehouden tijdens het bedenken en ontwerpen van het component. Hieruit zullen uiteindelijk mogelijke USP's
		komen, de sterktes en zwaktes van de concurrenten en dus ook de kansen en gevaren van het component.
	</p>
	<h2>Aanpak</h2>
	<p>
		Het eerste dat er gedaan moet worden om concurrenten te kunnen analyseren is het vinden van concurrenten op
		basis van het product of service dat wordt geanalyseerd. Dit wordt gedaan nadat het product of service dat moet
		worden vergeleken is vastgesteld. Hierbij wordt dan gekeken naar diverse punten, denk hier bijvoorbeeld aan
		prijs, kwaliteit en service. Het analyseren van de concurrenten is het belangrijkste en meeste werk, zo moet er
		per concurrent gekeken worden naar de opgestelde punten en hoe ze hierop scoren ten opzichte van de andere. Per
		punt wordt er ook een kleine toelichting gegeven om zo de score van het punt te onderbouwen. Als laatste kan er
		dan bestudeerd worden welke sterke en zwakke punten elke concurrent heeft. Hiermee kunnen mogelijke USP's
		verschijnen die het product of service uniek kunnen maken waarbij waarde kan worden gecreëerd.
	</p>
	<h2>Uitvoering</h2>
	<p>Begonnen met het kijken naar punten om te vergelijken:</p>
	<ul>
		<li><strong>Kosten</strong> - Mogelijke kosten voor het product moeten worden afgestemd op de behoefte van de gebruiker en de functionaliteit van het product.</li>
		<li><strong>Gebruiksvriendelijkheid</strong> - Gebruiksvriendelijkheid van het product is belangrijk voor het gebruik door de gebruiker omdat een product dat gemakkelijk in gebruik is vaker gebruik wordt.
		</li>
		<li><strong>Vorm</strong> - Zijn alle functionaliteiten die de gebruiker wil en verwacht verwerkt in het product? Denk hierbij aan gemakkelijk contact leggen met andere gebruikers.
		</li>
		<li><strong>Beschikbaarheid</strong> - Beschikbaarheid van het platform is handig voor de gebruiker, dan hoeft deze niet op een bepaald medium te zitten. Denk hierbij aan desktop, tablet en mobiel.
		</li>
		<li><strong>Delen van kennis
		</strong> - Het delen van kennis van de gebruiker en mogelijk vragen van de gebruiker moeten gemakkelijk kunnen worden beantwoord.</li>
		<li><strong>Contact met andere
		</strong> - Het starten van het contact en het in contact blijven met andere is erg belangrijk.
	</li>
	</ul>
	<p>Er is daarna gezocht naar directe en indirecte concurrenten, waar de volgende zijn uitgekomen:</p>
	<strong>Directe concurrenten</strong>
	<ul>
		<li><strong>Zorgzuster [1]</strong> - biedt hetzelfde aan als PIDZ, maar dan altijd in teams. Hierdoor is het een product wat in dezelfde soort markt zit als het product voor deze analyse.</li>
		<li><strong>PZP [2]</strong> - heeft een product waarbij er een community is. Hiermee worden ZZP'ers samengebundeld om vragen en problemen op te lossen.</li>
	</ul>
	<strong>Indirecte concurrenten</strong>
	<ul>
		<li><strong>WhatsApp [3]</strong> - er kan in contact worden gekomen met elkaar. Het richt zich niet zoals de directe concurrenten om ZZP'ers in de zorg.</li>
		<li><strong>Reddit [4]</strong> - is een platform waarbij het in contact staan met elkaar en het delen van kennis centraal staat. Hiermee is het een indirecte concurrent van het product.</li>
		<li><strong>StackExchange [5]</strong> - is een Q&A community waarbij er altijd wel een antwoord wordt gegeven op je vraag door een expert. Hierdoor het platform een concurrent in het delen van kennis en de verificatie van de antwoorden op vragen.</li>
	</ul>
	<h2>Conclusie</h2>
	<p>
		Er is geen directe concurrent met een platform waar er gemakkelijk kennis kan worden gedeeld en waar gebruikers
		gemakkelijk met elkaar in contact kunnen komen. Verder is er wel indirecte concurrentie van bestaande
		platformen, zoals Reddit en StackExchange, die de beoogde functionaliteiten van het product hebben. Als het
		product uiteindelijk soortgelijke functionaliteiten heeft als de indirecte concurrenten kan het op maat gemaakt
		worden voor de behoeftes van de gebruikers. Er zal dus wel gekeken kunnen worden naar hoe deze platformen deze
		functionaliteiten hebben verwerkt om inspiratie op te kunnen doen.
	</p>
	<p>Om de informatie gemakkelijk weer te geven is er een <a href="https://docs.google.com/spreadsheets/d/1DFWv3wQLvRPX58YyXRXndHF0lrpIogyqougcH7v60G0/" target="_blank" rel="noopener">excel sheet</a> voor de analyse en een <a href="https://drive.google.com/file/d/13YPzYN2J49ch8vXTIgwbCr7yEy55Re1Q/" target="_blank" rel="noopener">infographic</a> voor de onderzoeksaspecte en de conclusie gemaakt.</p>
	<Image imgURL="https://i.gyazo.com/5b8a9041b08f0b5b28d3ca754cc1645f.png" imgALT="Concurrentie analyse excel sheet" linkURL="https://docs.google.com/spreadsheets/d/1DFWv3wQLvRPX58YyXRXndHF0lrpIogyqougcH7v60G0/" />
	<Image imgURL="https://i.gyazo.com/48d11c01c2aa6e93b830f11bdc81f98f.jpg" imgALT="Concurrentie analyse infographic" linkURL="https://drive.google.com/file/d/13YPzYN2J49ch8vXTIgwbCr7yEy55Re1Q/" />
	<h2>Verantwoording</h2>
	<p>Volledige uitgevoerd door mijzelf.</p>
	<h2>Bronnen</h2>
	<ul>
		<li>[1] Zorgzuster. (z.d.). Geraadpleegd op 14 Mei 2020, van <a href="https://zorgzuster.nl/zzp/" target="_blank" rel="noopener">https://zorgzuster.nl/zzp/</a></li>
		<li>[2] PZP. (z.d.). Geraadpleegd op 14 Mei 2020, van <a href="https://pzp.nu/" target="_blank" rel="noopener">https://pzp.nu/</a></li>
		<li>[3] Whatsapp. (z.d.). Geraadpleegd op 14 Mei 2020, van <a href="https://whatsapp.com/" target="_blank" rel="noopener">https://whatsapp.com/</a></li>
		<li>[4] Reddit. (z.d.). Geraadpleegd op 14 Mei 2020, van <a href="https://reddit.com/" target="_blank" rel="noopener">https://reddit.com/</a></li>
		<li>[5] StackExchange. (z.d.). Geraadpleegd op 14 Mei 2020, van <a href="https://stackexchange.com/" target="_blank" rel="noopener">https://stackexchange.com/</a></li>
	</ul>
	<!-- Document: https://docs.google.com/document/d/18JZaBiCVn6ZHDkWyxh91wChU80UD8zaSPcBn2PFQWV8/ -->
	<!-- Spreadsheet: https://docs.google.com/spreadsheets/d/1DFWv3wQLvRPX58YyXRXndHF0lrpIogyqougcH7v60G0/ -->
	<!-- Product: https://drive.google.com/file/d/13YPzYN2J49ch8vXTIgwbCr7yEy55Re1Q/ -->
{:else if product.link === 'trend-analyse'}
	<h2>Aanleiding</h2>
	<p>
		Deze analyse wordt gedaan om verschillende trends te signaleren en te analyseren. Met de analyses van deze
		trends kan het concept worden vastgesteld waar er op dit moment vraag naar is.
	</p>
	<h2>Aanpak</h2>
	<p>
		Eerst zal er gekeken worden naar relevante trends in de zorg. Sommige trends zijn belangrijker en relevanter
		voor het concept. Bij elke trend wordt wat verteld over wat voor soort trend het is en hoe deze de markt
		verandert en/of wat het voor de markt betekent. Daarnaast wordt er gekeken naar de relevantie voor het product
		en de mogelijke kansen. Er wordt een enkele trend gekozen die het meest relevante is voor het product. Met deze
		trend zal er een consumer trend canvas gemaakt worden om alle informatie gemakkelijk weer te geven en
		inzichtelijk te maken.
	</p>
	<h2>Uitvoering</h2>
	<p>Er zijn trends gevonden die relevant zijn voor de zorg:</p>
	<strong>Andere samenwerkingsverbanden in de zorg</strong>
	<p>'Steeds minder zorgprofessionals werken exclusief in zorgorganisaties. Steeds vaker zien we ze terug als ZZP'ers in wijkteams en netwerken. Hun baan en invulling verandert daarmee drastisch. Zelfmanagement en veerkracht zijn de sleutelbegrippen voor deze zorgmedewerker nieuwe stijl. Hierdoor krijgen banen in de zorg een bredere invulling. Nieuwe taken zijn bijvoorbeeld het vervullen van een poortwachtersrol, signalering en het begeleiden van vrijwilligers.' [1]</p>
	<p>Deze trend is een macrotrend, wat betekent dat deze trend van 5 tot 10 jaar zal duren en verandering met zich meebrengt op consumenten niveau. Deze verandering zal zich uiten door bijvoorbeeld meer zelfstandige zorgprofessionals en andere taken voor deze zorgprofessionals.</p>
	<p>Mede doordat de zelfstandige zorgprofessional meer taken krijgt heeft hij/zij meer vragen over deze en andere taken is deze verandering relevant voor het product. Hier kan het product op inspelen door deze vragen makkelijk te laten worden gesteld en nog makkelijker te laten worden beantwoord door andere experts.</p>
	<strong>Technologie heeft de toekomst</strong>
	<p>'In vergelijking tot het buitenland, maakt de Nederlandse zorg veel gebruik van eHealth-toepassingen. Bij technologie in de zorg gaat het onder andere om beeldcommunicatie, monitoring, zelfzorg, robotisering, big data, edutainment en allerlei digitale platforms voor medische samenwerking. De zorgmedewerkers van de toekomst zijn opgegroeid in een sterk gedigitaliseerde omgeving en zij gebruiken technologie om meer zorg op afstand te leveren en om samen te werken met collega zorgprofessionals van verschillende organisaties.' [2]</p>
	<p>Deze trend is een megatrend, wat betekent dat deze trend van 10 tot 30 jaar zal duren en verandering met zich meebrengt op maatschappelijk niveau. Deze verandering zal zich uiten door bijvoorbeeld andere werkprocessen.</p>
	<p>Mede doordat het werkveld zich evolueert en meer gaat digitaliseren en meer met technologie gaat werken is dit iets wat relevant is voor het product. Zo kan hier bijvoorbeeld op ingespeeld worden door het gemakkelijker maken van het stellen van vragen. Hiernaast zullen er meer gebruikers online zijn doordat de zorg digitaliseert.</p>
	<strong>Kennis op maat maakt en deelt u samen</strong>
	<p>'De vraagstukken in de (ouderen)zorg worden steeds complexer. Het onderscheid tussen kennisontwikkelaars, -verspreiders en –gebruikers verdwijnt. Daarvoor in de plaats komt een grote variatie aan ontwikkelaars en gebruikers die in (vaak lokale/regionale) netwerkverbanden nauw samenwerken aan het ontwikkelen, aanbieden en gebruiken van kennis. Zorgorganisaties en maatschappelijke initiatieven geven ook steeds vaker zelf invulling aan de kennisfunctie.' [2]</p>
	<p>Deze trend is een microtrend, wat betekent dat deze trend tot 5 jaar zal gaan duren en verandering met zich meebrengt op marktniveau. Deze verandering zal zich uiten door bijvoorbeeld diverse platformen om kennis te delen over de zorg.</p>
	<p>Mede doordat er meer behoefte aan persoonlijke antwoorden is dit iets wat relevant is voor het product. Zo kan hier bijvoorbeeld op ingespeeld worden door het stellen van vragen en het platform uiteindelijk publiek maken.</p>
	<strong>Consumer Trend Canvas</strong>
	<p>Er is een consumer trend canvas[3] gemaakt voor de trend 'Kennis op maat maakt en deelt u samen' mede doordat deze trend erg relevant is voor het product.</p>
	<Image imgURL="https://i.gyazo.com/a97a72974c6792a7a76da371d54bde94.jpg" imgALT="Trend analyse consumer trend canvas" linkURL="https://drive.google.com/file/d/1LnfU7WJUgo9D2dLPDV0niNqsZnG-_kIJ/" />
	<h2>Conclusie</h2>
	<p>
		Het delen van kennis binnen de zorg zal de komende tijd belangrijker worden. Mede door de huidige COVID-19
		crisis is het directe contact tussen een zorgverlener en zorgontvanger niet aanwezig en gaat dit geheel
		digitaal. Deze trend van het digitaal gaan en het delen van kennis via andere wegen dan de traditionele kan op
		worden ingespeeld. Deze innovatiepotentie zal in het WijPIDZ component terugkomen om een aantrekkelijker product
		te maken voor de gebruiker.
	</p>
	<h2>Verantwoording</h2>
	<p>Volledige uitgevoerd door mijzelf. Inspiratie en informatie opgedaan uit vergelijkbare onderzoeken van Dylano Hartman of Mark Hendriks.</p>
	<h2>Bronnen</h2>
	<ul>
		<li>[1] Wortell. (2018 augustus). 7 trends in de zorg. Geraadpleegd op 19 mei 2020, van <a href="https://www.wortell.nl/assets/uploads/2018/08/Trendrapport-7-trends-in-de-zorg.pdf" target="_blank" rel="noopener">https://www.wortell.nl/assets/uploads/2018/08/Trendrapport-7-trends-in-de-zorg.pdf</a></li>
		<li>[2] van Zoest, F. (2017, 31 augustus). 9 trends in de ouderenzorg. Geraadpleegd op 19 mei 2020, van <a href="https://www.vilans.nl/artikelen/trends-ouderenzorg" target="_blank" rel="noopener">https://www.vilans.nl/artikelen/trends-ouderenzorg</a></li>
		<li>[3] CONSUMER TREND CANVAS. (2014 mei). Geraadpleegd op 19 mei 2020, van <a href="https://trendwatching.com/trends/consumertrendcanvas/" target="_blank" rel="noopener">https://trendwatching.com/trends/consumertrendcanvas/</a></li>
	</ul>
	<!-- Document: https://docs.google.com/document/d/1j2EkoYYUr2p0usXtJFqO7shb8kJnwyh7ifczReUiI-E/ -->
	<!-- Product: https://drive.google.com/file/d/1LnfU7WJUgo9D2dLPDV0niNqsZnG-_kIJ/ -->
{:else if product.link === 'concept-document'}
	<h2>Aanleiding</h2>
	<p>Dit document is gemaakt om het snel gemaakte proof of concept te verduidelijken voor de opdrachtgever.</p>
	<h2>Aanpak</h2>
	<p>
		Er wordt een proof of concept gemaakt om visueel weer te geven wat de ideeën zijn voor het concept. Hierbij worden de functionaliteiten van het platform uitgelicht.
	</p>
	<h2>Uitvoering</h2>
	<p>Het concept is een component om vragen te kunnen stellen, te beantwoorden, op te reageren en de mogelijkheid om met iemand 1-op-1 te chatten. Dit gaat het component inhouden. Deze functionaliteiten zijn uit onderzoek en inspiratie gekomen vanuit de onderzoeken die zijn gedaan, denk hierbij aan een concurrentie analyse en een trendanalyse.</p>
	<Image imgURL="https://i.gyazo.com/c69d7a07ef0f3605d9cbf969084689dc.jpg" imgALT="Concept document" linkURL="https://docs.google.com/document/d/1jMFDnrAp0jCWUPSIuvPXbX0W4njh-pzJl9Ctheyb3tw/" />
	<p>De resultaten van de gemaakte <a href="https://portfolio.maxaltena.com/S6/project2/concurrentie-analyse/">concurrentie analyse</a> en <a href="https://portfolio.maxaltena.com/S6/project2/trend-analyse/">trend analyse</a> zijn meegenomen in het proof of concept op de volgende punten:</p>
	<ul>
		<li><strong>1-op-1 chats</strong> - Uit onderzoek bleek dat mensen het fijn vinden om dingen 1-op-1 te delen in plaats van op het gehele internet.</li>
		<li><strong>Betrouwbaarheid</strong> - Stellen van vragen zijn bij indirecte concurrenten belangrijk er wordt niet gekeken naar betrouwbaarheid.</li>
		<li><strong>Vragen</strong> - Het delen van kennis is een trend, komend uit de trendanalyse, die op dit moment opkomend is bij de zorg. Als het stellen van vragen en beantwoorden gemakkelijk en betrouwbaar is speelt dit in op deze trend.</li>
	</ul>
	<h2>Conclusie</h2>
	<p>
		Door het concept te wireframen is er een basis van hoe het er uit moet komen te zien en welke functionaliteit er in zit. Doordat er een ontwerp is gemaakt kan er makkelijker feedback op worden gegeven door groepsgenoten en de opdrachtgever.
	</p>
	<h2>Verantwoording</h2>
	<p>Volledig uitgevoerd door mijzelf.</p>
	<!-- Document: https://docs.google.com/document/d/1jMFDnrAp0jCWUPSIuvPXbX0W4njh-pzJl9Ctheyb3tw/ -->
{:else if product.link === 'concept-analyse'}
	<h2>Aanleiding</h2>
	<p>
		Om het concept te versterken en beter te kunnen positioneren in de markt wordt er een concept analyse gedaan,
		bestaande uit een SWOT en USP analyse. Met deze informatie kan worden verantwoord welke functionaliteiten er in
		het concept moeten zitten en welke tot een USP kunnen leiden.
	</p>
	<h2>Aanpak</h2>
	<p>
		Er wordt eerst een SWOT analyse gedaan van het concept, wat zijn punten die sterk zijn van het concept en welke
		zijn de zwaktes? Met deze vragen beantwoord te hebben kan er nog gekeken worden naar de concurrentie om zo het
		concept in de markt te kunnen zetten met een Unique Selling Point.
	</p>
	<h2>Uitvoering</h2>
	<p>Om de sterke en zwakke punten en de mogelijkheden en bedreigingen van het concept beter in kaart te brengen is er een SWOT analyse gedaan van deze punten. Met deze informatie kan er ook gekeken worden naar hoe het concept het beste in de markt kan worden gezet.</p>
	<Image imgURL="https://i.gyazo.com/f99aec265b4b7deca44d5ef466165d99.png" imgALT="Concept analyse - SWOT analyse" linkURL="https://drive.google.com/file/d/1SCBEt05Va-CFqmPDSywv5G2Pwt2Zd5FM/" />
	<p>Om sterke punten en daarnaast ook unieke punten te vinden tegenover de concurrentie is er een Unique Selling Point analyse gedaan door middel van het format van mindtools [1]. Met deze informatie kan er ook gekeken worden naar hoe het concept het beste in de markt kan worden gezet.</p>
	<Image imgURL="https://i.gyazo.com/237cd60608bbd543521081c52072cf22.jpg" imgALT="Concept analyse - USP analyse" linkURL="https://drive.google.com/file/d/1JhdB5sASWLwuwQhFfZYWSzRg4SQOXCGx/" />
	<h2>Conclusie</h2>
	<p>
		Doordat het concept de problemen van de gebruiker oplost is dat sterke punt ook een van de unieke punten van het
		concept. Naast dat het concept een probleem van de gebruiker oplost is het ook voor de gebruiker ontworpen en
		gemaakt. Verder is het aanbieden van een platform zo groot als WijPIDZ met functionaliteiten die nuttig zijn
		voor de gebruiker een USP op zich. Het delen van kennis component in het WijPIDZ platform is op zichzelf een
		uniek concept om iedereen zijn/haar kennis te delen door vragen te beantwoorden of kennis op te doen door het
		vragen van vragen. Daarnaast is het verifiëren van antwoorden door de community een USP.
	</p>
	<h2>Verantwoording</h2>
	<p>Volledige uitgevoerd door mijzelf.</p>
	<h2>Bronnen</h2>
	<ul>
		<li>[1] Mindtools. (z.d.). USP Analysis: The Unique Selling Proposition: Finding Your Competitive Edge. Geraadpleegd op 1 juni 2020, van <a href="https://www.mindtools.com/pages/article/newTMC_11.htm" target="_blank" rel="noopener">https://www.mindtools.com/pages/article/newTMC_11.htm</a></li>
	</ul>
	<!-- Document: https://docs.google.com/document/d/1JyDQrD8sY6aFT1PBR2co3qC30n5tnWN3E0L2qCBFAhA/ -->
	<!-- SWOT analyse: https://drive.google.com/file/d/1SCBEt05Va-CFqmPDSywv5G2Pwt2Zd5FM/ -->
	<!-- USP analyse: https://drive.google.com/file/d/1JhdB5sASWLwuwQhFfZYWSzRg4SQOXCGx/ -->
{:else if product.link === 'business-model'}
	<h2>Aanleiding</h2>
	<p>
		Om de opdrachtgever en andere belanghebbende van het concept en het uiteindelijke product duidelijk te maken wat
		de business erachter is wordt er een Business Model Canvas gemaakt. Op deze manier kan gemakkelijk en in een
		oogopslag duidelijk zijn wat de waarde is.
	</p>
	<h2>Aanpak</h2>
	<p>
		Er zal worden gekeken naar de manieren waarop het product geld kan maken, op wat voor manieren er geld wordt
		uitgegeven, waardeproposities en klantgerichte punten. Mede door de workshop gegeven door Bob Nieme, de eigenaar
		van Data Streams, kan er goed aan de slag worden gegaan met het maken van een Business Model Canvas om al deze
		punten op een overzichtelijke manier weer te geven.
	</p>
	<h2>Uitvoering</h2>
	<p>Er is een Business Model Canvas, Value Proposition en Customer Profile gemaakt met Strategyzer [1].</p>
	<Image imgURL="https://i.gyazo.com/e7e895552c800e1a26e7765568f4d040.png" imgALT="Business model - Business Model Canvas" linkURL="https://drive.google.com/file/d/1TQi9XoJbz8Hee-rjAk1h6TVlnd1MMQlH/" />
	<strong>Value proposition ZZP'er</strong>
	<Image imgURL="https://i.gyazo.com/41b881534ad57fc7efaa104b0034cee6.png" imgALT="Business model - Value proposition" linkURL="https://drive.google.com/file/d/1s6-Ausgu2BgDcjC84cQp4xpAlL8Qi338/" />
	<strong>Customer profile ZZP'er</strong>
	<Image imgURL="https://i.gyazo.com/5de56098a5a3aba45fea60e708abb475.png" imgALT="Business model - Customer profile" linkURL="https://drive.google.com/file/d/1qUwEmXgXOGDj_qtHLtLJgEeoTOzf1gUj/" />
	<h2>Conclusie</h2>
	<p>
		Duidelijkheid van welke belanghebbende en kosten er zijn met dit product is er nu. Daarnaast was er nog niet
		over nagedacht hoe het product waarde creëert voor de verschillende klanten en belanghebbende. Zo is het voor
		PIDZ belangrijk dat het product er is om meer gebruikers aan te trekken voor het platform en deze te behouden.
		De ZZP'ers in de zorg hebben verschillende vragen en door het product wordt het gemakkelijker om deze vragen te
		stellen en te beantwoorden op een overzichtelijke manier.
	</p>
	<h2>Verantwoording</h2>
	<p>Volledige uitgevoerd door mijzelf.</p>
	<h2>Bronnen</h2>
	<ul>
		<li>[1] Strategyzer AG. (z.d.). Strategyzer | Corporate Innovation Strategy, Tools & Training. Geraadpleegd op 1 juni 2020, van <a href="https://www.strategyzer.com/" target="_blank" rel="noopener">https://www.strategyzer.com/</a></li>
	</ul>
	<!-- Document: https://docs.google.com/document/d/1Jsb8f93tNSEMV5fP18bTphtRvMsXrHlXMTrKnx2ZItA/ -->
	<!-- Business Model Canvas: https://drive.google.com/file/d/1TQi9XoJbz8Hee-rjAk1h6TVlnd1MMQlH/ -->
	<!-- Value proposition: https://drive.google.com/file/d/1s6-Ausgu2BgDcjC84cQp4xpAlL8Qi338/ -->
	<!-- Customer Profile: https://drive.google.com/file/d/1qUwEmXgXOGDj_qtHLtLJgEeoTOzf1gUj/ -->
{:else if product.link === 'ontwerpen'}
	<h2>Aanleiding</h2>
	<p>Er is ontworpen om een prototype te maken om mee diverse <a href="https://portfolio.maxaltena.com/S6/project2/usability-test/">usability tests</a> mee uit te voeren. Daarnaast is een prototype een deliverable die PIDZ graag zou willen hebben.</p>
	<h2>Aanpak</h2>
	<p>Er is een prototype gemaakt in Adobe XD [1]. Er is hiervoor gekozen doordat je gemakkelijk kunt ontwerpen en prototype in XD. Daarnaast kun je samen aan 1 gezamenlijk bestand werken.</p>
	<h2>Uitvoering</h2>
	<p>Het prototype is in te zien door middel van het <a href="https://drive.google.com/file/d/1r6U0sOjyvsJkA1u9KfiN9blHKgEUhkBo/" target="_blank" rel="noopener">Adobe XD bestand</a> en de <a href="https://xd.adobe.com/view/3ee51ae7-1310-4d76-8034-2d6f425f7ae3-6bb6/?fullscreen" target="_blank" rel="noopener">online klikbare versie</a></p>
	<p>Sommige styles, zoals het lettertype, de kleuren en de blokken, komen van het <a href="https://projects.invisionapp.com/dsm/smiling-gents/pidz-design-system/" target="_blank" rel="noopener">PIDZ design systeem</a> dat is aangeleverd en waar grotendeels aan gehouden moest worden.</p>
	<strong>Homepagina</strong>
	<p>Gebaseerd op van mijn <a href="https://portfolio.maxaltena.com/S6/project2/concept-document/">concept</a> en van de <a href="https://portfolio.maxaltena.com/S6/project2/concurrentie-analyse/">concurrentie analyse</a> waaruit bleek dat reddit een goede vorm heeft van het weergeven van vragen/posts.</p>
	<Image imgURL="https://i.gyazo.com/5567b2e5c2e3a88db9d16ca5805a8495.png" imgALT="Ontwerpen - Homepagina" linkURL="https://drive.google.com/file/d/1Whly9ADC6nx1RjH2np3NRNI6kv887AMV/" />
	<strong>Vraag details</strong>
	<p>Het gemakkelijk beantwoorden van vragen is een belangrijk aspect om zo min mogelijk frictie te hebben. Er komt veel overeen met stackexchange met de manier waarop er informatie weergegeven wordt.</p>
	<Image imgURL="https://i.gyazo.com/9c8fab87b3ff3fc94de45467dbdf3599.png" imgALT="Ontwerpen - Vraag details" linkURL="https://drive.google.com/file/d/1taN2qCWURJGx--fsJKJB4xWMOzrgZy5d/" />
	<p>Er zijn meerdere iteraties geweest op elementen die in het prototype zitten.</p>
	<strong>Zoekbalk</strong>
	<p>Doordat er meer content in op het platform delen van kennis kwam dan eerst gedacht, is de zoekbalk van rechts in de column naar boven verplaatst. Daarnaast is er door meer content ook vraag naar specifieker zoeken.</p>
	<Image imgURL="https://i.gyazo.com/710bfa2cf0828850f1e438ea6c3a304d.jpg" imgALT="Ontwerpen - Zoekbalk" linkURL="https://drive.google.com/file/d/14FXl29lsMpJS3jDYcH3QL2QxZiJDRooH/" />
	<strong>Antwoord op vraag</strong>
	<p>Om het duidelijker te maken hoe je een antwoord selecteert als het meest geholpen antwoord is er voor gekozen het duidelijker te maken hoe je deze kunt selecteren. Daarnaast is de titel weggehaalt omdat er geen behoefte aan was in een antwoord.</p>
	<Image imgURL="https://i.gyazo.com/f51bfa2b502626e161fdce6135cc1f05.jpg" imgALT="Ontwerpen - Antwoord op vraag" linkURL="https://drive.google.com/file/d/1A1DrlNOKvF8Gj0-UkvcnVNbW5Na65xuA/" />
	<h2>Conclusie</h2>
	<p>Het ontwerpen ging goed en voorspoedig doordat er met z'n drie aan werd gewerkt. Product is gemakkelijk gevisualseerd door middel van Adobe XD.</p>
	<h2>Verantwoording</h2>
	<p>Het uiteindelijke ontwerp is een fusie van alle 3 de concepten van Dylano Hartman, Mark Hendriks en mij. Ik heb bijvoorbeeld de hoofdpagina opnieuw ontworpen, een vraag stellen flow ontworpen en het inzien van vragen gemaakt.</p>
	<h2>Bronnen</h2>
	<ul>
		<li>[1] Adobe XD. (z.d.). UI/UX design and collaboration tool | Adobe XD. <a href="https://www.adobe.com/products/xd.html" target="_blank" rel="noopener">https://www.adobe.com/products/xd.html</a></li>
	</ul>
{:else if product.link === 'usability-test'}
	<h2>Aanleiding</h2>
	<p>Om het gemaakte product te testen zal er een usability test plaatsvinden met enkele ZZP'ers van PIDZ. Deze zullen worden online met Useberry [1] uitgevoerd worden door COVID-19. Deze testen worden gedaan om het eindproduct te verbeteren en inzichten te krijgen in het gebruik van het prototype. Na de eerste testronde is er niet meer getest met ZZP'ers van PIDZ maar met kennissen en ouders.</p>
	<h2>Aanpak</h2>
	<p>Door het maken van een Usability Test Plan Dashboard [2] kan er worden gekeken naar wat er getest gaat worden en hoe. Daarnaast zal er een tweede ronde worden gedaan waarbij andere personen worden getest als in de eerste ronde.</p>
	<p>De eerste ronde zal via PIDZ met ZZP'ers worden gedaan. Dit zal via Useberry gaan. De tweede ronde zal via Teams/Discord gedaan worden met andere personen om de resultaten van de eerste ronde te toetsen.</p>
	<h2>Uitvoering</h2>
	<strong>Usability Test Plan Dashboard</strong>
	<Image imgURL="https://i.gyazo.com/73a285903f444c7546e301b14450f96d.jpg" imgALT="Usability test - Usability Test Plan Dashboard" linkURL="https://drive.google.com/file/d/1fLzJmJm5sAg9apeZbwq0HeTC-NmcJ89r/" />
	<strong>ZZP'ers van PIDZ</strong>
	<p>De eerste ronde was succesvol met 5 verschillende personen die het prototype via Useberry hebben getest. Er waren 3 personen die niet het beste antwoord konden selecteren bij een vraag die zij stelde. 2 personen waren erg te spreken van het component en gaven feedback zoals: 'Het enige waar ik tegenaan liep dat het even zoeken was om een opmerking te liken en dat het niet echt een logische en duidelijke knop voor was.' Dit was ook terug te zien in de recordings van de personen. Om deze reden is het selecteren van het meest geholpen antwoord verbeterd.</p>
	<Image imgURL="https://i.gyazo.com/f51bfa2b502626e161fdce6135cc1f05.jpg" imgALT="Usability test - Antwoord op vraag" linkURL="https://drive.google.com/file/d/1A1DrlNOKvF8Gj0-UkvcnVNbW5Na65xuA/" />
	<Image imgURL="https://i.gyazo.com/85d8385b7719ec1dca022755e1d69878.jpg" imgALT="Usability test - Antwoord op vraag juist" linkURL="https://drive.google.com/file/d/1gyv98OeNigB7yd-ppyuORPE79CUUEH32/" />
	<strong>Diverse personen</strong>
	<p>De tweede ronde ging ongeveer hetzelfde als de eerste. Hierbij werden er wel enkele testen afgenomen op locatie (bv ouders) en hieruit kwam dat het platform werd gebruikt zoals gepland. Daarnaast waren de verbeteringen van de antwoorden goed te zien in het gemakkelijke gebruik.</p>
	<h2>Conclusie</h2>
	<p>Ten eerste was het lastig voor de ZZP'ers van PIDZ om Useberry te gebruiken. Ze lazen volgensmij niet de opdracht waardoor ze willekeurig een beetje gingen rondklikken. Het was dus een groot nadeel om Useberry te gebruiken in plaats van de reguliere on-site thinking aloud test. De resultaten van de test zijn wel meegenomen bij de tweede ronde waaruit kwam dat het platform goed te gebruiken was. Mede doordat dit deels on-site werd gedaan.</p>
	<Image imgURL="https://i.gyazo.com/152019f5c434e4efb9cc5e78456d58f4.png" imgALT="Usability test - Ronde 1 testresultaten" linkURL="https://gyazo.com/152019f5c434e4efb9cc5e78456d58f4" />
	<h2>Verantwoording</h2>
	<p>Het testplan is gemaakt door mijzelf. De testen zijn ook uitgevoerd door mijzelf. Het prototype is gemaakt met de groep bestaande uit Dylano Hartman, Mark Hendriks en mijzelf. De iteraties zijn ook door mijzelf gemaakt.</p>
	<h2>Bronnen</h2>
	<ul>
		<li>[1] Useberry. (z.d.). Useberry - Codeless prototype analytics. <a href="https://www.useberry.com/" target="_blank" rel="noopener">https://www.useberry.com/</a></li>
		<li>[2] Travis, D. (2013, 2 oktober). The 1-page usability test plan. <a href="https://www.userfocus.co.uk/articles/usability_test_plan_dashboard.html" target="_blank" rel="noopener">https://www.userfocus.co.uk/articles/usability_test_plan_dashboard.html</a></li>
	</ul>
{:else if product.link === 'svelte-workshop'}
	<h2>Aanleiding</h2>
	<p>Om mijn presentatie/workshop skills te verbeteren en om andere semester 6 studenten een nieuwe techniek te leren heb ik een Svelte workshop gegeven.</p>
	<h2>Presentatie</h2>
	<Image imgURL="https://i.gyazo.com/6436f51f2728404e87bde7c0578be685.jpg" imgALT="Svelte workshop - Presentatie" linkURL="https://docs.google.com/presentation/d/1C4_pAOsqH11qEbFMlQxtE9oFWn47OXSm8ObBTTyJks0/" />
	<h2>Uitvoering</h2>
	<Image imgURL="https://i.gyazo.com/d4a608365def738d06515003c2454c33.png" imgALT="Svelte workshop - Video" linkURL="https://web.microsoftstream.com/video/f5a514d9-5646-4b1d-9821-9ce1c8d36e93" />
	<h2>Verantwoording</h2>
	<p>Volledige uitgevoerd door mijzelf.</p>
	<!-- Presentatie: https://docs.google.com/presentation/d/1C4_pAOsqH11qEbFMlQxtE9oFWn47OXSm8ObBTTyJks0/ -->
	<!-- Video: https://web.microsoftstream.com/video/f5a514d9-5646-4b1d-9821-9ce1c8d36e93 -->
{:else if product.link === 'communicatiestrategie'}
	<h2>Aanleiding</h2>
	<p></p>
	<h2>Aanpak</h2>
	<p></p>
	<h2>Uitvoering</h2>
	<p></p>
	<h2>Conclusie</h2>
	<p></p>
	<h2>Verantwoording</h2>
	<p></p>
{:else if product.link === 'peer-feedback'}
	<h2>Aanleiding</h2>
	<p>Om mijzelf als student en 'young professional' te verbeteren en de leren waar mijn sterke en zwakke punten zitten en andere feedback te geven is er met een deel van de groep besloten om elkaar feedback te geven.</p>
	<h2>Aanpak</h2>
	<p>Er is peer feedback gegeven op basis van een template dat vorige semesters is uitgegeven door Fontys om studenten elkaar feedback te laten geven. Op deze manier kan er van elkaar geleerd worden en gereflecteerd worden op het project en semester.</p>
	<h2>Uitvoering</h2>
	<p>De volgende feedback is ontvangen:</p>
	<strong>Goede punten en verbeter punten</strong>
	<Image imgURL="https://i.gyazo.com/cc8df31be8fccbb07cb56a9db15fc4bb.png" imgALT="Peer feedback - Goede punten en verbeter punten" linkURL="https://docs.google.com/spreadsheets/d/17nIqFTNfJ9cjCEHuEAijHDlhc5ORw_TrrdCAHOkSuk8/" />
	<strong>Feedback Dylano Hartman</strong>
	<Image imgURL="https://i.gyazo.com/f99648fd2dd939b36f35836a0511bf57.png" imgALT="Peer feedback - Feedback Dylano Hartman" linkURL="https://docs.google.com/spreadsheets/d/17nIqFTNfJ9cjCEHuEAijHDlhc5ORw_TrrdCAHOkSuk8/edit#gid=710680365" />
	<strong>Feedback Mark Hendriks</strong>
	<Image imgURL="https://i.gyazo.com/ddf44545116bca280675bdf6d214e882.png" imgALT="Peer feedback - Feedback Mark Hendriks" linkURL="https://docs.google.com/spreadsheets/d/17nIqFTNfJ9cjCEHuEAijHDlhc5ORw_TrrdCAHOkSuk8/edit#gid=1728634695" />
	<strong>Feedback Mike Hendriks</strong>
	<Image imgURL="https://i.gyazo.com/98ec410484ac4f9ccc3308f3bbe4142f.png" imgALT="Peer feedback - Feedback Mike Hendriks" linkURL="https://docs.google.com/spreadsheets/d/17nIqFTNfJ9cjCEHuEAijHDlhc5ORw_TrrdCAHOkSuk8/edit#gid=1127562872" />
	<strong>Feedback Bart van de Klundert</strong>
	<Image imgURL="https://i.gyazo.com/4fbd7df51d197d2d9c87e628cd3aec36.png" imgALT="Peer feedback - Feedback Bart van de Klundert" linkURL="https://docs.google.com/spreadsheets/d/17nIqFTNfJ9cjCEHuEAijHDlhc5ORw_TrrdCAHOkSuk8/edit#gid=389252453" />
	<p>De volgende feedback is gegeven:</p>
	<Image imgURL="https://i.gyazo.com/f2a0a2ca48cc17705cdb25518fc2457a.png" imgALT="Peer feedback - Gegeven feedback" linkURL="https://docs.google.com/spreadsheets/d/17nIqFTNfJ9cjCEHuEAijHDlhc5ORw_TrrdCAHOkSuk8/" />
	<h2>Reflectie</h2>
	<p>De verkregen feedback van mijn peers was erg goed ontvangen doordat ik zelf mijn sterke en zwakkere punten van dit semester erin zag. Zo was mijn motivitie en daarbij ook mijn productiviteit wat minder wat de andere ook wel zagen. Het leiden van de groep en het initiatief nemen bij diverse dingen zie ik ook wel terug in mijzelf wat fijn is om te horen. Waar ik aan ga werken is het beter communiceren van mijn bedoelingen en mijn 'status' (m.b.t. het afwezig zijn).</p>
	<h2>Verantwoording</h2>
	<p>Er is feedback ontvangen en gegeven aan het grootste deel van de groep: Dylano Hartman, Mark Hendriks, Mike Hendriks en Bart van de Klundert. Noël Herwig en Timo van de Laar hebben geen feedback ontvangen of gegeven doordat ze het niet relevant vonden.</p>
	<!-- Spreadsheet: https://docs.google.com/spreadsheets/d/17nIqFTNfJ9cjCEHuEAijHDlhc5ORw_TrrdCAHOkSuk8/ -->
{:else if product.link === 'adviesrapport'}
	<h2>Aanleiding</h2>
	<p>Om de onderzoeken van alle drie de sub-groepen van De Sigaar samen te vatten en behapbaar te maken voor PIDZ is er een adviesrapport opgesteld met onze adviezen.</p>
	<h2>Aanpak</h2>
	<p>Mede doordat het de laatste week was van het project is er voor gekozen om mij het adviesrapport grotendeels te laten maken. De input van de sub-groepen was nodig om hun onderzoeksopzet, resultaten en conclusies te maken waarna ik het document 1 geheel kon maken.</p>
	<h2>Uitvoering</h2>
	<p>Ik ben begonnen met het kijken naar hoe ik een adviesrapport kan maken. Zo was er een 'perfect adviesrapport' van Scribbr [1] die ik als basis heb gebruikt om het adviesrapport te maken. Hierna ben ik begonnen met het opzetten van de globale dingen, zoals de inleiding van de opdrachtgever en de opdracht, waarna ik aan de sub-groepen heb gevraagd om hun stukjes te schrijven. Hierna heb ik hieroverheen gelezen waarbij ik feedback heb gegeven om de tekst en verbeteringen heb doorgevoerd. Als laatst heb ik het document van een simpelweg google <a href="https://docs.google.com/document/d/18CDEe6Pf5EhB5r3azcfRIpL8-jm6IzIlSznYHjGsFjc/" target="_blank" rel="noopener">document</a> een mooie presentable document gemaakt.</p>
	<Image imgURL="https://i.gyazo.com/2dcafedcdd12dc7934baf9e0ea760606.jpg" imgALT="Adviesrapport - Product" linkURL="https://drive.google.com/file/d/1uuAZwHHKi-mwhcmtaccib7ImcWya28s9/" />
	<h2>Conclusie</h2>
	<p>Om de adviezen te realiseren moeten de diverse onderdelen gezamenlijk onder het WijPIDZ platform worden gerealiseerd van concept naar product. Daarnaast zal er via diverse media duidelijk moeten worden gemaakt dat het delen van kennis onderdeel in WijPIDZ zit en welk probleem dit oplost om gebruikers gebruik te laten maken van het onderdeel.</p>
	<p>Er moet onderzoek gedaan worden naar affiliate marketing voor het onderdeel inkopen van goederen en diensten om zo connecties te maken met leveranciers. Als laatste is het belangrijk om de social media kanalen van PIDZ in te zetten om bekendheid voor het WijPIDZ platform te creëren. Het aanbod voor verschillende opleidingen en cursussen zal moeten worden verkregen door affiliate marketing. De niet-PIDZ leden, die gebruik maken van het opleidingen en cursussen onderdeel, moeten door middel van call-to-actions de voordelen voor PIDZ-leden gaan inzien en lid worden.</p>
	<p>Het WijPIDZ platform met de onderdelen, die diverse problemen van zelfstandige zorgprofessionals oplost, is het makkelijkst te realiseren door de adviezen na te leven om zo een waardevol WijPIDZ platform te creëren voor zowel de gebruiker als PIDZ.</p>
	<h2>Verantwoording</h2>
	<p>Grotendeels uitgevoerd door mijzelf. Stukjes tekst van andere sub-groepen overgeleven en aangepast waar nodig om verhaal lopend te houden.</p>
	<h2>Bronnen</h2>
	<ul>
		<li>[1] Benders, L. (2020, 21 april). Schrijf een perfect adviesrapport. Scribbr. <a href="https://www.scribbr.nl/stage/schrijf-een-perfect-adviesrapport/" target="_blank" rel="noopener">https://www.scribbr.nl/stage/schrijf-een-perfect-adviesrapport/</a></li>
	</ul>
	<!-- Document: https://docs.google.com/document/d/18CDEe6Pf5EhB5r3azcfRIpL8-jm6IzIlSznYHjGsFjc/ -->
	<!-- Product: https://drive.google.com/file/d/1uuAZwHHKi-mwhcmtaccib7ImcWya28s9/ -->
{:else}
	<p>Huh, product niet gevonden? Probeer het later nog eens of check of dit wel de goede link is!</p>
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
		color: var(--on-accent);
	}
	ul {
		margin-left: 1em;
		margin-bottom: 2em;
	}
	 li {
		margin: 0.25em 0.5em;
		word-spacing: 1px;
		line-height: 1.85;
	}
</style>
