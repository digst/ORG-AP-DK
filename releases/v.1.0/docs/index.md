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
	
/* style til egne og andres definitioner r??d/bl??*/
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
Date: 2021-12-22
Max ToC Depth: 3
Markup Shorthands: markdown yes
Repository: digst/ORG-AP-DK
Translation: en https://digst.github.io/ORG-AP-DK/docs/index-en.html
Inline Github Issues: full
Logo: digst...
</pre>


<h1>UDKAST TIL ORG-AP-DK 1.0.0-beta: Anvendelseprofil for organisation </h1>

#  Introduktion
Dette dokument introducerer modellering af organisationer og definerer en anvendelsesprofil baseret p?? internationale standarder. Anvendelsesprofilen udg??r en f??lles model for offentlige s??vel som ikke-offentlige organisationer i en dansk administrativ og f??llesoffentlig kontekst.

## Form??l
Data om organisationer, private eller offentlige, er de helt grundl??ggende oplysninger om organisationers navn, struktur, placering, opgaver, mv. Disse data indg??r i mange forskellige sammenh??nge i offentlige l??sninger. Ved at etablere en f??lles standard for opbygning og udstilling af data om b??de private og offentlige organisationer opn??s ikke blot et f??lles sprog og en f??lles struktur, men grundstenene s??ttes ogs?? for st??rre deling og genbrug af data om organisationer.

## Baggrund
Anvendelsesprofilen ORG-AP-DK udarbejdes i t??t koordiering og samarbejde med KL og en referencegruppe best??ende af deltagere fra kommuner, regioner og statslige myndigheder som udarbejder en beskrivelse af de forretningsm??ssige behov samt bagvedliggende informationsmodel.

Anvendelsesprofilen baseres p?? internationale standarder. S??rligt bidrager de internationale vokabularer [The Organization Ontology (ORG)](https://www.w3.org/TR/vocab-org/) og [Core Public Organisation Vocabulary (CPOV)](https://joinup.ec.europa.eu/release/core-public-organisation-vocabulary-v100) med centrale klasser og egenskaber. ORG-AP-DK er en n??rmere specifikation af, hvordan de internationale modeller skal forst??s og anvendes ??? i denne sammenh??ng til modellering af data vedr??rende organisationer og myndigheder i dansk f??llesoffentlig kontekst. 


## Metode
Anvendelsesprofilen er oprettet i henhold de [F??llesoffentlige regler for begrebs- og datamodellering](https://arkitektur.digst.dk/metoder/regler-begrebs-og-datamodellering), og sammens??tter s??ledes eksisterende vokabularer til en bestemt anvendelse. Teknologisk udspringer de anvendte og foresl??ede modeller af Semantic Web/Linked Dataverdenens modelleringsgrundlag, Resource Description Framework (RDF). En basal forst??else af RDF samt kendskab til de her profilerede vokabularer er et godt udgangspunkt for arbejdet med anvendelsesprofilen. ORG og CPOV foreligger i danske overs??ttelser. Disse oversatte dokumenter udg??r normative referencer for den i efterf??lgende opstillede anvendelsesprofil.

## Profilens anvendelse

<div class='note'>
Inds??t reference til KLs brugsscenarier.
Brugsscenarierne er inddelt i en r??kke perspektiver som beskrives n??rmere i n??ste afsnit.
</div>	

# Grundl??ggende perspektiver

<img src="img/illustration-til-ORG-AP-DK.svg" alt="grundl??ggende perspektiver">

<div class='note'>
Det aktuelle udkast omfatter ikke alle ovenst??ende perspektiver endnu, men vi arbejder l??bende p?? at opdatere modellen.
</div>

## Organisation
Kerneelementerne i denne anvendelsesprofil er de fire klasser der vises p?? nedenst??ende illustration. Overklassen i Organization Ontology er klassen org:Organization. Klassen er bevist holdt som en bred definition af hvad der kan kaldes ???organisation??? og er derfor anvendelig for en meget bred vifte af organisationsbeskrivelser. I denne anvendelsesprofil defineres tre specialiseringer ti klassen org:Organization:

I ORG defineres tre specialiseringer til klassen org:Organization, hhv. org:FormalOrganization, org:OrganizationalUnit, og org:OrganizationalCollaboration. Vokabularet CPOV udvider antallet af specialiseringer af org:Organization ved at tilf??je klassen for offentlige organisationer, cpov:PublicOrganization. Bem??rk at klassen cpov:PublicOrganization ikke er defineret som v??rende disjunkt til nogen af de tre klasser, org:FormalOrganization, org:OrganizationalCollaboration og org:OrganizationalUnit.  Det vil med andre ord sige, at en organisation godt kan v??re erkl??ret at v??re en offentlig organisation og samtidigt ogs?? kan erkl??res at v??re, eksempelvis, en formel organisation.  

- En **organisation** defineres bredt af det grundl??ggende vokabular, ORG, som *???[???] en samling mennesker, der er organiseret i et f??llesskab eller anden social, kommerciel eller politisk struktur. Gruppen har et vist f??lles form??l eller eksistensberettigelse, der r??kker ud over det s??t af personer, der tilh??rer den. En organisation kan i sig selv fungere som akt??r.???*
- En **formel organisation** beskrives af ORG som *???en organisation, der ??? is??r i juridisk forstand ??? er bredt anerkendt og har tilh??rende rettigheder og ansvar. Eksempler kan v??re et aktieselskab eller en velg??rende, statslig eller kirkelig forening???.*
- En **organisationsenhed** beskrives af ORG som *???en organisation som en afdeling eller en supportenhed, der er del af en st??rre organisation og kun har fuld anerkendelse i forbindelse med den organisation. Det g??lder is??r, at enheden ikke i sig selv kan opfattes som en juridisk enhed.???.*
- En **organisatorisk samarbejde** beskrives af ORG som *???et samarbejde mellem to eller flere organisationer s??som et projekt???. Det opfylder kriterierne for at v??re en organisation, idet samarbejdet har en identitet og et veldefineret form??l ufh??ngigt af dets medlemmer, men det det anses hverken formelt som en juridisk enhed eller en underordnet enhed i en st??rre organisation.*
- En **offentlig organisation** beskrives af CPOV som *???enhver organisation, der er defineret som v??rende en del af den offentlige sektor under en juridisk ramme p?? ethvert niveau???.*

<img src="img/View-Organisationer.png" alt="Organisationer">

## Basisinformation

Alle organisationer deler et f??lles s??t af egenskaber til beskrivelse af de mest basale informationer om organisationen. Med basale informationer menes her organisationens navn(e) og beskrivelse af organisationen, en eller flere identifikatorer tildelt organisationen samt logo og hjemmeside.

- En organisation og en organisationsenhed kan have et eller flere navne. Et af navnene p?? et givet sprog vil v??re det **foretrukne navn**, men andre kan angives som **alternative eller skjulte navne**.
- En organisation og en organisationsenhed kan forsynes med en **tekstbaseret beskrivelse**.
- En organisation og en organisationsenhed kan forsynes med en **identifikator** - Til identifikation af en dansk offentlig organisation kan en myndighedskode anvendes. Kommunekoder og regionskoder udg??r begge delm??ngder af myndighedskoder. Juridiske enheder kan identificeres med brug af et CVR-nummer. 
- En organisation kan have en billedlig repr??sentation i form at et **logo** og en **miniature**.
- En organisation kan k??des sammen med dens **hjemmeside** p?? internettet.

Svarer p?? f??lgende brugsscenarier beskrevet af KL: *"3.5 Basisinformation om organisationen"* 

<img src="img/View-Basisinformation.png" alt="basisinformation">

[Se eksempel her](https://digst.github.io/ORG-AP-DK/releases/v.1.0/docs/#eksempel-p-basisinformation)

	
## Organisatorisk struktur
Organisationer kan have eller kan indg?? i en organisatorisk struktur, oftest en hierarkisk struktur. 
Organisationer kan eksempelvis v??re sammensat af andre organisationer i en form for hierarki. Relationerne org:subOrganizationOf og org:hasSubOrganization danner grundlag for disse hierarkiske forbindelser. Bem??rk, at dette hierarki er fuldst??ndigt ??bent. Offentlige organisationer er ofte store og komplekse og kan v??re en samling af mindre organisationer, der hver for sig har en specifik identitet, som kan v??re givet ved lov. Til at sammenk??de organisationen med dens operationelle afdelinger bruges org:hasUnit og org:unitOf. En organisations interne struktur, det vil sige den m??de hvorp?? den er opbygget af organisationsenheder, kan beskrives ligeledes ved brug af relationerne org:hasSubOrganization og org:subOrganizationOf. Organisationer kan have andre former for relationer end de der udtrykkes i form af under- og overorganisatoriske forhold. Til brug for den slags relationer kan egenskaben org:linkedTo anvendes, som en generel beskrivelse af en relation mellem to organisationer. 


- En organisation kan best?? af flere **underorganisationer** der hver for sig har en specifik identitet, fx kan et ministerium best?? af flere underordnede styrelser.
- En organisation kan v??re inddelt i mindre **organisationsenheder** hvis eksistens er afh??ngig af organisationen, fx en afdeling i en st??rre organisation. Organisationer best??r typisk af mange afdelinger, kontorer, enheder, teams, grupper osv. En organisationsenhed kan ogs?? have underordnede enheder.
- Organisationer kan indbyrdes have **andre former for relationer** end de der udtrykkes i form af under- og overorganisatoriske forhold, fx finansiering eller k??derelationer.
- En organisation kan klassificeres som v??rende af en bestemt **organisationstype**. I forhold til offentlige organisationer kunne det fx v??re kommune, region, ministerier, styrelser og mange af de andre former for offentlige organisationer, der er en v??sentlig del af hverdagen i det offentlige organisationslandskab. 

Svarer p?? f??lgende brugsscenarier beskrevet af KL: *"3.1 Hvordan er organisationen bygget op?"* 

<img src="img/View-OrganisationalStructure.png" alt="organisatorisk struktur">

[Se eksempel her](https://digst.github.io/ORG-AP-DK/releases/v.1.0/docs/#eksempel-p-organisatoriske-strukturer)


## Kontaktoplysninger

Kontaktoplysninger for organisationer omfatter i anvendelsesprofilen beskrivelse af kontaktformer, kaldet kontaktpunkter, som e-mail, telefon eller digital post, tidspunkter hvor kontakt er mulig, samt emne og synlighed for kontaktpunktet.

- En organisation eller en organisationsenhed kan give information om hvordan man kommer i kontakt med organisationen eller organisationsenheden.
- En kontaktoplysning kan fx v??re et **telefonnummer**, en **e-mailadresse**, en **url**, herunder **Digital Post**, gennem hvilken man kan kontakte organisationen eller en repr??sentant for organisationen. 
- En kontaktoplysning kan ogs?? indholde information om **??bningstider** - enten p?? simpel vis eller i en mere kompleks struktur med yderligere begr??nsninger. 
- Det kan angives hvorvidt en given kontaktoplysning er **synlig** 

Svarer p?? f??lgende brugsscenarier beskrevet af KL: *"3.4 Hvordan kontaktes organisationen?"* 

<div class='note'>
Anvendelsesprofilen f??lger CPOVs anbefalinger om brug af henholdsvis egenskaben cv:openingsHours og klassen cv:OpeningHoursSpecification til at angive ??bningstider for kontaktpunktet. Dette er gjort p?? trods af at den l??sning vurderes b??de at v??re ikke-intuitiv og at rumme udfordringer i tolkningen.
</div>

<img src="img/View-ContactPoint.png" alt="kontaktoplysning">

[Se eksempel her](https://digst.github.io/ORG-AP-DK/releases/v.1.0/docs//#eksempel-p-kontaktinformation)



## Sted

Med anvendelsesprofilen kan en organisations fysiske placering angives enten direkte med en adresse eller via angivelse af et sted hvor organisationen holder til. Det sted organisationen holder til kan ogs?? tilf??jes en adresse. 
I vokabularet Organization Ontology bruges klassen org:Site til at repr??sentere de steder en organisation har og/eller holder til. Relationerne org:siteOf og org:hasSite danner forbindelser mellem et sted og en organisation. Egenskaben org:hasPrimarySite anvendes til at angive, hvord organisationen prim??rt er beliggende. Dertil kommer egenskaben org:siteAddress, der angiver stedets adresse.
Fra vokabularet Location Core Vocabulary anvendes egenskaben locn:address til at angive en direkte forbindelse mellem organisationen og en adresse. Fra samme vokabular anvendes ogs?? klassen locn:Address, der er defineret for at v??re kompatibel med INSPIREs krav til adresser.

- En organisation og en organisationsenheds **fysiske placering** kan angives. En organisation kan ogs?? have flere forskellige fysiske placeringer.
- Den placering hvor den formelle organisation **prim??rt er beliggende** - hjemstedet - kan dog ogs?? udpeges specifikt. 
- Placeringen kan fx angives med en **adresse** 
- Det kan angives hvilket **administrativt geografisk omr??de** en offentlig organisation d??kker forvaltningsm??ssigt.

<div class='note'>
Resultatet af et kommende arbejde med grunddatakernemodeller forventes at udvide de nuv??rende klasser og egenskaber for stedangivelse, med v??rdifulde og n??dvendige elementer, relateret til ???Danmarks Adresseregister??? (DAR), ???Det Centrale Virksomhedsregister??? (CVR) samt Danmarks Administrativt Geografiske Inddeling (DAGI). De elementer der er medtaget p?? nuv??rende tidspunkt, sikrer at en dansk anvendelseprofil vil v??re b??de anvendelig i almindelighed og kompatibel med EUs CPOV-specifikation. Vokabularer for DAR-, DAGI og CVR-data vil yderligere sikre at danske forvaltningsbehov opfyldes helt.

Denne del af anvendelsesprofilen fastl??gges n??r et kommende vokabularer til beskrivelse af DAR, DAGI og CVR er tilg??ngeligt. Arbejdet forventes at v??re en del af et kommende arbejde med grunddatakernemodeller.
Anvendelsesprofilen vil, p?? sigt, muligg??re en pr??cis udpegning af hvilket administrativt geografisk omr??de en offentlig organisation d??kker. Aktuelt benyttes cv:AdministrativeTerritorialUnit som udpeges med egenskaben dct:spatial. 

</div>

<img src="img/View-Site.png" alt="Sted og adresse">
	
## Medlemsskab og akt??rer

Beskrivelse af et medlemskab er, i denne sammenh??ng, en beskrivelse af et forhold eller en relation mellem enten person eller en organisation til en organisation. En person ansat i en organisation er dermed medlem af organisationen, ligesom en organisation der deltager i et organisatorisk samarbejde er medlem af samarbejdet. Anvendelsesprofilen har et antal m??der, hvorp?? man kan repr??sentere relationer mellem mennesker og organisationer. Erfaringer har vist, at der ikke findes ??n l??sning, der passer til alle. I visse tilf??lde foretr??kker man en meget enkel og direkte repr??sentation. I andre tilf??lde er det n??dvendigt med en mere kompleks repr??sentation for at registrere situationens nuancer. Personers tilh??rsforhold til en organisation kan under anvendelsesprofilen beskrives som enten et medlemskab, som en ans??ttelse eller som v??rende leder af organisationen.


- En persons relation til en organisation og en organisationsenhed kan beskrives som en direkte **medlemskabsrelation**. 
- En organisations relation til en anden organisation kan ogs?? have karakter af et **medlemskab**, som giver mulighed for en mere pr??cis og detaljeret beskrivelse af en medlemsskabsrelation. En person ansat i en organisation kan betragtes som **medlem** af organisationen. I forhold til et givet medlemskab spiller akt??ren i forhold til organisationen en **rolle**, som kan specificeres i en klassifikation over **rolletyper**.
- Relationen mellem en organisation eller organisationsenhed til en person, s??som **ansat** og **leder** kan ogs?? angives direkte.
- En **softwareakt??r**, s??som en softwarerobot (RPA), kan ogs?? fungere som en medlem af en organisation og varetage en bestemt rolle i den forbindelse

Medlemsskab og akt??rer - direkte:
<img src="img/View-MembershipAndAgents-direkte.png" alt="medlemsskab og akt??rer - direkte">

Medlemsskab og akt??rer - kvalificeret:
<img src="img/View-MembershipAndAgents-kvalificeret.png" alt="medlemsskab og akt??rer - kvalificeret">


Svarer p?? f??lgende brugsscenarier beskrevet af KL: *"3.3 Hvem er medlemmer af organisationen?"* 


<div class='note'>
Det aktuelle udkast omfatter endnu ikke beskrivelser af jobfunktioner i organisationen. (Jf. brugsscenariet beskrevet af KL: *"3.2 Hvad arbejder organisationen med?"* )
</div>
	
## Historik og opgaver

Ethvert aspekt af en organisationsm??ssig struktur kan ??ndre sig med tiden. N??r organisationer ??ndrer sig grundl??ggende (ikke blot ved at udskifte personale eller ??ndre den indre struktur), f.eks. ved at danne en ny organisation gennem sammenl??gning eller opk??b, vil den nye organisation typisk blive betegnet med en ny URI. Til angivelse af organisationens oprettelsesdato eller nedl??ggelsesdato benyttes schema:foundingDate og schema:dissolutionDate.
I anvendelsesprofilen skal alle offentlige organisationer beskrives med et organisatorisk form??l. Det organisatoriske form??l for en offentlig organisation antages altid at v??re en forvaltningsopgave. 

- En organisations eller organisationsenheds  **oprettelsesdato** eller **nedl??ggelsedato** kan angives, og dermed kan b??de overordnede organisatoriske ??ndringer og interne omstruktureringer rummes af modellen.
- En offentlig organisation kan tilknyttes de **forvaltningsopgaver** den varetager. Til dette form??l anvendes en klassifikation over forvaltningsopgaver, fx. FORM eller KLE. En forvaltningsopgave kan k??des sammen med den **lovgivning, den politik eller anden retskilde**, der ligger til grund for forvaltningsopgaven.

<img src="img/View-Opgaver.png" alt="Opgaver">

Svarer p?? f??lgende brugsscenarier beskrevet af KL: *"3.6.4 Forretningsh??ndelser?"* 

# UML-diagrammer


## Fuld visning af UML-Diagram 
Den fulde anvendelsesprofil ORG-AP-DK v.1.0.0-beta visualiseret med UML-diagram. 

<p class="center"><a href="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML.png"><img src="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML.png" alt="Illustration af ORG-AP-DK v1.0.0-beta som UML-klassediagram.png"/></a></p>

## Forenklet visning af UML-diagram
Forenklet visning af ORG-AP-DK v.1.0.0-beta uden datatyper og stereotyper og kun p?? dansk)  
<p class="center"><a href="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML-simple.png"><img src="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML-simple.png" alt="Illustration af ORG-AP-DK v1.0.0-beta som UML-klassediagram (kun p?? dansk og uden datatyper og stereotyper).png"/></a></p>


# Navneomr??der
<table class="term-table">
<thead><tr><th>pr??fiks</th><th>navneomr??de</th><th>titel</th></tr></thead><tbody>
 <tr><td>org-ap-dk </td><td>https://data.gov.dk/model/profile/organisation/</td><td>Anvendelsesprofil for organisation</td></tr>	
 <tr><td>org </td><td>http://www.w3.org/ns/org# </td><td>Organization Ontology </td></tr>
 <tr><td>cv</td><td>http://data.europa.eu/m8g/ </td><td>e-Government Core Vocabulary </td></tr>
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
Formelle organisationer og organisationsenheder skal identificeres med en unik, stabil og tv??rg??ende identifikator der er uafh??ngig af det system den er skabt i. Derved kan organisationsdata opm??rket med organisationsstandarden identificeres unikt p?? tv??rs af it-l??sninger og organisatoriske skel. 
	    
Der er et generelt behov for at kunne sammenstille organisationsdata fra forskellige kilder og forretningsdata opm??rket med organisationsdata p?? en sikker og nem m??de. Det betyder, at der er behov for at de relevante organisationer og enheder er opm??rket med en unik, tv??rg??ende identifikator. 
	    
Den tv??rg??ende identifikator ??ndres ikke i hele entitetens livstid. Oprettes en f.eks en ny organisationsenhed som erstatning for en tidligere enhed med samme navn, gives den nye en ny unik identifikator. Identifikatoren kan altid efter tildeling anvendes til at finde entiteten. 

Til dette anvendes en eksisterende global og bredt anvendt syntaks - URIer (Uniform Resource Identifiers). URI-specifikationen definerer en f??lles syntaks for identificering og adressering af ressourcer som p?? internettet. L??s mere om unikke og stabile identifikatorer i [RFC 4646](https://www.ietf.org/rfc/rfc3986.txt) [FAIR-principperne](https://www.go-fair.org/fair-principles/), [EU 10 Rules for Persistent URIs](https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/document/10-rules-persistent-uris) samt [Retningslinjer for stabile http-urier](https://arkitektur.digst.dk/node/588).

Udover den globalt unikke URI, forsynes organisationer ogs?? ofte med andre identifikatorer som udstedes til forskellige form??l af specifikke myndigheder, fx. myndighedskoder og CVR-nummer som denne specifikation ogs?? kan rumme. 


#  Elementer i ORG-AP-DK
I det f??lgende pr??senteres alle egenskaberne i ORG-AP-DK per klasse.

## Formel organisation

<img src="img/FormalOrganization.png" alt="formel organisation">
<dl class="def">
<dt>URI</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization ">http://www.w3.org/ns/org#FormalOrganization </a></dd>
<dt>Foretrukken term </dt>
<dd>formel organisation</dd>	
<dt>Alternativ term </dt>
<dd>organisation</dd>		
<dt>Anvendelsesnote </dt>
<dd>Bruges til at beskrive organisationer der er formelt anerkendt i samfundet med tilh??rende rettigheder og ansvar </dd>
<dt>Definition  </dt>
<dd>En organisation der er bredt anerkendt ??? is??r i juridisk forstand ??? og har tilh??rende rettigheder og ansvar. </dt>
<dt>Eksempel</dt>
<dd>Eksempler kan v??re et aktieselskab, en velg??rende forening, en statslig administrativ enhed og en kirkelig organisation</dd>
<dt>Specialisering af</dt>
<dd><a href="http://www.w3.org/ns/org#Organization" title="URI for org:Organization">http://www.w3.org/ns/org#Organization</a></dd>
</dl>	 

Klassens egenskaber:	

### navn

<dl class="def">
<dt>URI</dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#prefLabel" title="URI til prefLabel">http://www.w3.org/2004/02/skos/core#prefLabel</a></dd>
<dt>Foretrukken term </dt>
<dd>navn</dd>	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive organisationens prim??re - ofte juridisk anerkendte - navn. Det antages at organisationer kun har et s??dant navn p?? hvert sprog. Prim??re navne kan angives p?? flere sprog med flere forekomster af egenskaben skos:prefLabel. </dd>
<dt>Definition  </dt>
<dd>Den foretrukne leksikalske betegnelse for en ressource p?? et givet sprog. </dt>
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Underegenskab af</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#label" title="URI til label">http://www.w3.org/2000/01/rdf-schema#label</a></dd>


</dl>

### alternativt navn

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#altLabel" title="URI til altLabel">http://www.w3.org/2004/02/skos/core#altLabel</a></dd>  
<dt>Foretrukken term</dt>  
<dd>alternativt navn</dd>  
<dt>Alternativ term</dt>  
<dd>alternativ betegnelse</dd>  	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive et accepteret - men ikke foretrukkent - navn for organisationen</dd>	
<dt>Definition</dt>  
<dd>en alternativ leksikalsk betegnelse for en ressource</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### beskrivelse 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/description" title="URI til description">http://purl.org/dc/elements/1.1/description</a></dd>  
<dt>Foretrukken term</dt>  
<dd>beskrivelse</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en tekstbaseret beskrivelse af organisationens form??l og arbejde</dd>	
<dt>Definition</dt>  
<dd>en forklaring af en ressource</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/" title="URI til Dublin Core">http://purl.org/dc/elements/1.1/</a></dd>  
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
<dt>Alternativ betegnelse</dt>
<dd>grundl??ggelsesdato</dd>		
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den dato hvorp?? organisationen blev oprettet</dd>	
<dt>Definition</dt>  
<dd>den dato organisationen blev oprettet</dd>  
<dt>Defineret af</dt>  
<dd>http://schema.org/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#date" title="URI til xsd:date">http://www.w3.org/2001/XMLSchema#date</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>



### nedl??ggelsesdato
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/dissolutionDate" title="URI til dissolutionDate">http://schema.org/dissolutionDate</a> </dd>  
<dt>Foretrukken term</dt>  
<dd>nedl??ggelsesdato</dd>	
<dt>Alternativ betegnelse)</dt>	
<dd>opl??sningsdato</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den dato hvorp?? organisationen blev nedlagt</dd>	
<dt>Definition</dt>  
<dd>den dato organisationen blev nedlagt</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til SCHEMA.ORG">http://schema.org/</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#date" title="URI til xsd:date">http://www.w3.org/2001/XMLSchema#date</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>


### identifikator

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/adms#identifier" title="URI til identifier">http://www.w3.org/ns/adms#identifier</a></dd>  
<dt>Foretrukken term</dt>  
<dd>identifikator</dd>  
<dt>Alternativ term</dt>  
<dd>id</dd> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at knytte en organisation til en identifikator. Bem??rk at en organisation kan have flere identifikatorer tildelt organisationen af forskellige udstedende myndigheder til forskellige form??l.</dd>
<dt>Definition</dt>  
<dd>Knytter en ressource til en ADMS identifikator</dt>
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/adms#" title="URI til ADMS">http://www.w3.org/ns/adms#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/adms#Identifier" title="URI til Identifier">http://www.w3.org/ns/adms#Identifier</a></dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
</dl> 

L??s ogs?? afsnittet <a href="https://digst.github.io/ORG-AP-DK/releases/v.1.0/docs/#globalt-unikke-og-stabile-identifikatorer" title="Globalt Unikke og stabile Identifikatorer">Globalt Unikke og stabile Identifikatorer</a>



### er underorganisation af 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#subOrganizationOf" title="URI til subOrganizationOf">http://www.w3.org/ns/org#subOrganizationOf</a></dd>  
<dt>Foretrukken term</dt>  
<dd>er underorganisation af</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en hierarkisk overordnet organisation. </dt>	
<dt>Definition</dt>  
<dd>Repr??senterer hierarkisk indhold af organisationer eller organisationsenheder. Den angiver en organisation, som omfatter denne organisation. </dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til The Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
</dl>  


### har underorganisation 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasSubOrganization" title="URI til hasSubOrganization">http://www.w3.org/ns/org#hasSubOrganization</a></dd>  
<dt>Foretrukken term</dt>  
<dd>har underorganisation</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en hierarkisk underordnet organisation.</dd>	
<dt>Definition</dt>  
<dd>Repr??senterer hierarkisk indhold af organisationer eller organisationsenheder. Egenskaben angiver en organisation, som er en del af denne organisation. </dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til The Organization Ontology">http://www.w3.org/ns/org#</a></dd> 
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a></dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
</dl>  


### har enhed 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasUnit" title="URI til hasUnit ">http://www.w3.org/ns/org#hasUnit </a></dd>  
<dt>Foretrukken term</dt>  
<dd>har enhed</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en enhed som er en organisatorisk del af en st??rre organisation. Bem??rk at denne organisationsenhed eksistens er afh??ngig af den organisation den er en del af.</dd>
<dt>Definition</dt>  
<dd>Angiver en enhed, som er del af denne organisation, f.eks. en afdeling i en st??rre organisation </dd>  
<dt>Eksempel</dt>  
<dd>Eksempler kan v??re afdelinger, kontorer, sektioner, centre og lignende.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til The Organization Ontology">http://www.w3.org/ns/org#</a></dd> 
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
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en organisation som denne organisation har en eller anden relation til. Det kan eksempelvis v??re en finanseringsrelation eller en forsyningsk??derelation. </dd>
<dt>Definition</dt>  
<dd>Angiver en arbitr??r relation mellem to organisationer. Specialiseringer af denne kan f.eks. bruges til at angive finansiering eller k??derelationer.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til The Organization Ontology">http://www.w3.org/ns/org#</a></dd> 
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a></dd>
</dl>  


### hjemmeside  
<dl class="def"><dt>URI</dt>  
<dd><a href="http://xmlns.com/foaf/0.1/homepage" title="URI til homepage">http://xmlns.com/foaf/0.1/homepage</a></dd> 
<dt>Foretrukken term</dt>  
<dd>hjemmeside</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en den prim??re webside i det websted hvor organisationen pr??senterer sig selv</dd>	
<dt>Definition</dt>  
<dd>en hjemmeside for noget</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://xmlns.com/foaf/0.1/" title="URI til FOAF">http://xmlns.com/foaf/0.1/</a></dd> 
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://xmlns.com/foaf/0.1/Document" title="URI til Document">http://xmlns.com/foaf/0.1/Document</a></dd>
</dl>  

### logo  
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/logo" title="URI til logo">http://schema.org/logo</a></dd> 
<dt>Foretrukken term</dt>  
<dd>logo</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive organisationens prim??re logo</dd>
<dt>Definition</dt>  
<dd>et tilknyttet logo</dd> 
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til SCHEMA.ORG">http://schema.org/</a></dd>  
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://schema.org/ImageObject" title="URI til ImageObject">http://schema.org/ImageObject</a></dd>
</dl>  
 

### har prim??rt sted  
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasPrimarySite" title="URI til hasParimarySite ">http://www.w3.org/ns/org#hasPrimarySite</a></dd> 
<dt>Foretrukken term</dt>  
<dd>har prim??rt sted</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en organisations prim??re sted.</dd>  
<dt>Definition</dt>  
<dd>Angiver organisationens prim??re lokalitet. Det er det sted, hvor organisationen som standard kan kontaktes, og det er ikke n??dvendigvis det formelle hovedkvarter. </dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til The Organization Ontology">http://www.w3.org/ns/org#</a></dd>   
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/org#Site" title="URI til Site">http://www.w3.org/ns/org#Site</a></dd>
</dl>  


### har sted   
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasSite" title="URI til hasSite ">http://www.w3.org/ns/org#hasSite</a></dd> 
<dt>Foretrukken term/dt>  
<dd>har sted</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en hvor en organisation i nogen grad befinder sig.</dd>    
<dt>Definition</dt>  
<dd>Angiver et sted, hvor organisationen i nogen grad befinder sig, selv om det kun er indirekte (f.eks. et virtuelt kontor eller en professional servicevirksomhed, der fungerer som den registrerede adresse for en virksomhed). </dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til The Organization Ontology">http://www.w3.org/ns/org#</a></dd> 
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/org#Site" title="URI til Site">http://www.w3.org/ns/org#Site</a></dd>
</dl>  

### adresse
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#address" title="URI til address">http://www.w3.org/ns/locn#address</a></dd> 
<dt>Foretrukken term</dt>  
<dd>adresse</dd>
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en organisations adresse</dd>     
<dt>Definition</dt>  
<dd>adresserelationen kan knytte enhver ressource til en adresse </dd>   
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd>   
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/locn#Address" title="URI til Address">http://www.w3.org/ns/locn#Address</a></dd>
</dl>  

### har medlem
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasMember" title="URI til hasMember">http://www.w3.org/ns/org#hasMember</a></dd>  
<dt>Foretrukken term</dt>  
<dd>har medlem</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en akt??r som er medlem af organisationen.</dd>	
<dt>Definition</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til The Organization Ontology">http://www.w3.org/ns/org#</a></dd> 
<dt>Udfaldsrum:</dt>
<dd>
<a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a>, 
<a href="http://xmlns.com/foaf/0.1/Person" title="URI til Person">http://xmlns.com/foaf/0.1/Person</a> & SoftwareAgent
</dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
</dl>  



###	ansat  
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/employee" title="URI til employee">http://schema.org/employee</a></dd> 
<dt>Foretrukken term</dt>  
<dd>ansat</dd>    
<dt>Definition</dt>  
<dd>en person som arbejder for denne organisation</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Egenskaben anvendes alene til at angive at den p??g??ldende er ansat. Detaljerede oplysninger om ans??ttelsesforholdet, eksempelvis l??nforhold, ligger udenfor denne anvendelsesprofils form??l.</dd>  
<dt>Defineret af</dt>  
<dd>http://schema.org/</dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://xmlns.com/foaf/0.1/Person" title="URI til Person">http://xmlns.com/foaf/0.1/Person</a></dd> 
</dl>  




### har kontaktoplysning

<dl class="def"><dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/contactPoint" title="URI til ContactPoint">http://data.europa.eu/m8g/contactPoint</a></dd>
<dt>Foretrukken term</dt>  
<dd>har kontaktpunkt</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive hvordan man kommer i kontakt med organisationen</dd>  
<dt>Definition</dt>  
<dd></dd>   
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til eGovernment Core Vocabularies">http://data.europa.eu/m8g/</a></dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://data.europa.eu/m8g/ContactPoint" title="URI til ContactPoint">http://data.europa.eu/m8g/ContactPoint</a></dd>
</dl>  


### formel organisationstype
<dl class="def">
<dt>URI</dt>  
<dd>ovx:formalType</dd>  
<dt>Foretrukken term</dt>  
<dd>formel organisationsstype</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at k??de en formel organisation sammen med et SKOS-begreb tilknyttet klassen ovx:FormalOrganizationType.</dd>   
<dt>Definition</dt>  
<dd></dd>   
<dt>Defineret af</dt>  
<dd></dd>  
<dt>Multiplicitet</dt><dd></dd>  
<dt>Udfaldsrum</dt>
<dd>ovx:FormalOrganizationType</dd>
</dl> 

## Organisationsenhed
<img src="img/OrganizationalUnit.png" alt="organisationsenhed">
<dl class="def">  
<dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#OrganizationalUnit" title="URI til OrganizationalUnit">http://www.w3.org/ns/org#OrganizationalUnit</a></dd>  
<dt>Foretrukken term</dt>  
<dd>organisationsenhed</dd> 
<dt>Alternativ betegnelse</dt>	
<dd>organisatorisk enhed</dd> 
<dt>Anvendelsesnote </dt>
<dd>Bruges til at beskrive en enhed som er del af en st??rre organisation og som kun har en fuld anerkendelse i forbindelse med den organisation. Organisationer best??r typisk af mange organisationsenheder som s??som afdelinger, kontorer, enheder, teams, grupper osv. </dd>	 	
<dt>Definition</dt>  
<dd>En organisation som en afdeling eller en supportenhed, der er del af en st??rre organisation og kun har fuld anerkendelse i forbindelse med den organisation. Det g??lder is??r, at enheden ikke i sig selv kan opfattes som en juridisk enhed. </dd>  
<dt>Eksempel </dt>
<dd>Eksempler kan v??re afdelinger, kontorer, centre, enheder, teams	</dd>
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/ns/org#Organization" title="URI til Organization ">http://www.w3.org/ns/org#Organization </a></dd>

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
<dd>Bruges til at angive organisationsenhedens prim??re navn. Det antages at organisationsenheder kun har et s??dant navn p?? hvert sprog. Prim??re navne kan angives p?? flere sprog med flere forekomster af egenskaben skos:prefLabel. </dd>
<dt>Definition </dt>
<dd>Den foretrukne leksikalske betegnelse for en ressource p?? et givet sprog. </dt>
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral" title="URI til PlainLiteral">http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral</a></dd>
<dt>Underegenskab af</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#label" title="URI til label">http://www.w3.org/2000/01/rdf-schema#label </a></dd>
</dl>


### alternativt navn

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#altLabel" title="URI til altLabel">http://www.w3.org/2004/02/skos/core#altLabel</a></dd>  
<dt>Foretrukken term</dt>  
<dd>alternativt navn</dd>  
<dt>Alternativ term</dt>  
<dd>alternativ betegnelse</dd>  	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive et accepteret - men ikke foretrukkent - navn for organisationsenheden</dt>	
<dt>Definition</dt>  
<dd>en alternativ leksikalsk betegnelse for en ressource</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">http://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### beskrivelse 
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/description" title="URI til description">http://purl.org/dc/elements/1.1/description</a></dd>   
<dt>Foretrukken term</dt>  
<dd>beskrivelse</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en tekstbaseret beskrivelse af organisationsenhedens form??l og arbejde</dd>
<dt>Definition</dt>  
<dd>en forklaring af en ressource</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/" title="URI til Dublin Core">http://purl.org/dc/elements/1.1/</a></dd>  
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
<dt>Alternativ betegnelse </dt>
<dd>grundl??ggelsesdato</dd>		
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den dato hvorp?? organisationsenheden blev oprettet</dd>	
<dt>Definition</dt>  
<dd>den dato organisationen blev oprettet</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til SCHEMA.ORG">http://schema.org/</a></dd>   
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#date" title="URI til xsd:date">http://www.w3.org/2001/XMLSchema#date</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>



### nedl??ggelsesdato
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/dissolutionDate" title="URI til dissolutionDate">http://schema.org/dissolutionDate</a> </dd>  
<dt>Foretrukken term</dt>  
<dd>nedl??ggelsesdato</dd>	
<dt>Alternativ betegnelse)</dt>	
<dd>opl??sningsdato</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den dato hvorp?? organisationsenheden blev nedlagt</dd>	
<dt>Definition</dt>  
<dd>den dato organisationen blev nedlagt</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til SCHEMA.ORG">http://schema.org/</a></dd>   
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
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en organisation eller en organisationsenhed, som denne enhed er en del af </dd>  
<dt>Definition </dt>
<dd>Angiver en organisation som denne organisationsenhed er en del af.</dd>	
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
<dt>Udfaldsrum</dt>
<dd>
<a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a> & 
<a href="http://www.w3.org/ns/org#OrganizationalUnit" title="URI til OrganizationalUnit">http://www.w3.org/ns/org#OrganizationalUnit</a>
</dd>
</dl>  

### har enhed 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasUnit" title="URI til hasUnit ">http://www.w3.org/ns/org#hasUnit </a></dd>  
<dt>Foretrukken term</dt>  
<dd>har enhed</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en organisationsenhed som er en del af denne organisationsenhed</dd>	
<dt>Definition </dt>
<dd>Angiver en enhed som er den del af denne organisation</dd>		
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/org#OrganizationalUnit" title="URI til OrganizationalUnit">http://www.w3.org/ns/org#OrganizationalUnit</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>  
</dl>  

### har sted
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasSite" title="URI til hasSite ">http://www.w3.org/ns/org#hasSite</a></dd> 
<dt>Foretrukken term/dt>  
<dd>har sted</dd>
<dt>Anvendelsesnote</dt>  
<dd>Angiver et sted, hvor organisationsenheden i nogen grad befinder sig, selv om det kun er indirekte (f.eks. et virtuelt kontor). </dd>    
<dt>Definition</dt>  
<dd>et sted, hvor organisationen i nogen grad befinder sig, selv om det kun er indirekte (f.eks. et virtuelt kontor).</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/org#Site" title="URI til Site">http://www.w3.org/ns/org#Site</a></dd>
</dl>  

### adresse
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#address" title="URI til address">http://www.w3.org/ns/locn#address</a></dd> 
<dt>Foretrukken term</dt>  
<dd>adresse</dd>   
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive organisationsenhedens adresse</dd> 
<dt>Definition</dt>  
<dd>adresserelationen kan knytte enhver ressource til en adresse </dd>   
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd>   
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/locn#Address" title="URI til Address">http://www.w3.org/ns/locn#Address</a></dd>
</dl>  

### enhedstype
<dl class="def">
<dt>URI</dt>  
<dd>ovx:unitType</dd>  
<dt>Foretrukken term</dt>  
<dd>enhedstype</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til k??de en organisationsenhed sammen med et SKOS-begreb tilknyttet klassen ovx:OrganizationalUnitType.</dd> 
<dt>Definition</dt>  
<dd></dd>   
<dt>Defineret af</dt>  
<dd></dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd>ovx:OrganizationalUnitType</dd>
</dl> 


## Organisatorisk samarbejde
<img src="img/OrganizationalCollaboration.png" alt="organisatorisk samarbejde">
<dl class="def">
<dt>URI</dt>
<dd><a href="http://www.w3.org/ns/org#OrganizationalCollaboration" title="URI til OrganizationalCollaboration">http://www.w3.org/ns/org#OrganizationalCollaboration</a></dd> 
<dt>Foretrukken betegnelse </dt>
<dd>organisatorisk samarbejde</dd>		
<dt>Anvendelsesnote </dt>
<dd>Bruges til at beskrivel et samarbejde mellem to eller flere organisationer </dd>
<dt>Definition </dt>
<dd>Et samarbejde mellem to eller flere organisationer s??som et projekt???. Det opfylder kriterierne for at v??re en organisation, idet samarbejdet har en identitet og et veldefineret form??l ufh??ngigt af dets medlemmer, men det det anses hverken formelt som en juridisk enhed eller en underordnet enhed i et st??rre organisation</dt>
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/ns/org#Organization" title="URI til The Organization Ontology">http://www.w3.org/ns/org#Organization </a></dd>
</dl>	 

Klassens egenskaber:	

### har medlem
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#hasMember" title="URI til hasMember">http://www.w3.org/ns/org#hasMember</a></dd>  
<dt>Foretrukken term</dt>  
<dd>har medlem</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en formel organisation som indg??r i et organisatorisk samarbejde.</dd>	
<dt>Definition</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til The Organization Ontology">http://www.w3.org/ns/org#</a></dd> 
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a></dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
</dl>  


## Offentlig organisation
<img src="img/PublicOrganisation.png" alt="offentlig organisation">
<dl class="def">
<dt>URI</dt>
<dd><a href="http://data.europa.eu/m8g/PublicOrganisation " title="URI til PublicOrganisation">http://data.europa.eu/m8g/PublicOrganisation</a></dd> 
<dt>Foretrukken betegnelse </dt>
<dd>offentlig organisation</dd>		
<dt>Anvendelsesnote </dt>
<dd>Bruges til at beskrive organisationer der defineres som v??rende en del af den offentlige sektor under en juridsk ramme p?? ethvert niveau. En organisation kan best?? af flere underorganisationer, og enhver organisation kan have ??n eller flere organisationsenheder. Hver af disse beskrives med de samme typer af egenskaber og relationer. </dd>
<dt>Definition </dt>
<dd>Enhver organisation der defineres som v??rende en del af den offentlige sektor under en juridsk ramme p?? ethvert niveau</dt>
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/ns/org#Organization" title="URI til Organization ">http://www.w3.org/ns/org#Organization </a></dd>
</dl>	 
Klassens egenskaber:	


### navn
<dl class="def">
<dt>URI</dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#prefLabel" title="URI til prefLabel">http://www.w3.org/2004/02/skos/core#prefLabel</a></dd>
<dt>Foretrukken term </dt>
<dd>navn</dd>	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive den offentlige organisations prim??re - ofte juridisk anerkendte - navn. Det antages at organisationer kun har et s??dant navn p?? hvert sprog. Prim??re navne kan angives p?? flere sprog med flere forekomster af egenskaben skos:prefLabel. </dd>
<dt>Definition  </dt>
<dd>Den foretrukne leksikalske betegnelse for en ressource p?? et givet sprog. </dt>
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral" title="URI til PlainLiteral">http://www.w3.org/1999/02/22-rdf-syntax-ns#PlainLiteral</a></dd>
<dt>Underegenskab af</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#label" title="URI til label">http://www.w3.org/2000/01/rdf-schema#label</a></dd>

</dl>

### alternativt navn
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#altLabel" title="URI til altLabel">http://www.w3.org/2004/02/skos/core#altLabel</a></dd>  
<dt>Foretrukken term</dt>  
<dd>alternativt navn</dd>  
<dt>Alternativ term</dt>  
<dd>alternativ betegnelse</dd>  	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive et accepteret - men ikke foretrukkent - navn for den offentlige organisation</dd>	
<dt>Definition</dt>  
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
<dt>Foretrukken term</dt>  
<dd>beskrivelse</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en tekstbaseret beskrivelse af den offentlige organisations form??l og arbejde</dd>	
<dt>Definition</dt>  
<dd>en forklaring af en ressource</dd>  
<dt>Defineret af</dt>  
<dd>http://purl.org/dc/elements/1.1/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>



### geografisk d??kning
<dl class="def"><dt>URI</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/spatial" title="URI til spatial">http://purl.org/dc/elements/1.1/spatial</a></dd>  
<dt>Foretrukken term</dt>  
<dd>geografisk d??kning</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive et administrativt geografisk omr??de som en offentlig organisation d??kker forvaltningsm??ssigt</dd>	
<dt>Definition</dt>  
<dd>ressourcens geografiske d??kning</dd>  
<dt>Defineret af</dt>  
<dd>http://purl.org/dc/elements/1.1/</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### form??l
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#purpose" title="URI til hasUnit ">http://www.w3.org/ns/org#purpose</a></dd>  
<dt>Foretrukken term</dt>  
<dd>form??l</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at referere til klassifikation af offentlige forvaltningsopgaver</dd>	
<dt>Definition </dt>
<dd>Angiver organisationens form??l. Der kan v??re mange form??l p?? forskellige abstraktionsniveauer, men det ligger i en organisations natur at have en grund til at eksistere. Denne egenskab er en metode til at dokumentere denne grund. En organisation kan have flere form??l. 
</dd>	
<dt>Kommentar </dt>
<dd>Det anbefales, at form??let bliver angivet af en reguleret term- eller kodeliste, ideelt klassen skos:Concept. R??kkevidden er dog ??ben for andre typer beskrivende systemer. Det er forventet, at profiler i dette vokabularium vil indsn??vre r??kkevidden af org:purpose. Alternative navne: emne, ansvar (is??r hvis det bruges p?? organisationsenheder som statslige departementer.)
</dd>	
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href=" http://www.w3.org/2004/02/skos/core#Concept" title="URI til skos:Concept"> http://www.w3.org/2004/02/skos/core#Concept</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>  
</dl>  

### offentlig organisationstype
<dl class="def">
<dt>URI</dt>  
<dd></dd>  
<dt>Foretrukken term</dt>  
<dd>offentlig organisationstype</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive den formelle organisation som den offentlige organisation er medlem af</dd>  
<dt>Definition</dt>  
<dd></dd>   
<dt>Defineret af</dt>  
<dd></dd>  
<dt>Multiplicitet</dt><dd></dd>  
<dt>Udfaldsrum</dt>
<dd>ovx:PublicOrganizationType</dd>
</dl> 

### medlem af
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#memberOf" title="URI til memberOf">http://www.w3.org/ns/org#memberOf</a></dd> 
<dt>Foretrukken term</dt>  
<dd>medlem af</dd>   
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive det organisatoriske samarbejde som den formelle organisation er medlem af</dd>  
<dt>Definition</dt>  
<dd>Angiver, at en akt??r (person eller anden organisation) er medlem af organisationen uden at angive medlemskabets natur eller rolle i den. </dd> 
<dt>Kommentar</dt>  
<dd>Bem??rk, at valget af navn p?? egenskaben ikke er t??nkt til at begr??nse egenskaber til kun formelle medlemskabsarrangementer. Det er ogs?? tilt??nkt, at det skal d??kke relaterede begreber, f.eks. tilh??rsforhold eller andet engagement i organisationen. Ekstensioner kan specialisere denne relation til at angive bestemte roller inden for organisationen eller mere nuancerede relationer til organisationen. </dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/org#OrganizationalCollaboration" title="URI til OrganizationalCollaboration">http://www.w3.org/ns/org#OrganizationalCollaboration</a></dd>  
</dl>


## Kontaktoplysning 
<img src="img/ContactPoint.png" alt="kontaktoplysning">

<dl class="def">  
<dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/ContactPoint" title="URI til ContactPoint">http://data.europa.eu/m8g/ContactPoint</a></dd>  
<dt>Foretrukken term</dt>  
<dd>kontaktoplysning</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at repr??sentere en kontaktoplysning for organisationen</dd>  
<dt>Definition</dt>  
<dd>Oplysning om hvordan man kan kontakte organisationen</dd>  

<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til Core Vocabularies">http://data.europa.eu/m8g/</a></dd>  
</dl>  
  
Klassens egenskaber:	

### kontakttype  
<dl class="def"><dt>URI</dt>  
<dd><a href="https://schema.org/contactType<" title="URI til contactType">https://schema.org/contactType</a></dd>  
<dt>Foretrukken term</dt>  
<dd>kontakttype</dd>  
<dt>Anvendelsenote</dt>  
<dd>Bruges til at klassificere kontaktoplysninger</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org ">http://schema.org/</a></dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">http://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</a></dd>
</dl>

### synlighed  
<dl class="def"><dt>URI</dt>  
<dd></dd>  
<dt>Foretrukken term</dt>  
<dd>synlighed</dd>  
<dt>Anvendelsenote</dt>  
<dd>Bruges til markere hvorvidt kontaktoplysningen m?? vises offentligt eller ikke</dd>  
<dt>Definition</dt>  
<dd></dd>  
<dt>Udfaldsrum</dt>
<dd></dd>
<dt>Multiplicitet</dt><dd>[0..1]</a></dd>
</dl>

<div class='note'>NY! Fra KL: Definition: markerer hvorvidt kontaktinformationen m?? vises offentligt eller ikke. Kommentar: P?? eksempelvis hjemmesider, markerer denne hvorvidt oplysningen er ekstern tilg??ngelig, kun til intern brug eller hemmelig. Eksempel: - eksternt - internt - hemmeligt </div>


### telefonnummer
<dl class="def"><dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/hasTelephone" title="URI til hasTelephone">http://data.europa.eu/m8g/hasTelephone</a></dd>   
<dt>Foretrukken term</dt>  
<dd>telefon</dd>  
<dt>Accepteret term</dt>  
<dd>telefonnummer</dd>  
<dt>Anvendelsesnote</dt>  
<dd>telefonnummer som man man ringe til hvis man vil i kontakt med organisationen eller organisationsenheden </dd> 
<dt>Definition</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til eGovernment Core Vocabularies">http://data.europa.eu/m8g/</a></dd>   
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</a></dd></dl>  



### email 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/hasEmail" title="URI til hasEmail">http://data.europa.eu/m8g/hasEmail</a></dd>   
<dt>Foretrukken term</dt>  
<dd>e-mail</dd>  
<dt>Accepteret term</dt>  
<dd>e-mailadresse</dd>  
<dt>Anvendelsesnote</dt>  
<dd>emailadresse som man han skrive til hvis man vil i kontakt med organisationen eller organisationsenheden</dd>  
<dt>Definition</dt>  
<dd>adresse der identificerer en elektronisk postkasse</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til eGovernment Core Vocabularies">http://data.europa.eu/m8g/</a></dd> 
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</a></dd>
</dl>


### url 
<dl class="def"><dt>URI</dt>  
<dd></dd>  
<dt>Foretrukken term</dt>  
<dd>url</dd>   
<dt>Definition</dt>  
<dd>adresse til en ressource p?? internettet</dd>  
<dt>Eksempler</dt>  
<dd>Eksempelvis en organisations webkontaktformular, Facebook- eller LinkedIn-side</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at referere til en webside hvorigennem en organisation kan kontaktes. Omfatter organisationers anvendelse af sociale medier.</dd>  
<dt>Defineret af</dt>  
<dd></dd>  
<dt>Udfaldsrum</dt>
<dd></dd>
<dt>Multiplicitet</dt><dd>[0..1]</a></dd>
</dl>
	
<div class='note'>
I EUs  eGovernment Core Vocabularies oprettes muligvis en ny egenskab til angivelse af kontaktpunkter repr??senteret ved url'er
</div>
	
	
### ??bningstider
<dl class="def"><dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/hasEmail" title="URI til hasEmail">http://data.europa.eu/m8g/hasEmail</a></dd>    
<dt>Foretrukken term</dt>  
<dd>??bningstider</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive de normale ??bningstider for organisationen eller organisationsenheden.</dd>  
<dt>Definition</dt>  
<dd>Angiver den normale ??bningstid for organisationen. </dd>  
<dt>Kommentar</dt>  
<dd>V??rdien af denne egenskab er struktureret tekst, der angiver det tidsrum, hvor kontaktpunktet normalt er tilg??ngeligt.
Dage angives med kombinationer af to bogstaver: Mo, Tu, We, Th, Fr, Sa, Su. Flere dage kan angives, adskilt med komma ???,??? mellem de enkelte dage. Dage og timer kan angives som et tidsrum, med brug af bindestreg ???-???.
Hvis kontaktpunktet f.eks. er ??bent mandag til fredag fra 9 -17, vil v??rdien af openingHours v??re Mo-Fr 09:00-17:00. Hvis kontaktpunktet er tilg??ngeligt tirsdag og torsdag mellem 16 og 20, vil v??rdien v??re Tu,Th 16:00-20:00.
</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til Core Vocabularies">http://data.europa.eu/m8g/</a></dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</a></dd></dl>


### tilg??nglig i tidsrum 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/hoursAvailable" title="URI til hoursAvailable ">http://data.europa.eu/m8g/hoursAvailable </a></dd>  
<dt>Foretrukken term</dt>  
<dd>tilg??ngelig i tidsrum</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive i hvilket tidsrum organisationen eller organisationsenheden har ??bent</dd>  
<dt>Definition</dt>  
<dd>tidsrum hvor denne service eller dette kontaktpunkt er tilr??de</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til Core Vocabularies">http://data.europa.eu/m8g/</a></dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://data.europa.eu/m8g/OpeningHoursSpecification" title="URI til OpeningsHoursSpecification">http://data.europa.eu/m8g/OpeningHoursSpecification</a></dd>  
</dl>  
 
<div class='note'>
Det er endnu uvist om eGovernment Core Vocabularies opretter en ny egenskab for hoursAvailable ??kvivalent med egenskaben fra Schema.org
</div>

 
<strong>Objektegenskaber (associationsender): </strong>  

## ??bningstidsspecifikation  
<img src="img/OpeningsHoursSpecification.png" alt="??bningstidsspecifikation">
<dl class="def">  
<dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/OpeningHoursSpecification" title="URI til OpeningHoursSpecification">http://data.europa.eu/m8g/OpeningHoursSpecification </a></dd>  
<dt>Foretrukken term</dt>  
<dd>??bningstidsspecifikation</dd>   
<dt>Definition</dt>  
<dd>En struktureret v??rdi som giver information om ??bningstider for en lokation eller en bestemt service der tilbydes p?? en lokation.
Lokationen er ??ben hvis egenskaben ?????bner??? er specificeret og ellers lukket.
Hvis v??rdien for egenskaben ???lukker??? er mindre end v??rdien for ?????bner??? s?? antages det at perioden omfatter n??ste dag.
</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til Core Vocabularies">http://data.europa.eu/m8g/</a></dd> 
</dl>  
 

 
 
  
Klassens egenskaber:	

### lukker  
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/closes" title="URI til closes">https://schema.org/closes</a></dd>  
<dt>Foretrukken term</dt>  
<dd>lukker</dd>  
<dt>Definition</dt>  
<dd>det tidspunkt lokationen eller tjenesten lukker p?? den eller de angive ugedage</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/closes" title="URI til closes">https://schema.org/closes</a></dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#time" title="URI til xsd:time">http://www.w3.org/2001/XMLSchema#time</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>

### ??bner 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://schema.org/opens" title="URI til opens">https://schema.org/opens</a></dd>  
<dt>Foretrukken term</dt>  
<dd>??bner</dd>  
<dt>Definition</dt>  
<dd>det tidspunkt lokationen eller tjenesten ??bner p?? den eller de angive ugedage</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org">https://schema.org/</a></dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#time" title="URI til xsd:time">http://www.w3.org/2001/XMLSchema#time</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>

### g??lder fra 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/validFrom" title="URI til validFrom">http://data.europa.eu/m8g/validFrom </a></dd>  
<dt>Foretrukken term</dt>  
<dd>g??ldende fra</dd>  
<dt>Definition</dt>  
<dd>den dato hvorfra noget g??lder</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til Core Vocabularies">http://data.europa.eu/m8g/</a></dd> 
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#time" title="URI til xsd:time">http://www.w3.org/2001/XMLSchema#time</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>

### g??lder til
<dl class="def"><dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/validThrough" title="URI til validThrough">http://data.europa.eu/m8g/validThrough</a></dd>  
<dt>Foretrukken term</dt>  
<dd>g??ldende indtil</dd>  
<dt>Definition</dt>  
<dd>den dato hvorefter noget ikke l??ngere er g??ldende</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til Core Vocabularies">http://data.europa.eu/m8g/</a></dd> 
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#time" title="URI til xsd:time">http://www.w3.org/2001/XMLSchema#time</a></dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>  

### ugedag
<dl class="def"><dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/dayOfWeek" title="URI til dayOfWeek">http://data.europa.eu/m8g/dayOfWeek</a></dd>  
<dt>Foretrukken term</dt>  
<dd>ugedag</dd>  
<dt>Definition</dt>  
<dd>den ugedag ??bningstiderne g??lder for </dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til Core Vocabularies">http://data.europa.eu/m8g/</a></dd> 
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://data.europa.eu/m8g/DayOfWeek" title="URI til DayOfWeek">http://data.europa.eu/m8g/DayOfWeek</a></dd>  
</dl>  
 

## Sted	
<img src="img/Site.png" alt="sted">
<dl class="def">  
<dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#Site" title="URI til site">http://www.w3.org/ns/org#Site</a></dd> 
<dt>Foretrukken term</dt>  
<dd>sted</dd>  
<dt>Definition</dt>  
<dd>Kontorfaciliteter eller andre lokaler, hvor organisationen holder til. Mange organisationer er spredt over flere steder, og mange steder vil huse flere organisationer. Typisk vil stedet v??re en fysisk lokation, men muligheden for ikke-fysiske steder s??som virtuelle kontorer med en tilknyttet postboks og telefonreception udelukkes ikke.  </dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive et sted hvor organisationen eller organisationsenheden holder til.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
</dl>  
 
 

Klassens egenskaber:	

### foretrukken betegnelse
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#prefLabel" title="URI til prefLabel">http://www.w3.org/2004/02/skos/core#prefLabel</a></dd>  
<dt>Foretrukken term</dt>  
<dd>foretrukken betegnelse</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive stedets foretrukne navn</dd>  
<dt>Definition</dt>  
<dd>den foretrukne leksikalske betegnelse for en ressource p?? et givet sprog</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">http://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>
</dl>  




### alternativ betegnelse 
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#altLabel" title="URI til altLabel">http://www.w3.org/2004/02/skos/core#altLabel</a></dd>  
<dt>Foretrukken term</dt>  
<dd>alternativ betegnelse</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive stedets alternative navn</dd>  
<dt>Definition</dt>  
<dd>en alternativ leksikalsk betegnelse for en ressource</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">http://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>
</dl>


<!-- ### produktionsnummer -->

### stedets adresse
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#address" title="URI til address ">http://www.w3.org/ns/locn#address</a></dd> 
<dt>Foretrukken term</dt>  
<dd>adresse</dd>   
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en stedets adresse</dd>  
<dt>Definition</dt>  
<dd>adresserelationen kan knytte enhver ressource til en adresse </dd>   
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd>   
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/locn#Address" title="URI til Address">http://www.w3.org/ns/locn#Address</a></dd>
</dl>  




## Adresse
<img src="img/Address.png" alt="adresse">

<div class='note'>
Denne del af anvendelsesprofilen fastl??gges endeligt n??r et kommende vokabularer til beskrivelse af DAR er tilg??ngeligt. Arbejdet forventes at v??re en del af et kommende arbejde med grunddatakernemodeller.
</div>


Klassens egenskaber:	
### vejnavn
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#thoroughfare" title="URI til thoroughfare">http://www.w3.org/ns/locn#thoroughfare</a></dd>
<dt>Foretrukken term</dt>  
<dd>vejnavn</dd>   
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive den del af adressen som repr??senterer vejens navn.</dd>  
<dt>Definition</dt>  
<dd>adressekomponent som repr??senterer navnet p?? en passage eller str??kning fra en lokation til et andet. En vej er ikke n??dvendigvis en gade eller vej p?? land, men kan ogs?? v??re en vandvej eller anden feature</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd>   
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>


###	positionsindikator
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#locatorDesignator" title="URI til locatorDesignator">http://www.w3.org/ns/locn#locatorDesignator</a></dd>
<dt>Foretrukken term</dt>  
<dd>positionsindikator</dd>   
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive husnummer, d??rbetegnelse, etagebetegnelse og lignende.</dd>  
<dt>Definition</dt>  
<dd>Et nummer elller tegnsekvens som g??r det muligt for en bruger eller applikation at fortolke, parse og formatere positionsindikatorer. Med andre ord, s?? er det husnummeret, lejlighedsnummeret, etc. For en adresse s??som "Lejlighed 3, 17 Bridge Street", er positionsindikatoreren "Lejlighed 3, 17"</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd>   
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>

<div class='note'>
Det sk??nnes at locn:locatorDesignator d??kker flere egenskaber i DAR, fx. husnummertekst, etagebetegnelse og d??rbetengelse i DAR, hvorfor b??de disse og locn:locatorDesignator medtages her.
</div>

###	husnummertekst  
<dl class="def"><dt>URI</dt>  
<dd>https://data.gov.dk/model/profile/dar#husnummertekst </dd>  
<dt>Foretrukken term</dt>  
<dd>husnummer</dd>  
<dt>Definition</dt>  
<dd>husnummeret til adressen inklusive evt. bogstav </dd>  
<dt>Defineret af</dt>  
<dd>https://data.gov.dk/model/profile/dar#</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#string" title="URI til xsd:string">http://www.w3.org/2001/XMLSchema#string</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd></dl>

###	d??rbetegnelse  
<dl class="def"><dt>URI</dt>  
<dd>https://data.gov.dk/model/profile/dar#d??rbetegnelse </dd>  
<dt>Foretrukken term</dt>  
<dd>d??rbetegnelse</dd>  
<dt>Definition</dt>  
<dd>Betegnelse, som angiver den adgangsd??r e.l. som adressen identificerer </dd>  
<dt>Defineret af</dt>  
<dd>https://data.gov.dk/model/profile/dar#</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#string" title="URI til xsd:string">http://www.w3.org/2001/XMLSchema#string</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd></dl>

###	etagebetegnelse  
<dl class="def"><dt>URI</dt>  
<dd>https://data.gov.dk/model/profile/dar#etagebetegnelse </dd>  
<dt>Foretrukken term</dt>  
<dd>etagebetegnelse</dd>  
<dt>Definition</dt>  
<dd>Betegnelse, som angiver hvilken etage den del af bygningen som adressen identificerer, er beliggende p?? </dd>   
<dt>Defineret af</dt>  
<dd>https://data.gov.dk/model/profile/dar#</dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#string" title="URI til xsd:string">http://www.w3.org/2001/XMLSchema#string</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>

### supplerende bynavn
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#addressArea" title="URI til addressArea">http://www.w3.org/ns/locn#addressArea</a></dd>
<dt>Foretrukken term</dt>  
<dd>supplerende bynavn</dd>   
<dt>Definition</dt>  
<dd>Det eller de ord der navngiver et geografisk omr??de eller en lokalitet der grupperer en r??kke addresserbare objekter uden at denne gruppering betragtes som en administrativ enhed. Dette vil typisk v??re en del af en by, et nabolag eller en landsby.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd>   
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>


### postboks
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#poBox" title="URI til poBox">http://www.w3.org/ns/locn#poBox</a></dd>
<dt>Foretrukken term</dt>  
<dd>postboks</dd>   
<dt>Definition</dt>  
<dd>nummer der identificerer en postboks</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd> 
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>

### postnummer
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#postCode" title="URI til postCode">http://www.w3.org/ns/locn#postCode</a></dd>
<dt>Foretrukken term</dt>  
<dd>postnummer</dd>  
<dt>Definition</dt>  
<dd>kode som identificerer et postdistrikt</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd> 
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>

### postnummernavn
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#postName" title="URI til postName">http://www.w3.org/ns/locn#postName</a></dd> 
<dt>Foretrukken term</dt>  
<dd>post name</dd>  
<dt>Definition</dt>  
<dd>navnet p?? et postdistrikt, typisk et bynavn.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl> 

	
### fuld adresse

<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#fullAddress" title="URI til fullAddress">http://www.w3.org/ns/locn#fullAddress</a></dd>  
<dt>Foretrukken term</dt>  
<dd>full address</dd>  
<dt>Definition</dt>  
<dd>Den fulde adresse strevet som en tekststring, med eller uden formatering. </dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd></dl>

### adresse-id
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/locn#addressID" title="URI til addressID">http://www.w3.org/ns/locn#addressID</a></dd>   
<dt>Foretrukken term</dt>  
<dd>adresse-id</dd>   
<dt>Definition</dt>  
<dd>globalt unik identifikator for en instans af en adresse</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd> 
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2000/01/rdf-schema#Literal" title="URI til Literal">http://www.w3.org/2000/01/rdf-schema#Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd></dl>


## Administrativ geografisk inddeling
<img src="img/AdministrativeTerritorialUnits.png" alt="administrativ geografisk inddeling">

<dl class="def">  
<dt>URI</dt>  
<dd><a href="http://data.europa.eu/m8g/AdministrativeTerritorialUnit" title="URI til AdministrativeTerritorialUnit">http://data.europa.eu/m8g/AdministrativeTerritorialUnit</a></dd>  
<dt>Foretrukken term</dt>  
<dd>administrativ geografisk inddeling</dd> 
<dt>Anvendelsesnote</dt>  
<dd>Bruges til angive hvilket administrativt geografisk omr??de en offentlig organisation d??kker forvaltningsm??ssigt.</dd>  
<dt>Definition</dt>  
<dd> </dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/m8g/" title="URI til CV">http://data.europa.eu/m8g/</a></dd>  
</dl>  

<div class='note'>
Denne del af anvendelsesprofilen fastl??gges endeligt n??r et kommende vokabularer til beskrivelse af DAGI er tilg??ngeligt. Arbejdet forventes at v??re en del af et kommende arbejde med grunddatakernemodeller.
Anvendelsesprofilen vil, p?? sigt, muligg??re en pr??cis udpegning af hvilket administrativt geografisk omr??de en offentlig organisation d??kker. Aktuelt benyttes cv:AdministrativeTerritorialUnit som udpeges med egenskaben dct:spatial. 
</div>

Klassens egenskaber:	

### geometri
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2000/01/rdf-schema#label" title="URI til label">http://www.w3.org/2000/01/rdf-schema#label</a></dd>  
<dt>Foretrukken term</dt>  
<dd>geometri</dd>    
<dt>Anvendelsesnote</dt>  
<dd>Bruges til </dd>  
<dt>Definition</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/locn#" title="URI til Core Location">http://www.w3.org/ns/locn#</a></dd> 
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#string" title="URI til xsd:string">http://www.w3.org/2001/XMLSchema#string</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>  



## Medlemsskab
<img src="img/Membership.png" alt="medlemsskab">
 
<dl class="def">  
<dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#Membership" title="URI til Membership">http://www.w3.org/ns/org#Membership</a></dd>  
<dt>Foretrukken term</dt>  
<dd>medlemsskab</dd> 
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at give en pr??cis og detaljeret beskrivelse af en medlemsskabsrelation. Klassen, og dermed dens forekomster, har tre faste relationer: 1) til den organisation noget er medlem af, 2) til den akt??r der er medlemmet, 3 til den rolle akt??ren har i kraft af medlemsskabet.
</dd>  
<dt>Definition</dt>  
<dd>Repr??senterer en n-aritets-relation mellem en akt??r, en organisation og en rolle. </dd>  
<dt>Kommentar</dt>  
<dd>Det er muligt direkte at angive medlemskab uafh??ngigt af den specifikke rolle gennem brug af egenskaben org:memberOf. </dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
</dl>  

Klassens egenskaber:	

### betegnelse
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/2000/01/rdf-schema#label" title="URI til label">http://www.w3.org/2000/01/rdf-schema#label</a></dd>  
<dt>Foretrukken term</dt>  
<dd>betegnelse</dd>    
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive medlemskabets navn</dd>  
<dt>Definition</dt>  
<dd>et menneskel??sbart navn for noget</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2000/01/rdf-schema#" title="URI til RDFS">http://www.w3.org/2000/01/rdf-schema#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#string" title="URI til xsd:string">http://www.w3.org/2001/XMLSchema#string</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>  

### beskrivelse 
<dl class="def"><dt>URI</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/description" title="URI til description">http://purl.org/dc/elements/1.1/description</a></dd> 
<dt>Foretrukken term</dt>  
<dd>beskrivelse</dd>   
<dt>Definition</dt>  
<dd>en forklaring af en ressource</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en beskrivelse af medlemsskabet</dd> 
<dt>Defineret af</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/" title="URI til Dublin Core">http://purl.org/dc/elements/1.1/</a></dd> 
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#string" title="URI til xsd:string">http://www.w3.org/2001/XMLSchema#string</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>

### dannet p?? tidspunkt
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/prov#generatedAtTime" title="URI til generatedAtTime">http://www.w3.org/ns/prov#generatedAtTime</a></dd> 
<dt>Foretrukken term</dt>  
<dd>dannet p?? tidspunkt</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive hvorn??r medlemsskabet blev dannet</dd> 
<dt>Definition</dt>  
<dd>det tidspunkt hvor en entitet blev skabt og efterf??lgende kan tages i brug</dd>  
<dt>Defineret af</dt>   
<dd><a href="http://www.w3.org/ns/prov#" title="URI til PROV-O">http://www.w3.org/ns/prov#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#dateTime" title="URI til xsd:dateTime">http://www.w3.org/2001/XMLSchema#dateTime</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>

### ugyldiggjort p?? tidspunkt
<dl class="def"><dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/prov#invalidatedAtTime" title="URI til invalidatedAtTime ">http://www.w3.org/ns/prov#invalidatedAtTime</a></dd>  
<dt>Foretrukken term</dt>  
<dd>ugyldiggjort p?? tidspunkt</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive hvorn??r medlemsskabet blev ugyldiggjort</dd> 
<dt>Definition</dt>  
<dd>det tidspunkt hvor en entitet blev ugyldiggjort (dvs. ikke l??ngere kan tages i brug)</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/prov#" title="URI til PROV-O">http://www.w3.org/ns/prov#</a></dd>   
<dt>Udfaldsrum:</dt>
<dd><a href="http://www.w3.org/2001/XMLSchema#dateTime" title="URI til xsd:dateTime">http://www.w3.org/2001/XMLSchema#dateTime</a></dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>



### organisation 
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#organization" title="URI til organization">http://www.w3.org/ns/org#organization</a></dd>  
<dt>Foretrukken term</dt>  
<dd>organisation</dd>   
<dt>Accepteret term</dt>  
<dd>medlemsorganisation</dd>  
<dt>Definition</dt>  
<dd>Angiver organisationen, hvor akt??ren er medlem</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt><dd>[1..1]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a> el. <a href="http://www.w3.org/ns/org#OrganizationalUnit" title="URI til OrganizationalUnit">http://www.w3.org/ns/org#OrganizationalUnit</a> el. <a href="http://www.w3.org/ns/org#OrganizationalCollaboration" title="URI til OrganizationalCollaboration">http://www.w3.org/ns/org#OrganizationalCollaboration</a></dd>  
</dl>  



### medlem 
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#member" title="URI til member">http://www.w3.org/ns/org#member</a></dd>  
<dt>Foretrukken term</dt>  
<dd>medlem</dd>   
<dt>Definition</dt>  
<dd>Angiver personen (eller anden akt??r, herunder organisation), der er involveret i medlemskabsrelationen. </dd> 
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive den organisation, organisationsenhed, person eller softwareakt??r, der er involveret i medlemskabsrelationen.</dd>   
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt><dd>[1..1]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/org#FormalOrganization" title="URI til FormalOrganization">http://www.w3.org/ns/org#FormalOrganization</a> el. <a href="http://www.w3.org/ns/org#OrganizationalUnit" title="URI til OrganizationalUnit">http://www.w3.org/ns/org#OrganizationalUnit</a> el. foaf:Person el. SoftwareAgent</dd>  
</dl>  



### rolle

<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/org#role" title="URI til role">http://www.w3.org/ns/org#role</a></dd>  
<dt>Foretrukken term</dt>  
<dd>rolle</dd>  
<dt>Definition</dt>  
<dd>Angiver den rolle, som akt??ren spiller i medlemskabsrelationen i en organisation. </dd>  
<dt>Kommentar</dt>  
<dd>Kan ogs?? bruges med org:Post til at angive de roller, som enhver besidder af posten spiller. </dd>  
<dt>Defineret af</dt>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive den rolle, som akt??ren spiller i medlemskabsrelationen i en organisation, organisationsenhed eller organisatorisk samarbejde.</dd> 
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt><dd>[1..1]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://www.w3.org/ns/org#Role" title="URI til Role">http://www.w3.org/ns/org#Role</a></dd> 
</dl>  
 

	



## Rolle
<img src="img/Role.png" alt="rolle">

<dl class="def">  
<dt>URI</dt>  
<dd>http://www.w3.org/ns/org#Role</dd>  
<dt>Foretrukken term</dt>  
<dd>rolle</dd>  
<dt>Definition</dt>  
<dd>Angiver en rolle, som en person eller anden akt??r kan indtage i en organisation. </dd>  
<dt>Kommentar</dt>  
<dd>Forekomster af denne klasse beskriver den abstrakte rolle. Brug en forekomst af org:Membership til at angive en specifik forekomst af en person, der spiller den rolle i en specifik organisation. </dd>  
<dt>Anvendelsesnote</dt>  
<dd>Forekomster af denne klasse beskriver en rolle en akt??r kan indtage i en organisation. Bem??rk at klassen org:Role kan specialiseres. Dette kan eksempelvis benyttes til at angive roller indenfor en s??rlig faggruppe, eller til roller specifkke for organisatoriske samarbejder.</dd> 
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd> 
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#Concept" title="URI til Concept">http://www.w3.org/2004/02/skos/core#Concept</a></dd> 
</dl>  

Klassens egenskaber:	
### foretrukken betegnelse
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#prefLabel" title="URI til prefLabel">http://www.w3.org/2004/02/skos/core#prefLabel</a></dd>  
<dt>Foretrukken term</dt>  
<dd>foretrukken betegnelse</dd>  
<dt>Definition</dt>  
<dd>den foretrukne leksikalske betegnelse for en ressource p?? et givet sprog</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive den foretrukne betegnelsen for rollen</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt><dd>[1..*]</dd>
</dl>  


### alternativ betegnelse 
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#altLabel" title="URI til altLabel">http://www.w3.org/2004/02/skos/core#altLabel</a></dd>  
<dt>Foretrukken term</dt>  
<dd>alternativ betegnelse</dd>  
<dt>Definition</dt>  
<dd>en alternativ leksikalsk betegnelse for en ressource</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en alternativ betegnelse for rollen</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum:</dt>
<dd><a href="https://www.w3.org/1999/02/22-rdf-syntax-ns#langString" title="URI til langString">https://www.w3.org/1999/02/22-rdf-syntax-ns#langString</a></dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>
</dl>

### definition
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/2004/02/skos/core#definition</dd>  
<dt>Foretrukken term</dt>  
<dd>definition</dd>  
<dt>Definition</dt>  
<dd>beskrivelse af betydningen af et begreb</dd> 
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive rollens definition</dd>   
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd> 
<dt>Udfaldsrum:</dt>
<dd>rdf:langString</dd>
<dt>Multiplicitet</dt><dd>[1..*]</dd>
</dl>

## Person

<img src="img/Person.png" alt="Person">

<dl class="def">  
<dt>URI</dt>  
<dd>http://xmlns.com/foaf/0.1/Person </dd>  
<dt>Foretrukken term</dt>  
<dd>person</dd>  
<dt>Definition</dt>  
<dd>Klassen Person repr??senterer mennesker bredt forst??et - levende, d??de, virkelige eller fiktive. Klassen Person er en specialisering af klassen Akt??r idet alle mennesker betragtes ???akt??rer??? i FOAF. </dd>  
<dt>Anvendelsesnote</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd>http://xmlns.com/foaf/0.1/</dd>  
</dl>  
 
 
Klassens egenskaber:	
### leder af 
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/ns/org#headOf</dd>  
<dt>Foretrukken term</dt>  
<dd>leder af</dd>   
<dt>Definition</dt>  
<dd>Angiver at denne person er leder af eller formel chef for organisationen.</dd>  
<dt>Kommentar</dt>  
<dd>Dette vil typisk betyde at denne person ogs?? er roden i grafen for ???org:reportsTo, selvom en organisation kan have mere end ??n leder.</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive at en person er leder eller formel chef for den p??g??ldende formelle organisation eller for den organisatoriske enhed</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd>org:FormalOrganization</dd>
</dl>  

### medlem af
<dl class="def">
<dt>URI</dt>  
<dd>http://www.w3.org/ns/org#memberOf</dd>  
<dt>Foretrukken term</dt>  
<dd>medlem af</dd>   
<dt>Definition</dt>  
<dd>Angiver, at en akt??r (person eller anden organisation) er medlem af organisationen uden at angive medlemskabets natur eller rolle i den. </dd>  
<dd>Bem??rk, at valget af navn p?? egenskaben ikke er t??nkt til at begr??nse egenskaber til kun formelle medlemskabsarrangementer. Det er ogs?? tilt??nkt, at det skal d??kke relaterede begreber, f.eks. tilh??rsforhold eller andet engagement i organisationen. Ekstensioner kan specialisere denne relation til at angive bestemte roller inden for organisationen eller mere nuancerede relationer til organisationen. </dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive den organisation personen er medlem af</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd>org:FormalOrganization</dd>
</dl>  
 
### har medlemsskab
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/ns/org#hasMembership </dd>  
<dt>Foretrukken term</dt>  
<dd>har medlemsskab</dd>  
<dt>Definition</dt>  
<dd>Angiver en medlemskabsrelation, som den akt??r spiller. </dd>  
<dt>Anvendelsesnote</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd> 
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd>org:Membership</dd>
</dl>  


## Softwareakt??r
<img src="img/SoftwareAgent.png" alt="softwareakt??r">
<dl class="def">  
<dt>URI</dt>  
<dd></dd>  
<dt>Foretrukken term</dt>  
<dd>softwareakt??r</dd>  
<dt>Definition</dt>  
<dd></dd>  
<dt>Anvendelsesnote</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd></dd>  
</dl>  

Klassens egenskaber:	
### medlem af
<dl class="def">
<dt>URI</dt>  
<dd>http://www.w3.org/ns/org#memberOf</dd>  
<dt>Foretrukken term</dt>  
<dd>medlem af</dd>   
<dt>Definition</dt>  
<dd>Angiver, at en akt??r (person eller anden organisation) er medlem af organisationen uden at angive medlemskabets natur eller rolle i den. </dd>  
<dd>Bem??rk, at valget af navn p?? egenskaben ikke er t??nkt til at begr??nse egenskaber til kun formelle medlemskabsarrangementer. Det er ogs?? tilt??nkt, at det skal d??kke relaterede begreber, f.eks. tilh??rsforhold eller andet engagement i organisationen. Ekstensioner kan specialisere denne relation til at angive bestemte roller inden for organisationen eller mere nuancerede relationer til organisationen. </dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive den organisation softwareakt??ren er medlem af</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>   
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd>org:FormalOrganization</dd>
</dl>  
 
### har medlemsskab
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/ns/org#hasMembership </dd>  
<dt>Foretrukken term</dt>  
<dd>har medlemsskab</dd>  
<dt>Definition</dt>  
<dd>Angiver en medlemskabsrelation, som den akt??r spiller. </dd>  
<dt>Anvendelsesnote</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/org#" title="URI til Organization Ontology">http://www.w3.org/ns/org#</a></dd>   
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd>org:Membership</dd>
</dl>  



<!--
## Funktion
<img src="img/Function.png" alt="funktion">
-->

## Identifikator
<img src="img/Identifier.png" alt="identifikator">

<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/ns/adms#Identifier" title="URI til Identifier">http://www.w3.org/ns/adms#Identifier</a></dd>  
<dt>Foretrukken term</dt>  
<dd>kode</dd>  
<dt>Alternativ term</dt>  
<dd>notation</dd>  
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en kode der unikt identificer organisation i en bestemt kontekst.</dd> 	
<dt>Definition</dt>  
<dd>En notation, ogs?? kaldt en klassifikationskode, er en streng af tegn, s??som "T58.5" eller "303.4833", som anvendes til at identificere et unikt begreb i et givet begrebssystem.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/ns/adms#" title="URI til ADMS">http://www.w3.org/ns/adms#</a></dd>
</dl>  


### kode
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#notation" title="URI til notation">http://www.w3.org/2004/02/skos/core#notation</a></dd>  
<dt>Foretrukken term</dt>  
<dd>kode</dd>  
<dt>Alternativ term</dt>  
<dd>notation</dd>  	
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en kode der unikt identificer organisation i en bestemt kontekst.</dd> 
<dt>Definition</dt>  
<dd>En notation, ogs?? kaldt en klassifikationskode, er en streng af tegn, s??som "T58.5" eller "303.4833", som anvendes til at identificere et unikt begreb i et givet begrebssystem.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#</a></dd>  
<dt>Udfaldsrum</dt><dd>rdfs:Literal</dd>
<dt>Multiplicitet</dt><dd>[1]</dd>
</dl>  

### udstedelsesdato
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#notation" title="URI til notation">http://www.w3.org/2004/02/skos/core#notation</a></dd>  
<dt>Foretrukken term</dt>  
<dd>kode</dd>  
<dt>Alternativ term</dt>  
<dd>notation</dd>  	
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive en kode der unikt identificer organisation i en bestemt kontekst defineret af den udstedende myndighed</dd> 
<dt>Definition</dt>  
<dd>En notation, ogs?? kaldt en klassifikationskode, er en streng af tegn, s??som "T58.5" eller "303.4833", som anvendes til at identificere et unikt begreb i et givet begrebssystem.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://www.w3.org/2004/02/skos/core#" title="URI til SKOS">http://www.w3.org/2004/02/skos/core#notation</a></dd>  
<dt>Udfaldsrum</dt><dd>rdfs:Literal</dd>
<dt>Multiplicitet</dt><dd>[1]</dd>
</dl>  


### udstedende myndighed
<dl class="def"><dt>URI</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/creator" title="URI til creator">http://purl.org/dc/elements/1.1/creator</a></dd>  
<dt>Foretrukken term</dt>  
<dd>udstedende myndighed</dd>  
<dt>Alternativ term</dt>  
<dd>navn p?? udstedende myndighed</dd>  	
<dt>Anvendelsesnote</dt>  
<dd>Bruges til at angive navnet p?? den myndighed der har udstedt identifikatoren</dd> 	
<dt>Definition</dt>  
<dd>En entitet som er prim??rt ansvarlig for ressourcens skabelse.</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://purl.org/dc/elements/1.1/" title="URI til Dublin Core">http://purl.org/dc/elements/1.1/</a></dd> 
<dt>Udfaldsrum</dt>
<dd>rdfs:Literal</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>
</dl>  



## Billedobjekt
<img src="img/Image.png" alt="billedobjekt">
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://schema.org/ImageObject" title="URI til ImageObject">http://schema.org/ImageObject</a></dd>  
<dt>Foretrukken term</dt>  
<dd>billedobjekt</dd>  	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at beskrive en billedfil som repr??senterer en organisation</dd>	
<dt>Definition</dt>  
<dd>En billedfil</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til Schema.org">http://schema.org/</a></dd>  
</dl>


### miniature  
<dl class="def"><dt>URI</dt>  
<dd><a href="https://schema.org/thumbnail" title="URI til thumbnail">https://schema.org/thumbnail</a></dd> 
<dt>Foretrukken term</dt>  
<dd>miniature</dd>  
<dt>Anvendelsesnote </dt>
<dd>Bruges til at angive en miniature af organisationens logo</dd>
<dt>Definition</dt>  
<dd>Miniature af et billede eller en video</dd> 
<dt>Defineret af</dt>  
<dd><a href="http://schema.org/" title="URI til SCHEMA.ORG">http://schema.org/</a></dd>  
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
<dt>Udfaldsrum</dt>
<dd><a href="http://schema.org/ImageObject" title="URI til ImageObject">http://schema.org/ImageObject</a></dd>
</dl>  
 



## Retskilde
<img src="img/LegalResource.png" alt="retskilde">
<dl class="def">
<dt>URI</dt>  
<dd><a href="http://data.europa.eu/eli/ontology#LegalResource" title="URI til LegalResource">http://data.europa.eu/eli/ontology#LegalResource</a></dd>  
<dt>Foretrukken term</dt>  
<dd>retskilde</dd>  	
<dt>Anvendelsesnote </dt>
<dd>Bruges til at beskrive en retskilde</dd>	
<dt>Definition</dt>  
<dd>Et v??rk i et juridisk korpus</dd>  
<dt>Defineret af</dt>  
<dd><a href="http://data.europa.eu/eli/ontology#" title="URI til ELI">http://data.europa.eu/eli/ontology#</a></dd>  
</dl>


<!--
## ??ndringsh??ndelse
<img src="img/ChangeEvent.png" alt="??ndringsh??ndelse">
-->



# Klassifikationer

<img src="img/View-FDAOrganisationer.png" alt="Klassifikation af organisationer">


##  formel organisationstype

<dl class="def">  
<dt>URI</dt>  
<dd>ovx:FormalOrganizationType</dd>  
<dt>Foretrukken term</dt>  
<dd>formel organisationstype</dd>  
<dt>Definition</dt>  
<dd>Klassen er en underklasse til skos:Concept og indeholder, som begreber, formelle organisationstyper.</dd>  
<dt>Defineret af</dt>  
<dd>OVX</dd> 
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#Concept" title="URI til Concept">http://www.w3.org/2004/02/skos/core#Concept</a></dd> 
</dl>


##  offentlig organisationstype
<dl class="def">  
<dt>URI</dt>  
<dd>ovx:PublicFormalOrganizationType</dd>  
<dt>Foretrukken term</dt>  
<dd>offentlig organisationstype</dd>  
<dt>Definition</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd>OVX</dd> 
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#Concept" title="URI til Concept">http://www.w3.org/2004/02/skos/core#Concept</a></dd> 
</dl>

##  organisatorisk enhedstype


<dl class="def">  
<dt>URI</dt>  
<dd>ovx:OrganizationalUnitType</dd>  
<dt>Foretrukken term</dt>  
<dd>organisatorisk enhedstype</dd>  
<dt>Definition</dt>  
<dd>Klassen er en underklasse til skos:Concept og indeholder, som begreber, organisatoriske enhedstyper</dd>  
<dt>Defineret af</dt>  
<dd>OVX</dd> 
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#Concept" title="URI til Concept">http://www.w3.org/2004/02/skos/core#Concept</a></dd> 
</dl>

##  offentlig organisatorisk enhedstype

<dl class="def">  
<dt>URI</dt>  
<dd>ovx:PublicOrganizationalUnitType</dd>  
<dt>Foretrukken term</dt>  
<dd>offentlig organisatorisk enhedstype</dd>  
<dt>Definition</dt>  
<dd></dd>  
<dt>Defineret af</dt>  
<dd>OVX</dd> 
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#Concept" title="URI til Concept">http://www.w3.org/2004/02/skos/core#Concept</a></dd> 
</dl>

##  type af forvaltningsopgave

<dl class="def">  
<dt>URI</dt>  
<dd>ovx:PublicAdministrativeTaskType</dd>  
<dt>Foretrukken term</dt>  
<dd>type af forvaltningsopgave</dd>  
<dt>Definition</dt>  
<dd>Klassen er en underklasse til skos:Concept og indeholder, som begreber, de offentlige forvaltningsopgaver der er relevante for danske offentlige organisationer. </dd>  
<dt>Defineret af</dt>  
<dd>OVX</dd> 
<dt>Specialisering af </dt>
<dd><a href="http://www.w3.org/2004/02/skos/core#Concept" title="URI til Concept">http://www.w3.org/2004/02/skos/core#Concept</a></dd> 
</dl>



#  Referencer

#  Bilag

## UML-diagrammer

### UML-diagram: ORG-AP-DK v. 1.0.0-beta 
<a href="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML.png"><img alt="Illustration af ORG-AP-DK v. 1.0.0-beta UML" src="img/Illustration-ORG-AP-DK-v1.0.0-beta-UML.png"></a>

## Eksempler 

### Eksempel p?? basisinformation
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

### Eksempel p?? idenfikatorer
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
	
	

### Eksempel p?? organisatoriske strukturer
	
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

### Eksempel p?? kontaktinformation    
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
	
	
================

[arkitektur.digst.dk](arkitektur.digst.dk)

