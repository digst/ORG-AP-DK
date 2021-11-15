<style>
@media print {
  html { margin: 0cm 2cm 2cm 0cm; font-size: 80%; }
  /* DIGST fonts */
  body { font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;}
  h2,h3,h4, h4 dfn { font-family: "Garamond", serif; color: black; margin-bottom: 0; font-style: normal; font-weight: normal;}
  h2:not(#subtitle) { page-break-before: always; font-size: 250%; border-bottom: solid 0.5px black; padding-top: 20px; margin-bottom: 6px;}
  h3 { font-size: 145%;}
  h4 { font-size: 125%;}
  #toc {page-break-before: always;}
  /* DIGST-like frontpage */
  .head { width: 50%; margin-left: 24px; padding: 0px; background-color: #031D5C;}
  .head div { background-color: white; padding: 24px; }
  .head hr { display: none;}
  .head h1 { background-color: #031D5C; color: white; margin: 0px; padding: 50px 0px 50px 24px; font-weight: normal; }
  #subtitle { padding-left: 24px; background-color: #031D5C; color: #031D5C; }
  .head time { display: block; font-family: "Helvetica Neue", Helvetica, Arial; margin: 0px; background-color: #031D5C; font-size: 80%; color: white;}
  .toc li { line-height: 70%; font-family: "Helvetica Neue", Helvetica, Arial;
    font-weight: 600; font-size: 90%; }
  h2.heading.settled > a.self-link, h3.heading.settled > a.self-link, h4.heading.settled > a.self-link, h4.heading.settled > a.self-link, h5.heading.settled > a.self-link, h6.heading.settled > a.self-link { display: none; }
  blockquote { font-size: 80%; font-style: italic; margin-left: 5%; width: 70%; border-left-width: 2px;}
	h2#abstract {display: none;}
	.p-summary {width: 50%; margin-left: 24px; padding: 0px;}
}
.new {
    border: solid 3px green;
    padding: 6px;
    margin: 18px 0px 18px 0px;
}

h2.heading.settled > a.self-link, h3.heading.settled > a.self-link, h4.heading.settled > a.self-link, h4.heading.settled > a.self-link, h5.heading.settled > a.self-link, h6.heading.settled > a.self-link { display: none; }

.term-table{
  font-size: 80%;
}

.term-table tr td:nth-of-type(3), .term-table tr td:nth-of-type(4), .term-table tr td:nth-of-type(5){
  word-wrap: anywhere;
  overflow-wrap: anywhere;
  hyphens: auto;
  word-break: break-all;
}

.term-table td{
  border-bottom: 1px solid #ccc;
  padding: 4px 8px;
}

.term-table tr td:first-child{
  font-weight: 600;
  word-wrap: break-word;
}

.term-table tr th:first-child{
  width: 10%;
}

.term-table tr th:nth-of-type(2){
  width: 45%;
}

.term-table tr th:nth-of-type(3){
  width: 45%;
}



.term-table tr td:nth-of-type(2){
  font-style: italic;
}

.term-table th{
  color: #000;
  border: none;
  background-color: #C8C8C8;
  text-transform: capitalize;
  font-weight: 600;
  padding: 6px 8px;
}

.body{
  max-width: 100% !important;
}

.body.h-entry{
  max-width: 100%;
}

	@media screen and (min-width: 78em) {

		body.h-entry:not(.toc-inline) {
			padding-left: 25em;
		}
}


dl.def dt,dl.def dd {
    box-sizing: border-box;
}
dl.def dt {
    float: left;
    width: 25%;
    padding-bottom: 0;
}
dl.def dd {
    margin-left: 25%!important;
}
dl.def dd:after {
    content: "";
    display: block;
    clear: both;
} 

img{max-width:100%!important}
p.center{text-align:center!important}
p.left{text-align:left!important}
p.right{text-align:right!important}
p.italic{font-style: italic!important;}
#toc h2{color:#000!important}
#toc ol, #toc li, #toc a {
    display: block;
}
.toc .secno {
    margin-right: 1rem!important;
}
:not(li) > .toc {
    margin-left: 0rem!important;
}
	#toc > .toc > li > a > span {
    margin-top: 0rem;
}
	
/* style til egne og andres definitioner rød/blå*/
</style>


<pre class="metadata">
Title: ORG-AP-DK 1.0.0-beta
Status: LD
URL: https://data.gov.dk/model/profile/ORG-AP-DK/
Editor Term: Udgiver, Udgivere 
Editor: Digitaliseringsstyrelsen,, arkitektur@digst.dk
Abstract: 'ORG-AP-DK 1.0.0-beta' .
Boilerplate: copyright no, conformance no, abstract no
Shortname: ORG-AP-DK
Revision: 1.0.0-beta 
Date: 2021-11-15
Max ToC Depth: 3
Markup Shorthands: markdown yes
Repository: digst/ORG-AP-DK
Translation: en https://digst.github.io/ORG-AP-DK/docs/index-en.html
Inline Github Issues: full
Logo: digst...
</pre>


<h1>UDKAST TIL ORG-AP-DK 1.0.0-beta: Anvendelseprofil for organisation </h1>

#  Introduktion
Dette dokument introducerer modellering af organisationer og definerer en anvendelsesprofil baseret på internationale standarder. Anvendelsesprofilen udgør en fælles model for offentlige såvel som ikke-offentlige organisationer i en dansk administrativ og fællesoffentlig kontekst.

## Formål
Data om organisationer, private eller offentlige, er de helt grundlæggende oplysninger om organisationers navn, struktur, placering, opgaver, mv. Disse data indgår i mange forskellige sammenhænge i offentlige løsninger. Ved at etablere en fælles standard for opbygning og udstilling af data om både private og offentlige organisationer opnås ikke blot et fælles sprog og en fælles struktur, men grundstenene sættes også for større deling og genbrug af data om organisationer.

## Baggrund
Anvendelsesprofilen ORG-AP-DK udarbejdes i tæt koordiering og samarbejde med KL og en referencegruppe bestående af deltagere fra kommuner, regioner og statslige myndigheder som udarbejder en beskrivelse af de forretningsmæssige behov samt bagvedliggende informationsmodel.

Anvendelsesprofilen baseres på internationale standarder. Særligt bidrager de internationale vokabularer [The Organization Ontology (ORG)](https://www.w3.org/TR/vocab-org/) og [Core Public Organisation Vocabulary (CPOV)](https://joinup.ec.europa.eu/release/core-public-organisation-vocabulary-v100) med centrale klasser og egenskaber. ORG-AP-DK er en nærmere specifikation af, hvordan de internationale modeller skal forstås og anvendes – i denne sammenhæng til modellering af data vedrørende organisationer og myndigheder i dansk fællesoffentlig kontekst. 


## Metode
Anvendelsesprofilen er oprettet i henhold de [Fællesoffentlige regler for begrebs- og datamodellering](https://arkitektur.digst.dk/metoder/regler-begrebs-og-datamodellering), og sammensætter således eksisterende vokabularer til en bestemt anvendelse. Teknologisk udspringer de anvendte og foreslåede modeller af Semantic Web/Linked Dataverdenens modelleringsgrundlag, Resource Description Framework (RDF). En basal forståelse af RDF samt kendskab til de her profilerede vokabularer er et godt udgangspunkt for arbejdet med anvendelsesprofilen. ORG og CPOV foreligger i danske oversættelser. Disse oversatte dokumenter udgør normative referencer for den i efterfølgende opstillede anvendelsesprofil.

## Profilens anvendelse

<div class='issue'>
Indsæt reference til KLs brugsscenarier.
Brugsscenarierne er inddelt i en række perspektiver som beskrives nærmere i næste afsnit.
</div>	

# Grundlæggende perspektiver

<img src="img/illustration-til-ORG-AP-DK-core.svg" alt="grundlæggende perspektiver">

<div class='issue'>
Det aktuelle udkast omfatter ikke alle ovenstående perspektiver endnu, men vi arbejder løbende på at opdatere modellen.
</div>

## Organisation
- Det grundlæggende vokabular, ORG, definerer bredt **organisation** som *”[…] en samling mennesker, der er organiseret i et fællesskab eller anden social, kommerciel eller politisk struktur. Gruppen har et vist fælles formål eller eksistensberettigelse, der rækker ud over det sæt af personer, der tilhører den. En organisation kan i sig selv fungere som aktør.”*
- En **formel organisation** beskrives af ORG som *”en organisation, der – især i juridisk forstand – er bredt anerkendt og har tilhørende rettigheder og ansvar. Eksempler kan være et aktieselskab eller en velgørende, statslig eller kirkelig forening”.*
- En **offentlig organisation** beskrives af CPOV som *”enhver organisation, der er defineret som værende en del af den offentlige sektor under en juridisk ramme på ethvert niveau”.*


## Basisinformation
- En organisation tilføjes en eller flere navne. En af navnene på et givet sprog vil være organisationens **primære, juridiske navn**, men andres kan angives som **alternative eller skjulte navne**.
- En organisation kan forsynes med en **tekstbaseret beskrivelse** af organisationen 
- En organisation kan have en billedlig repræsentation i form at et **logo og en miniature**.
- En organisation kan kædes sammen med dens **hjemmeside** på internettet.
- En organisation kan forsynes med en **identifikator** - Til identifikation af en dansk offentlig organisation kan en myndighedskode anvendes. Kommunekoder og regionskoder udgør begge delmængder af myndighedskoder. Juridiske enheder kan identificeres med brug af et CVR-nummer. 
- En offentlig organisation kan tilknyttes de **forvaltningsopgaver** der varetages af myndigheden opmærkning med fx KLE eller FORM.

Svarer på følgende brugsscenarier beskrevet af KL: *"3.5 Basisinformation om organisationen"* 

[Se eksempel her](https://digst.github.io/ORG-AP-DK/releases/v.1.0/docs/#eksempel-p-basisinformation)

	
## Organisatorisk struktur
- En organisation kan bestå af flere **underorganisationer** der hver for sig har en specifik identitet, fx kan et ministerium bestå af flere underordnede styrelser.
- En organisation kan være inddelt i mindre **organisationsenheder** hvis eksistens er afhængig af organisationen, fx en afdeling i en større organisation. Organisationer består typisk af mange afdelinger, kontorer, enheder, teams, grupper osv.
- Organisationer kan indbyrdes have **andre former for relationer** end de der udtrykkes i form af under- og overorganisatoriske forhold, fx finansiering eller kæderelationer.
- En organisation kan klassificeres som værende af en bestemt **organisationstype**. I forhold til offentlige organisationer kunne det fx være kommune, region, ministerier, styrelser og mange af de andre former for offentlige organisationer, der er en væsentlig del af hverdagen i det offentlige organisationslandskab. 

Svarer på følgende brugsscenarier beskrevet af KL: *"3.1 Hvordan er organisationen bygget op?"* 

<img src="img/OrganisationalStructure.png" alt="organisatorisk struktur">

[Se eksempel her](https://digst.github.io/ORG-AP-DK/releases/v.1.0/docs/#eksempel-p-organisatoriske-strukturer)


## Kontaktoplysninger
- En organisation eller en organisationsenhed kan give information om hvordan man kommer i kontakt med organisationen
- Et kontaktoplysning kan fx være et **telefonnummer**, en **e-mailadresse**, en **url**, herunder Digital Post, gennem hvilken man kan kontakte organisationen eller en repræsentant for organisationen. 
- Et kontaktoplysningen kan også indholde information om **åbningstider** - enten på simpel vis eller i en mere komplekks struktur med yderligere begrænsninger. 

Svarer på følgende brugsscenarier beskrevet af KL: *"3.4 Hvordan kontaktes organisationen?"* 

<img src="img/View-ContactPoint.png" alt="kontaktoplysning">

[Se eksempel her](https://digst.github.io/ORG-AP-DK/releases/v.1.0/docs//#eksempel-p-kontaktinformation)



## Sted
- En organisations **fysiske placering** kan angives. Placeringen kan fx angives med en **adresse**.
- Det kan angives hvilket **administrativt geografisk område** en offentlig organisation dækker forvaltningsmæssigt.

<div class='issue'>
En organisation kan også have en virtuel lokation.
</div>

	
## Medlemsskab og aktører
- En persons relation til en organisation kan beskrives som en direkte **medlemskabsrelation**. En organisations relation til en anden organisation kan også have karakter af et **medlemskab**. En person ansat i en organisation kan betragtes som **medlem** af organisationen. I forhold til et givet medlemskab spiller aktøren i forhold til organisationen en **rolle**, som kan specificeres i en klassifikation over rolletyper.
- En organisations relationer til personer i form af **ansatte** og **ledere** kan også angives direkte.
- En **softwareaktør**, såsom en softwarerobot (RPA), kan også fungere som en medlem af en organisation og varetage en bestemt rolle i den forbindelse

Svarer på følgende brugsscenarier beskrevet af KL: *"3.3 Hvem er medlemmer af organisationen?"* 


<div class='issue'>
Det aktuelle udkast omfatter endnu ikke beskrivelser af jobfunktioner i organisationen. (Jf. brugsscenariet beskrevet af KL: *"3.2 Hvad arbejder organisationen med?"* )
</div>
	
## Hændelser og opgaver
- En organisation oprettes og ændres som svar på begivenheder eller **hændelser**. Dette kan være resultatet af ny lovgivning, ny politik eller at den påtager sig nye forpligtelser mv. En given ændring eller oprettelse kan således kædes sammen med den **lovgivning, den politik eller anden retskilde**, der udløste eller ligger til grund for hændelsen.
- En organisations **oprettelse** eller **nedlæggelse** kan beskrives og denne kan ske på et specifikt tidspunkt eller over en periode. Både overordnede organisatoriske ændringer og interne omstruktureringer kan rummes af modellen.
- En offentlig organisation beskrives med et organisatorisk formål, der antages altid at være en **forvaltningsopgave**. Til dette formål anvendes en klassifikation over forvaltningsopgaver.

Svarer på følgende brugsscenarier beskrevet af KL: *"3.6.4 Forretningshændelser?"* 

# UML-diagrammer


## Diagram med alle elementer
Den fulde anvendelsesprofil ORG-AP-DK v.1.0.0-beta visualiseret med UML-diagram.

<p class="center"><a href="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML.png"><img src="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML.png" alt="Illustration af ORG-AP-DK v1.0.0-beta som UML-klassediagram.png"/></a></p>

<p class="center"><a href="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML-simple.png"><img src="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML-simple.png" alt="Illustration af ORG-AP-DK v1.0.0-beta som UML-klassediagram (kun på dansk og uden datatyper og stereotyper).png"/></a></p>


# Navneområder
<table class="term-table">
<thead><tr><th>præfiks</th><th>navneområde</th><th>titel</th></tr></thead><tbody>
 <tr><td>org-ap-dk </td><td>https://data.gov.dk/model/profile/organisation/</td><td>Anvendelsesprofil for organisation</td></tr>	
 <tr><td>org </td><td>http://www.w3.org/ns/org# </td><td>Organization Ontology </td></tr>
 <tr><td>cpov </td><td>http://data.europa.eu/m8g/ </td><td>Core Public Organization Vocabulary </td></tr>
 <tr><td>foaf </td><td>http://xmlns.com/foaf/0.1/ </td><td>Friend of a Friend </td></tr>
 <tr><td>skos </td><td>http://www.w3.org/2004/02/skos/core# </td><td>Simple Knowledge Organization System </td></tr>
 <tr><td>dct </td><td>http://purl.org/dc/terms/ </td><td>Dublin Core Metadata Terms </td></tr>
 <tr><td>prov </td><td>http://www.w3.org/ns/prov# </td><td>The PROV Ontology </td></tr>
 <tr><td>locn </td><td>http://www.w3.org/ns/locn#   </td><td>Location Core Vocabulary </td></tr>
 <tr><td>cpsv </td><td>http://data.europa.eu/cv/ </td><td>Core Public Service Vocabulary </td></tr>
 <tr><td>eli </td><td>http://data.europa.eu/eli/ontology# </td><td>European Legislation Identifier </td></tr>
 <tr><td>schema </td><td>http://schema.org/ </td><td>Schema.org </td></tr>
 <tr><td>rdf </td><td>http://www.w3.org/1999/02/22-rdf-syntax-ns# </td><td>Resource Description Framework </td></tr>
 <tr><td>rdfs </td><td>http://www.w3.org/2000/01/rdf-schema# </td><td>RDF Schema </td></tr>
 <tr><td>owl </td><td>http://www.w3.org/2002/07/owl# </td><td>Web Ontology Language </td></tr>
 <tr><td>xsd </td><td>http://www.w3.org/2001/XMLSchema#  </td><td>XML Schema </td></tr>
 <tr><td>dagi </td><td>https://data.gov.dk/model/profile/cvr# </td><td>Grunddatamodel for Det Centrale Virksomhedsregister </td></tr>
 <tr><td>dar </td><td>https://data.gov.dk/model/profile/dar# </td><td>Grunddatamodel for Danmarks Adresser  </td></tr>
 <tr><td>cvr </td><td>https://data.gov.dk/model/profile/dagi# </td><td>Grunddatamodel for Danmarks Administrative Geografiske Inddeling</td></tr>
 <tr><td>ovx </td><td>https://data.gov.dk/model/organization/extension# </td><td>Organization Vocabulary Extension </td></tr>
</tbody></table>

</table>

# Globalt unikke og stabile identifikatorer	    
Formelle organisationer og organisationsenheder skal identificeres med en unik, stabil og tværgående identifikator der er uafhængig af det system den er skabt i. Derved kan organisationsdata opmærket med organisationsstandarden identificeres unikt på tværs af it-løsninger og organisatoriske skel. 
	    
Der er et generelt behov for at kunne sammenstille organisationsdata fra forskellige kilder og forretningsdata opmærket med organisationsdata på en sikker og nem måde. Det betyder, at der er behov for at de relevante organisationer og enheder er opmærket med en unik, tværgående identifikator. 
	    
Den tværgående identifikator ændres ikke i hele entitetens livstid. Oprettes en f.eks en ny organisationsenhed som erstatning for en tidligere enhed med samme navn, gives den nye en ny unik identifikator. Identifikatoren kan altid efter tildeling anvendes til at finde entiteten. 

Til dette anvendes en eksisterende global og bredt anvendt syntaks - URIer (Uniform Resource Identifiers). URI-specifikationen definerer en fælles syntaks for identificering og adressering af ressourcer som på internettet. Læs mere om unikke og stabile identifikatorer i [RFC 4646](https://www.ietf.org/rfc/rfc3986.txt) [FAIR-principperne](https://www.go-fair.org/fair-principles/), [EU 10 Rules for Persistent URIs](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/document/10-rules-persistent-uris) samt [Retningslinjer for stabile http-urier](https://arkitektur.digst.dk/node/588).

Udover den globalt unikke URI, forsynes organisationer også ofte med andre identifikatorer som udstedes til forskellige formål af specifikke myndigheder, fx. myndighedskoder og CVR-nummer som denne specifikation også kan rumme. 


#  Elementer i ORG-AP-DK
I det følgende præsenteres alle egenskaberne i ORG-AP-DK per klasse.

## Formel organisation

<img src="img/FormalOrganization.png" alt="formel organisation">
<dl class="def">
<dt>URI</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization " title="URI til FormalOrganization ">http://www.w3.org/ns/org#FormalOrganization </a></dd>
<dt>Foretrukken term (da)</dt>
<dd>formel organisation</dd>	
<dt>Alternativ term (da)</dt>
<dd>organisation</dd>		
<dt>Anvendelsesnote </dt>
<dd>Bruges til at beskrive organisationer der er formelt anerkendt i samfundet med tilhørende rettigheder og ansvar </dd>
<!-- <dt>Anvendelsesnote (en) </dt> <dd>Used to describe organizations which are recognized in the world at large with associated rights and responsibilities</dd> -->
<dt>Definition (da) </dt>
<dd>En organisation der er bredt anerkendt – især i juridisk forstand – og har tilhørende rettigheder og ansvar. </dt>
<!-- <dt>Definition (en) </dt> <dd>An Organization which is recognized in the world at large, in particular in legal jurisdictions, with associated rights and responsibilities. Examples include a corporation, charity, government or church.</dd> -->
<dt>Eksempel</dt>
<dd>Eksempler kan være et aktieselskab, en velgørende forening, en statslig administrativ enhed og en kirkelig organisation</dd>
<dt>Specialisering af</dt>
<dd><a href="http://www.w3.org/ns/org#Organization" title="URI for org:Organization">http://www.w3.org/ns/org#Organization</a></dd>
</dl>	 

Klassens egenskaber:	

### navn

<dl class="def">
<dt>URI</dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#prefLabel" title="URI til prefLabel">http://www.w3.org/2004/02/skos/core#prefLabel</a></dd>
<dt>Foretrukken term (da)</dt>
<dd>navn</dd>	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive organisationens primære - ofte juridisk anerkendte - navn. Det antages at organisationer kun har et sådant navn på hvert sprog. Primære navne kan angives på flere sprog med flere forekomster af egenskaben skos:prefLabel. </dd>
<!--<dt>Anvendelsesnote (en) </dt> <dd>Used to provide the primary - often legally recognised - name of the organization. An organization may only have one such name in any given language. Primary names may be provided in multiple languages with multiple instances of the preferred label property.</dd>	 --> 
<dt>Definition (da) </dt>
<dd>Den foretrukne leksikalske betegnelse for en ressource på et givet sprog. </dt>
<!-- <dt>Definition (en) </dt> <dd>The preferred lexical label for a resource, in a given language. </dd> -->
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral" title="URI til PlainLiteral">http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral</a></dd>
<dt>Underegenskab af</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#label" title="URI til label">http://www.w3.org/2000/01/rdf-schema#label</a></dd>


</dl>

### alternativt navn

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#altLabel" title="URI til altLabel">http://www.w3.org/2004/02/skos/core#altLabel</a></dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>alternativt navn</dd>  
<dt>Alternativ term på dansk</dt>  
<dd>alternativ betegnelse</dd>  	
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>alternative label</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive et accepteret - men ikke foretrukkent - navn for organisationen</dd>	
<!-- 
<dt>Anvendelsesnote (en) </dt>
<dd>Used to provide an accepted - not not preferred - name for the organisation</dd>	
-->
<dt>Definition på dansk</dt>  
<dd>en alternativ leksikalsk betegnelse for en ressource</dd>  
<!--<dt>Definition på engelsk</dt>  
<dd>An alternative lexical label for a resource.</dd>  
-->
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til ">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### beskrivelse 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/description" title="URI til description">http://purl.org/dc/elements/1.1/description</a></dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>beskrivelse</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>description</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en tekstbaseret beskrivelse af organisationens formål og arbejde</dd>	
<!-- <dt>Anvendelsesnote (en) </dt> <dd>Used to provide a textual description of the purpose and avtivity of the organisation</dd>	--> 
<dt>Definition på dansk</dt>  
<dd>en forklaring af en ressource</dd>  
<!--  <dt>Definition på engelsk</dt>  <dd>An account of the resource. </dd> -->
<dt>Defineret af</dt>  
<dd>http://purl.org/dc/elements/1.1/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### oprettelsesdato
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/foundingDate" title="URI til foundingDate">http://schema.org/foundingDate</a></dd>  
<dt>Foretrukken term</dt>  
<dd>oprettelsesdato</dd>  
<dt>Alternativ betegnelse (da)</dt>
<dd>grundlæggelsesdato</dd>		
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>founding date</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den dato hvorpå organisationen blev oprettet</dd>	
<!-- 
<dt>Anvendelsesnote (en) </dt> <dd>Used to specifying the date on which the organisation was created</dd> -->
<dt>Definition</dt>  
<dd>den dato organisationen blev oprettet</dd>  
<!-- <dt>Definition på engelsk</dt>  
<dd>The date that this organization was founded.</dd>  -->
<dt>Defineret af</dt>  
<dd>http://schema.org/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#date" title="URI til xsd:date">http://www.w3.org/2001/XMLSchema#date</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>



### nedlæggelsesdato
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/dissolutionDate" title="URI til dissolutionDate">http://schema.org/dissolutionDate</a> </dd>  
<dt>Foretrukken term</dt>  
<dd>nedlæggelsesdato</dd>	
<dt>Alternativ betegnelse)</dt>	
<dd>opløsningsdato</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>dissolution date</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den dato hvorpå organisationen blev nedlagt</dd>	
<!-- <dt>Anvendelsesnote (en) </dt> <dd>Used to specifying the date on which the organisation was dissolved</dd>	 -->
<dt>Definition</dt>  
<dd>den dato organisationen blev nedlagt</dd>  
<!--<dt>Definition på engelsk</dt>  <dd>The date that this organization was dissolved. </dd>  -->
<dt>Defineret af</dt>  
<dd>http://schema.org/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#date" title="URI til xsd:date">http://www.w3.org/2001/XMLSchema#date</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>


### identifikator

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/adms#identifier" title="URI til identifier">http://www.w3.org/ns/adms#identifier</dd>  
<dt>Foretrukken term</dt>  
<dd>identifikator</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>identifier</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at knytte en organisation til en identifikator. Bemærk at en organisation kan have flere identifikatorer tildelt organisationen af forskellige udstedende myndigheder til forskellige formål.</dd>
<!-- <dt>Anvendelsesnote (en) </dt> <dd></dd>	-->
<dt>Definition</dt>  
<dd>Knytter en ressource til en ADMS identifikator</dt>
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/adms#" title="URI til ">http://www.w3.org/ns/adms#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/adms#Identifier" title="URI til Identifier">http://www.w3.org/ns/adms#Identifier</a></dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
</dl> 

Læs også afsnittet <a href="https://digst.github.io/ORG-AP-DK/releases/v.1.0/docs/#globalt-unikke-og-stabile-identifikatorer" title="Globalt Unikke og stabile Identifikatorer">Globalt Unikke og stabile Identifikatorer</a>



### er underorganisation af 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#subOrganizationOf" title="URI til subOrganizationOf">http://www.w3.org/ns/org#subOrganizationOf</a></dd>  
<dt>Foretrukken term</dt>  
<dd>er underorganisation af</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>sub-organization of</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en hierarkisk overdordnet organisation. </dt>	
<!--
<dt>Anvendelsesnote (en) </dt>
<dd>Used to specify a hierarchically superordinate organisation.</dd>	-->

<dt>Definition</dt>  
<dd>Repræsenterer hierarkisk indhold af organisationer eller organisatoriske enheder. Den angiver en organisation, som omfatter denne organisation. </dd>  
<!--	
<dt>Definition på engelsk</dt>  
<dd>Represents hierarchical containment of Organizations or OrganizationalUnits; indicates an Organization which contains this Organization. Inverse of `org:hasSubOrganization`. </dd>  
-->
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til ">http://www.w3.org/ns/org#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
</dl>  


### har underorganisation 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasSubOrganization " title="URI til hasSubOrganization ">http://www.w3.org/ns/org#hasSubOrganization </a></dd>  
<dt>Foretrukken term</dt>  
<dd>har underorganisation</dd>  
<!--
<dt>Foretrukken term på engelsk</dt>  
<dd>has sub-organization</dd> -->
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en hierarkisk underordnet organisation.</dd>	
<!--<dt>Anvendelsesnote (en) </dt> <dd>Used to specify an organisation which this organisation contains</dt>	-->	
<dt>Definition</dt>  
<dd>Repræsenterer hierarkisk indhold af organisationer eller organisatoriske enheder. Egenskaben angiver en organisation, som er en del af denne organisation. </dd>  
<!-- <dt>Definition på engelsk</dt>  
<dd>Represents hierarchical containment of Organizations or Organizational Units; indicates an organization which is a sub-part or child of this organization. Inverse of `org:subOrganizationOf`. </dd>   -->
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til ">http://www.w3.org/ns/org#</a></dd>
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a></dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
</dl>  


### har enhed 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasUnit " title="URI til hasUnit ">http://www.w3.org/ns/org#hasUnit </a></dd>  
<dt>Foretrukken term</dt>  
<dd>har enhed</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 

<dt>Definition</dt>  
<dd>Angiver en enhed, som er del af denne organisation, f.eks. en afdeling i en større organisation </dd>  
<!--<dt>Definition på engelsk</dt> <dd>Indicates a unit which is part of this Organization, e.g. a Department within a larger FormalOrganization. Inverse of `org:unitOf` </dd>  -->
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en enhed som er en organisatorisk del af en større organisation. Bemærk at denne organisationsenhed eksistens er afhængig af den organisation den er en del af.</dd>	
<dt>Eksempel</dt>  
<dd>Eksempler kan være afdelinger, kontorer, sektioner, centre og lignende.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til org">http://www.w3.org/ns/org#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/org#OrganizationalUnit" title="URI til OrganizationalUnit">http://www.w3.org/ns/org#OrganizationalUnit</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>  
</dl>  

### relateret til  
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#linkedTo" title="URI til linkedTo">http://www.w3.org/ns/org#linkedTo</a></dd>  
<dt>Foretrukken term</dt>  
<dd>relateret til</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>Angiver en arbitrær relation mellem to organisationer. Specialiseringer af denne kan f.eks. bruges til at angive finansiering eller kæderelationer.</dd>  
<!--
<dt>Definition på engelsk</dt>  
<dd>Indicates an arbitrary relationship between two organizations. Specializations of this can be used to, for example, denote funding or supply chain relationships.  </dd>  
--> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en organisation som denne organisation har en eller anden relation til. Det kan eksempelvis være en finanseringsrelation eller en forsyningskæderelation. </dd>	
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til ">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a></dd></dl>  


### hjemmeside  
<dl class="def"><dt>URI</dt>  
<dd>http://xmlns.com/foaf/0.1/homepage</dd>  
<dt>Foretrukken term</dt>  
<dd>hjemmeside</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>en hjemmeside for noget</dd>  
<!--
<dt>Definition på engelsk</dt>  
<dd>A homepage for some thing. </dd>  -->
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en den primære webside i det websted hvor organisationen præsenterer sig selv</dd>	
<dt>Defineret af</dt>  
<dd>http://xmlns.com/foaf/0.1/</dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt><dd>http://xmlns.com/foaf/0.1/WebPage</dd></dl>  

### logo  
<dl class="def"><dt>URI</dt>  
<dd>http://schema.org/logo </dd>  
<dt>Foretrukken term</dt>  
<dd>logo</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>et tilknyttet logo</dd>  
<!-- <dt>Definition på engelsk</dt>  
<dd>An associated logo.</dd>  -->
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive organisationens primære logo</dd>
<dt>Defineret af</dt>  
<dd>http://schema.org/</dd>  
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
<dt>Udfaldsrum</dt><dd>  <a href="http://schema.org/ImageObject" title="URI til ImageObject ">http://schema.org/ImageObject</a></dd></dl>  
 

### har sted
### har primært sted
### adresse
### har kontaktoplysning
### formel organisationstype

## Organisationsenhed
<img src="img/OrganizationalUnit.png" alt="organisationsenhed">
<dl class="def">  
<dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#OrganizationalUnit" title="URI til OrganizationalUnit">http://www.w3.org/ns/org#OrganizationalUnit</a></dd>  
<dt>Foretrukken term</dt>  
<dd>organisationsenhed</dd> 
<dt>Alternativ betegnelse</dt>	
<dd>organisatorisk enhed</dd>  	
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 



<dt>Definition</dt>  
<dd>En organisation som en afdeling eller en supportenhed, der er del af en større organisation og kun har fuld anerkendelse i forbindelse med den organisation. Det gælder især, at enheden ikke i sig selv kan opfattes som en juridisk enhed. </dd>  
<!--<dt>Definition på engelsk</dt>  
<dd>An Organization such as a department or support unit which is part of some larger Organization and only has full recognition within the context of that Organization. In particular the unit would not be regarded as a legal entity in its own right. </dd>  
-->
	
<dt>Eksempel </dt>
<dd>Eksempler kan være afdelinger, kontorer, centre, enheder, teams	</dd>
<dt>Anvendelsesnote </dt>
<dd>Bruges til at beskrive en enhed som er del af en større organisation og som kun har en fuld anerkendelse i forbindelse med den organisation. Organisationer består typisk af mange organisationsenheder som såsom afdelinger, kontorer, enheder, teams, grupper osv. </dd>	
<!-- <dt>Anvendelsesnote (en) </dt>
<dd>Used for describing a unit which is part of some larger organization and only has full recognition within the context of that organization. Typically, organisations consist of many organisational units such as deparments, divisions, units, teams, groups etc. </dd>	-->	
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/ns/org#Organization " title="URI til Organization ">http://www.w3.org/ns/org#Organization </a></dd>

</dl>  

### navn

<dl class="def">
<dt>URI</dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#prefLabel" title="URI til prefLabel">http://www.w3.org/2004/02/skos/core#prefLabel</a></dd>
<dt>Foretrukken betegnelse </dt>
<dd>navn</dd>	
<dt>Alternativ betegnelse </dt>
<dd>foretrukken betegnelse</dd>	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive organisationsenhedens primære navn. Det antages at organisationsenheder kun har et sådant navn på hvert sprog. Primære navne kan angives på flere sprog med flere forekomster af egenskaben skos:prefLabel. </dd>
<dt>Anvendelsesnote (en) </dt>
<dd>Used to provide the primary name of the organizationak unit. An organizational unit may only have one such name in any given language. Primary names may be provided in multiple languages with multiple instances of the preferred label property.</dd>	

<dt>Definition </dt>
<dd>Den foretrukne leksikalske betegnelse for en ressource på et givet sprog. </dt>
<!--
<dt>Definition (en) </dt>
<dd>The preferred lexical label for a resource, in a given language. </dd>
-->
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral" title="URI til PlainLiteral">http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral</a></dd>
<dt>Underegenskab af</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#label" title="URI til label ">http://www.w3.org/2000/01/rdf-schema#label </a></dd>
</dl>


### alternativt navn

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#altLabel" title="URI til altLabel">http://www.w3.org/2004/02/skos/core#altLabel</a></dd>  
<dt>Foretrukken term</dt>  
<dd>alternativt navn</dd>  
<dt>Alternativ term</dt>  
<dd>alternativ betegnelse</dd>  	
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>alternative label</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive et accepteret - men ikke foretrukkent - navn for organisationsenheden</dt>	
<!--
<dt>Anvendelsesnote (en) </dt>
<dd>Used to provide an accepted - not not preferred - name for the organizational unit</dd>	-->

<dt>Definition</dt>  
<dd>en alternativ leksikalsk betegnelse for en ressource</dd>  
<!--
<dt>Definition på engelsk</dt>  
<dd>An alternative lexical label for a resource.</dd>  -->

<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">http://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### beskrivelse 
<dl class="def"><dt>URI</dt>  
<dd>http://purl.org/dc/elements/1.1/description</dd>  
<dt>Foretrukken term</dt>  
<dd>beskrivelse</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>description</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en tekstbaseret beskrivelse af organisationsenhedens formål og arbejde</dd>
<!--	
<dt>Anvendelsesnote (en) </dt>
<dd>Used to provide a textual description of the purpose and avtivity of the organizational unit</dd>	-->
<dt>Definition</dt>  
<dd>en forklaring af en ressource</dd>  
<!--
<dt>Definition på engelsk</dt>  
<dd>An account of the resource. </dd>  
-->
<dt>Defineret af</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/" title="URI til DC">http://purl.org/dc/elements/1.1/</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">http://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>

### oprettelsesdato
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/foundingDate" title="URI til foundingDate">http://schema.org/foundingDate</a></dd>  
<dt>Foretrukken term</dt>  
<dd>oprettelsesdato</dd>  
<dt>Alternativ betegnelse (da)</dt>
<dd>grundlæggelsesdato</dd>		
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>founding date</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den dato hvorpå organisationsenheden blev oprettet</dd>	
<!-- 
<dt>Anvendelsesnote (en) </dt> <dd>Used to specifying the date on which the organisational unit was created</dd> -->
<dt>Definition</dt>  
<dd>den dato organisationen blev oprettet</dd>  
<!-- <dt>Definition på engelsk</dt>  
<dd>The date that this organization was founded.</dd>  -->
<dt>Defineret af</dt>  
<dd>http://schema.org/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#date" title="URI til xsd:date">http://www.w3.org/2001/XMLSchema#date</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>



### nedlæggelsesdato
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/dissolutionDate" title="URI til dissolutionDate">http://schema.org/dissolutionDate</a> </dd>  
<dt>Foretrukken term</dt>  
<dd>nedlæggelsesdato</dd>	
<dt>Alternativ betegnelse)</dt>	
<dd>opløsningsdato</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>dissolution date</dd> --> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den dato hvorpå organisationsenheden blev nedlagt</dd>	
<!-- <dt>Anvendelsesnote (en) </dt> <dd>Used to specifying the date on which the organisational unit was dissolved</dt>	 -->
<dt>Definition</dt>  
<dd>den dato organisationen blev nedlagt</dd>  
<!--<dt>Definition på engelsk</dt>  <dd>The date that this organization was dissolved. </dd>  -->
<dt>Defineret af</dt>  
<dd>http://schema.org/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#date" title="URI til xsd:date">http://www.w3.org/2001/XMLSchema#date</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>


### er enhed af
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#unitOf" title="URI til unitOf ">http://www.w3.org/ns/org#unitOf </a></dd>  
<dt>Foretrukken term</dt>  
<dd>enhed af</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>unit of </dd> --> 
<dt>Definition </dt>
<dd>Angiver en organisation som denne organisationsenhed er en del af.</dd>	
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en organisation eller en organisationsenhed, som denne enhed er en del af </dd>  
<!--
<dt>Anvendelsesnote (en)</dt>  
<dd>Indicates an organization or organizational unit of which this unit is a part </dd>  -->
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
<dt>Rækkevidde</dt><dd><a href="http://www.w3.org/ns/org#FormalOrganization & http://www.w3.org/ns/org#OrganizationalUnit" title="URI til OrganizationalUnit">http://www.w3.org/ns/org#FormalOrganization & http://www.w3.org/ns/org#OrganizationalUnit</a></dd>
</dl>  

### har enhed 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasUnit" title="URI til hasUnit ">http://www.w3.org/ns/org#hasUnit </a></dd>  
<dt>Foretrukken term</dt>  
<dd>har enhed</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd>has unit</dd> --> 
<dt>Definition </dt>
<dd>Angiver en enhed som er den del af denne organisation</dd>		
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en organisationsenhed som er en del af denne organisationsenhed</dd>	
<!--
<dt>Anvendelsesnote (en) </dt>
<dd>Used for specifying an organizational unit which is a part of this organizational unit</dd>	-->
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/org#OrganizationalUnit" title="URI til OrganizationalUnit">http://www.w3.org/ns/org#OrganizationalUnit</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>  
</dl>  

### har sted
### enhedstype



## Offentlig organisation

<img src="img/PublicOrganisation.png" alt="offentlig organisation">
<dl class="def">
<dt>URI</dt>
<dd>http://data.europa.eu/m8g/PublicOrganisation </dd>
<dt>Foretrukken betegnelse (da)</dt>
<dd>offentlig organisation</dd>		
<dt>Anvendelsesnote </dt>
<dd>Bruges til at beskrive organisationer der defineres som værende en del af den offentlige sektor under en juridsk ramme på ethvert niveau. En organisation kan bestå af flere underorganisationer, og enhver organisation kan have én eller flere organisationsenheder. Hver af disse beskrives med de samme typer af egenskaber og relationer. </dd>
<!--
<dt>Anvendelsesnote (en)</dt>
<dd>Used for describing organisations that are defined as being part of the public sector by a legal framework at any level. The Public Organization class represents the organization. One organization may comprise several sub-organizations and any organization may have one or more organizational units. Each of these is described using the same properties and relationships. </dd>-->

<dt>Definition </dt>
<dd>Enhver organisation der defineres som værende en del af den offentlige sektor under en juridsk ramme på ethvert niveau</dt>
<!--
<dt>Definition</dt>
<dd>Any Organization that is defined as being part of the public sector by a legal framework at any level.</dd>	-->

<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/ns/org#Organization" title="URI til Organization ">http://www.w3.org/ns/org#Organization </a></dd>

</dl>	 
Klassens egenskaber:	


### navn

<dl class="def">
<dt>URI</dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#prefLabel" title="URI til prefLabel">http://www.w3.org/2004/02/skos/core#prefLabel</a></dd>
<dt>Foretrukken term (da)</dt>
<dd>navn</dd>	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den offentlige organisations primære - ofte juridisk anerkendte - navn. Det antages at organisationer kun har et sådant navn på hvert sprog. Primære navne kan angives på flere sprog med flere forekomster af egenskaben skos:prefLabel. </dd>
<dt>Definition (da) </dt>
<dd>Den foretrukne leksikalske betegnelse for en ressource på et givet sprog. </dt>
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral" title="URI til PlainLiteral">http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral</a></dd>
<dt>Underegenskab af</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#label" title="URI til label">http://www.w3.org/2000/01/rdf-schema#label</a></dd>


</dl>

### alternativt navn

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#altLabel" title="URI til altLabel">http://www.w3.org/2004/02/skos/core#altLabel</a></dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>alternativt navn</dd>  
<dt>Alternativ term på dansk</dt>  
<dd>alternativ betegnelse</dd>  	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive et accepteret - men ikke foretrukkent - navn for den offentlige organisation</dd>	
<dt>Definition på dansk</dt>  
<dd>en alternativ leksikalsk betegnelse for en ressource</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til ">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### beskrivelse 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/description" title="URI til description">http://purl.org/dc/elements/1.1/description</a></dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>beskrivelse</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en tekstbaseret beskrivelse af den offentlige organisations formål og arbejde</dd>	
<dt>Definition på dansk</dt>  
<dd>en forklaring af en ressource</dd>  
<dt>Defineret af</dt>  
<dd>http://purl.org/dc/elements/1.1/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>



### geografisk dækning
<dl class="def"><dt>URI</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/spatial" title="URI til spatial">http://purl.org/dc/elements/1.1/spatial</a></dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>geografisk dækning</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive et administrativt geografisk område som en offentlig organisation dækker forvaltningsmæssigt</dd>	
<dt>Definition på dansk</dt>  
<dd>ressourcens geografiske dækning</dd>  
<dt>Defineret af</dt>  
<dd>http://purl.org/dc/elements/1.1/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### formål

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#purpose" title="URI til hasUnit ">http://www.w3.org/ns/org#purpose</a></dd>  
<dt>Foretrukken term</dt>  
<dd>formål</dd>  
<dt>Definition </dt>
<dd>Angiver organisationens formål. Der kan være mange formål på forskellige abstraktionsniveauer, men det ligger i en organisations natur at have en grund til at eksistere. Denne egenskab er en metode til at dokumentere denne grund. En organisation kan have flere formål. 
</dd>	
<dt>Kommentar </dt>
<dd>Det anbefales, at formålet bliver angivet af en reguleret term- eller kodeliste, ideelt klassen skos:Concept. Rækkevidden er dog åben for andre typer beskrivende systemer. Det er forventet, at profiler i dette vokabularium vil indsnævre rækkevidden af org:purpose. Alternative navne: emne, ansvar (især hvis det bruges på organisatoriske enheder som statslige departementer.)
</dd>	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at referere til klassifikation af offentlige forvaltningsopgaver</dd>	
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href=" http://www.w3.org/2004/02/skos/core#Concept" title="URI til skos:Concept"> http://www.w3.org/2004/02/skos/core#Concept</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>  
</dl>  


## Kontaktoplysning 

<img src="img/ContactPoint.png" alt="kontaktpunkt">

<dl class="def">  
<dt>URI</dt>  
<dd>http://schema.org/ContactPoint</dd>  
<dt>Foretrukken term</dt>  
<dd>kontaktoplysning</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>Oplysning om hvordan man kan kontakte organisationen</dd>  
<!--
<dt>Definition på engelsk</dt>  
<dd>A contact point—for example, a Customer Complaints department. </dd>  -->
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at repræsentere en kontaktoplysning for organisationen</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org ">http://schema.org/</a></dd>  
</dl>  
 
  
Klassens egenskaber:	


### kontakttype  
<dl class="def"><dt>URI</dt>  
<dd>https://schema.org/contactType</dd>  
<dt>Foretrukken term</dt>  
<dd>kontakttype</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Anvendelsenote</dt>  
<dd>Bruges til at klassificere kontaktoplysninger</dd>  
<!--
<dt>Definition på engelsk</dt>  
<dd>A person or organization can have different contact points, for different purposes. For example, a sales contact point, a PR contact point and so on. This property is used to specify the kind of contact point.</dd>  -->
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org ">http://schema.org/</a></dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#langString">http://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
	<dt>Multiplicitet</dt><dd>[0..1]" title="URI til langString</dd><dt>Multiplicitet</dt><dd>[0..1]">http://www.w3.org/1999/02/22-rdf-syntax-ns#langString</dd>
<dt>Multiplicitet</dt><dd>[0..1]</a></dd></dl>


### telefonnummer
<dl class="def"><dt>URI</dt>  
<dd>http://schema.org/telephone </dd>  
<dt>Foretrukken term</dt>  
<dd>telefon</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Accepteret term</dt>  
<dd>telefonnummer</dd>  
<dt>Definition</dt>  
<dd>telefonnummer som tilhører et bestemt mobilabonnement</dd>  
<!--
<dt>Definition på engelsk</dt>  
<dd>The telephone number. </dd>  -->
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org">http://schema.org/</a></dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</a></dd></dl>  



### email 
<dl class="def"><dt>URI</dt>  
<dd>http://schema.org/email</dd>  
<dt>Foretrukken term</dt>  
<dd>e-mail</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Accepteret term</dt>  
<dd>e-mailadresse</dd>  
<dt>Definition</dt>  
<dd>adresse der identificerer en elektronisk postkasse til hvilken meddelelser kan leveres</dd>  
<!--
<dt>Definition på engelsk</dt>  
<dd>Email address. </dd>  -->
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org ">http://schema.org/</a></dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</a></dd></dl>


### url 
<dl class="def"><dt>URI</dt>  
<dd>http://schema.org/u</dd>  
<dt>Foretrukken term</dt>  
<dd>url</dd>   
<dt>Definition</dt>  
<dd>adresse til en ressource på internettet</dd>  
<dt>Eksempler</dt>  
<dd>Eksempelvis en organisations webkontaktformular, Facebook- eller LinkedIn-side</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at referere til en webside hvorigennem en organisation kan kontaktes. Omfatter organisationers anvendelse af sociale medier.</dd>  

<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org ">http://schema.org/</a></dd>  
<dt>Udfaldsrum</dt>
<dd></dd>
<dt>Multiplicitet</dt><dd>[0..1]</a></dd></dl>
	
	
### åbningstider
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/openingHours" title="URI til openingHours ">https://schema.org/openingHours </a></dd>  
<dt>Foretrukken term</dt>  
<dd>åbningstider</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>Angiver den normale åbningstid for organisationen. 
</dd>  
<!--
<dt>Definition på engelsk</dt>  
<dd>The general opening hours for a business. </dd> --> 
<dt>Kommentar</dt>  
<dd>Værdien af denne egenskab er struktureret tekst, der angiver det tidsrum, hvor kontaktpunktet normalt er tilgængeligt.
Dage angives med kombinationer af to bogstaver: Mo, Tu, We, Th, Fr, Sa, Su. Flere dage kan angives, adskilt med komma ’,’ mellem de enkelte dage. Dage og timer kan angives som et tidsrum, med brug af bindestreg ’-’.
Hvis kontaktpunktet f.eks. er åbent mandag til fredag fra 9 -17, vil værdien af schema:openingHours være Mo-Fr 09:00-17:00. Hvis kontaktpunktet er tilgængeligt tirsdag og torsdag mellem 16 og 20, vil værdien være Tu,Th 16:00-20:00.
</dd>  
<!--
<dt>Kommentar på engelsk</dt>  
<dd>Opening hours can be specified as a weekly time range, starting with days, then times per day. Multiple days can be listed with commas ',' separating each day. Day or time ranges are specified using a hyphen '-'. 
Days are specified using the following two-letter combinations: Mo, Tu, We, Th, Fr, Sa, Su.
Times are specified using 24:00 time. For example, 3pm is specified as 15:00.
Here is an example: &lt;time itemprop="openingHours" datetime="Tu,Th 16:00-20:00"&gt;Tuesdays and Thursdays 4-8pm&lt;/time&gt;.
If a business is open 7 days a week, then it can be specified as &lt;time itemprop="openingHours" datetime="Mo-Su"&gt;Monday through Sunday, all day&lt;/time&gt;.
</dd>  -->
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org ">http://schema.org/</a></dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</a></dd></dl>


### tilgænglig i tidsrum 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/hoursAvailable" title="URI til hoursAvailable ">https://schema.org/hoursAvailable </a></dd>  
<dt>Foretrukken term</dt>  
<dd>tilgængelig i tidsrum</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>tidsrum hvor denne service eller dette kontapunkt er tilråde</dd>  
<!-- <dt>Definition på engelsk</dt>  <dd>The hours during which this service or contact is available. </dd>  --> 
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org ">http://schema.org/</a></dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Rækkevidde</dt><dd>OpeningHoursSpecification</dd></dl>  
 
<strong>Objektegenskaber (associationsender): </strong>  

## Åbningstidsspecifikation  
<img src="img/OpeningsHoursSpecification.png" alt="Åbningstidsspecifikation">
<dl class="def">  
<dt>URI</dt>  
<dd><a href="http://schema.org/OpeningHoursSpecification" title="URI til OpeningHoursSpecification ">https://schema.org/OpeningHoursSpecification </a></dd>  
<dt>Foretrukken term</dt>  
<dd>åbningstidsspecifikation</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>En struktureret værdi som giver information om åbningstider for en lokation eller en bestemt service der tilbydes på en lokation.
Lokationen er åben hvis egenskaben ”åbner” er specificeret og ellers lukket.
Hvis værdien for egenskaben ”lukker” er mindre end værdien for ”åbner” så antages det at perioden omfatter næste dag.
</dd>  
<!-- <dt>Definition på engelsk</dt>  
<dd>A structured value providing information about the opening hours of a place or a certain service inside a place. 
The place is open if the opens property is specified, and closed otherwise.
If the value for the closes property is less than the value for the opens property then the hour range is assumed to span over the next day </dd>   -->
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til ">https://schema.org/</a></dd>  
</dl>  
 
  
Klassens egenskaber:	

### lukker  
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/closes" title="URI til closes">https://schema.org/closes</a></dd>  
<dt>Foretrukken term</dt>  
<dd>lukker</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>det tidspunkt lokationen eller tjenesten lukker på den eller de angive ugedage</dd>  
<!-- <dt>Definition på engelsk</dt>  <dd></dd>  --> 
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/closes" title="URI til closes">https://schema.org/closes</a></dd>  
<dt>Udfaldsrum</dt><dd>xsd:time</dd><dt>Multiplicitet</dt><dd>[0..1]</dd></dl>

### åbner 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/opens" title="URI til opens">https://schema.org/opens</a></dd>  
<dt>Foretrukken term</dt>  
<dd>åbner</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>det tidspunkt lokationen eller tjenesten åbner på den eller de angive ugedage</dd>  
<!-- <dt>Definition på engelsk</dt>  <dd></dd>  --> 
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org">https://schema.org/</a></dd>  
<dt>Udfaldsrum</dt><dd>xsd:time</dd><dt>Multiplicitet</dt><dd>[0..1]</dd></dl>

### gælder fra 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/validFrom" title="URI til validFrom ">https://schema.org/validFrom </a></dd>  
<dt>Foretrukken term</dt>  
<dd>gældende fra</dd>  
<!-- <dt>Foretrukken term på engelsk</dt>  <dd></dd> --> 
<dt>Definition</dt>  
<dd>den dato hvorfra noget gælder</dd>  
<!-- <dt>Definition på engelsk</dt>  <dd></dd>  --> 
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org">https://schema.org/</a></dd>  
<dt>Udfaldsrum</dt><dd>xsd:dateTime</dd><dt>Multiplicitet</dt><dd>[0..1]</dd></dl>

### gælder til
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/validThrough" title="URI til validThrough">https://schema.org/validThrough</a></dd>  
<dt>Foretrukken term</dt>  
<dd>gældende indtil</dd>  
<dt>Definition</dt>  
<dd>den dato hvorefter noget ikke længere er gældende</dd>  
<!-- <dt>Definition på engelsk</dt>  <dd></dd>  --> 
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org">https://schema.org/</a></dd>  
<dt>Udfaldsrum</dt><dd>xsd:dateTime</dd><dt>Multiplicitet</dt><dd>[0..1]</dd></dl>  



### ugedag
<dl class="def"><dt>Foretrukken term</dt>  
<dd>ugedag</dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Rækkevidde</dt><dd>DayOfWeek</dd></dl>  
 

## Sted	
<img src="img/Site.png" alt="sted">


Klassens egenskaber:	

### foretrukken betegnelse
### alternativ betegnelse
### produktionsnummer
### stedets adresse


## Adresse
<img src="img/Address.png" alt="adresse">

Klassens egenskaber:	
### navngiven vej
### husnummer
### dørbetegnelse
### etagebetegnelse
### supplerende bynavn
### postboks
### postnummer
### postnummernavn
### fuld adresse
### adresse-id



## Administrativ geografisk inddeling
<img src="img/AdministrativeTerritorialUnits.png" alt="administrativ geografisk inddeling">


## Medlemsskab
<img src="img/Membership.png" alt="medlemsskab">
### betegnelse
### beskrivelse
### dannet på tidspunkt
### ugyldiggjort på tidspunkt
### organisation
### medlem
### rolle

Klassens egenskaber:	

## Rolle
<img src="img/Role.png" alt="rolle">
Klassens egenskaber:	
### foretrukken betegnelse
### alternativ betegnelse
### definition

## Funktion
<img src="img/Function.png" alt="funktion">

## Person

Klassens egenskaber:	
### leder af
### medlem af
### har medlemsskab


## Softwareaktør

Klassens egenskaber:	
### har medlemsskab
### medlem af


## Identifikator
<img src="img/Identifier.png" alt="identifikator">

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/adms#Identifier" title="URI til Identifier">http://www.w3.org/ns/adms#Identifier</a></dd>  
<dt>Foretrukken term</dt>  
<dd>kode</dd>  
<dt>Alternativ term</dt>  
<dd>notation</dd>  	
<dt>Definition</dt>  
<dd>En notation, også kaldt en klassifikationskode, er en streng af tegn, såsom "T58.5" eller "303.4833", som anvendes til at identificere et unikt begreb i et givet begrebssystem.</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en kode der unikt identificer organisation i en bestemt kontekst.</dd> 	
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/adms#" title="URI til ADMS">http://www.w3.org/ns/adms#</a></dd></dl>  


### kode
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#notation" title="URI til notation">http://www.w3.org/2004/02/skos/core#notation</a></dd>  
<dt>Foretrukken term</dt>  
<dd>kode</dd>  
<dt>Alternativ term</dt>  
<dd>notation</dd>  	
<dt>Definition</dt>  
<dd>En notation, også kaldt en klassifikationskode, er en streng af tegn, såsom "T58.5" eller "303.4833", som anvendes til at identificere et unikt begreb i et givet begrebssystem.</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en kode der unikt identificer organisation i en bestemt kontekst.</dd> 	
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum</dt><dd>rdfs:Literal</dd>
<dt>Multiplicitet</dt><dd>[1]</dd></dl>  

### udstedelsesdato
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#notation" title="URI til notation">http://www.w3.org/2004/02/skos/core#notation</a></dd>  
<dt>Foretrukken term</dt>  
<dd>kode</dd>  
<dt>Alternativ term</dt>  
<dd>notation</dd>  	
<dt>Definition</dt>  
<dd>En notation, også kaldt en klassifikationskode, er en streng af tegn, såsom "T58.5" eller "303.4833", som anvendes til at identificere et unikt begreb i et givet begrebssystem.</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en kode der unikt identificer organisation i en bestemt kontekst defineret af den udstedende myndighed</dd> 	
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#notation</a></dd>  
<dt>Udfaldsrum</dt><dd>rdfs:Literal</dd>
<dt>Multiplicitet</dt><dd>[1]</dd></dl>  


### udstedende myndighed
<dl class="def"><dt>URI</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/creator" title="URI til creator">http://purl.org/dc/elements/1.1/creator</a></dd>  
<dt>Foretrukken term</dt>  
<dd>udstedende myndighed</dd>  
<dt>Alternativ term</dt>  
<dd>navn på udstedende myndighed</dd>  	
<dt>Definition</dt>  
<dd>An entity primarily responsible for making the resource.</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive navnet på den myndighed der har udstedt identifikatoren</dd> 	
<dt>Defineret af</dt>  
<dd>http://purl.org/dc/elements/1.1/</dd>  
<dt>Udfaldsrum</dt>
<dd>rdfs:Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd></dl>  



## Billedobjekt
<img src="img/Image.png" alt="billedobjekt">


## Retskilde
<img src="img/LegalResource.png" alt="retskilde">

## Ændringshændelse
<img src="img/ChangeEvent.png" alt="ændringshændelse">




# Klassifikationer

##  formel organisationstype
FormalOrganizationType
### foretrukken betegnelse
### alternativ betegnelse
### definition

##  offentlig organisationstype
PublicFormalOrganizationType
### foretrukken betegnelse
### alternativ betegnelse
### definition

##  organisatorisk enhedstype
OrganizationalUnitType
### foretrukken betegnelse
### alternativ betegnelse
### definition

##  offentlig organisatorisk enhedstype
PublicOrganizationalUnitType
### foretrukken betegnelse
### alternativ betegnelse
### definition

##  type af forvaltningsopgave
PublicAdministrativeTaskType
### foretrukken betegnelse
### alternativ betegnelse
### definition





#  Referencer

#  Bilag

## UML-diagrammer

### UML-diagram: ORG-AP-DK v. 1.0.0-beta 
<a href="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML.png"><img alt="Illustration af ORG-AP-DK v. 1.0.0-beta UML" src="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML.png"></a>

## Eksempler 

### Eksempel på basisinformation
<div class='example'>
<xmp>
<http://example.com/Organization1> a org:FormalOrganization;
    skos:prefLabel  "Organisation 1"@da ;
    skos:prefLabel  "Organization 1"@en ;
    skos:altLabel  "Org 1"@da ;
    skos:altLabel  "Org 1"@en ;
    dct:description "Beskrivelse af organisation 1 "@da ;
    dct:description "Description of organization 1"@da ;
    schema:foundingDate "2011-11-01"^^xsd:date ;
    schema:dissolutionDate "2021-11-01"^^xsd:date ;
    schema:logo <example.com/logo-organization1.png> ;
    foaf:homepage <example.com/homepage/Organization1> .
</xmp>
</div>

### Eksempel på idenfikatorer
<div class='example'>
<xmp>
<http://example.com/Organization1> a org:FormalOrganization; a org:PublicOrganization;
    legal:legalIdentifier [
    a adms:Identifier ;
    skos:notation "#CVR-nummer" ;
    issuingAuthorityName "ERST" ;
  ] ;
    org:identifier [
    a adms:Identifier ;
    skos:notation"#CPR-myndighedskode#" ;
    issuingAuthorityName "CPR" ;
  ] .
</xmp>
</div>
	
	

### Eksempel på organisatoriske strukturer
	
<img src="img/OrganisationalStructure-example.png" alt="organisatorisk struktur - graf">
	
<div class='example'>
<xmp>
    <http://example.com/Organization1> a org:FormalOrganization;
        skos:prefLabel  "Organisation 1"@da ;
        dct:description "Beskrivelse af organisation 1"@da .

    <http://example.com/Organization2> a org:FormalOrganization;
        skos:prefLabel  "Organisation 2"@da ;
        org:subOrganizationOf  <http://example.com/Organization1> ;
        dct:description "Beskrivelse af organisation 2"@da .

    <http://example.com/Organization3> a org:FormalOrganization;
        skos:prefLabel  "Organisation 3"@da ;
        org:subOrganizationOf  <http://example.com/Organization1> ;
        dct:description "Beskrivelse af organisation 3"@da .

    <http://example.com/OrganizationalUnit1> a org:OrganizationalUnit;
        skos:prefLabel  "Organisationsenhed 1"@da ;
        org:unitOf  <http://example.com/Organization3> ;
        dct:description "Beskrivelse af organisationsenhed 1"@da .

    <http://example.com/OrganizationalUnit2> a org:OrganizationalUnit;
        skos:prefLabel  "Organisationsenhed 2"@da ;
        org:unitOf  <http://example.com/OrganizationalUnit1> ;
        dct:description "Beskrivelse af organisationsenhed 2"@da .

    <http://example.com/OrganizationalUnit3> a org:OrganizationalUnit;
        skos:prefLabel  "Organisationsenhed 3"@da ;
        org:unitOf  <http://example.com/OrganizationalUnit1> ;
        dct:description "Beskrivelse af organisationsenhed 3"@da .	
</xmp>
</div>

### Eksempel på kontaktinformation    
<div class='example'>
<xmp>
<http://example.com/Organization1> a org:FormalOrganization; a org:PublicOrganization;
    skos:prefLabel  "Organisation 1"@da ;
    schema:contactPoint [
    a schema:ContactPoint ;
    schema:contactType "Reception" ; 
    schema:telephone "33925200 ";	
    schema:openingsHours "Mo,Tu,We,Th,Fri 08:00-16:00" ] .	    
</xmp>
</div>	    
	
	
<!--
## FormalOrganizationTypes (offentlig organisationstype)  
## PublicFormalOrganizationTypes (offentlig organisationstype)  
## OrganizationalUnitTypes (organisatorisk enhedstype)  
## PublicOrganizationalUnitTypes (offentlig organisatorisk enhedstype)  
## PublicAdministrativeTaskTypes (type af forvaltningsopgave)  
-->



================

[arkitektur.digst.dk](arkitektur.digst.dk)

