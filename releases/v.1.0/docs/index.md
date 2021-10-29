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
Abstract: 'ORG-AP-DK 1.0.0' .
Boilerplate: copyright no, conformance no, abstract no
Shortname: ORG-AP-DK
Revision: 1.0.0-beta 
Date: 2021-09-13
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

#  Modellens grundlæggende struktur


<img src="img/OrganisationalStructure.png" alt="organisatorisk struktur">

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

#  Gældende krav og overensstemmelse


#  Elementer i ORG-AP-DK
I det følgende præsenteres alle egenskaberne i ORG-AP-DK per klasse.

## Formel organisation

<img src="img/FormalOrganization.png" alt="formel organisation">
<dl class="def">
<dt>URI</dt>
<dd>http://www.w3.org/ns/org#FormalOrganization </dd>
<dt>Foretrukken term (da)</dt>
<dd>formel organisation</dd>	
<dt>Alternativ term (da)</dt>
<dd>organisation</dd>		
<dt>Anvendelsesnote (da) </dt>
<dd>organisation der er formelt anerkendt i samfundet med tilhørende rettigheder og ansvar </dt>
<dt>Anvendelsesnote (en) </dt>
<dd>organization which is recognized in the world at large with associated rights and responsibilities</dd>
<!--
<dt>Definition (da) </dt>
<dd>En organisation, der – især i juridisk forstand – er bredt anerkendt og har tilhørende rettigheder og ansvar. Eksempler kan være et aktieselskab eller en velgørende, statslig eller kirkelig forening.</dt>
<dt>Definition (en) </dt>
<dd>An Organization which is recognized in the world at large, in particular in legal jurisdictions, with associated rights and responsibilities. Examples include a corporation, charity, government or church.</dd>
-->
<dt>Specialisering af</dt>
<dd>http://www.w3.org/ns/org#Organization </dd>
<dt>Kravniveau</dt>
<dd>Obligatorisk</dd>
</dl>	 

Klassens egenskaber:	

### navn

<dl class="def">
<dt>URI</dt>
<dd>http://www.w3.org/2004/02/skos/core#prefLabel</dd>
<dt>Foretrukken term (da)</dt>
<dd>navn</dd>	
<dt>Alternativ term (da)</dt>
<dd>foretrukken term</dd>	
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at angive organisationens primære -ofte juridisk anerkendte - navn. Det antages at organisationer kun har et sådant navn på hvert sprog. Primære navne kan angives på flere sprog med flere forekomster af egenskaben skos:prefLabel. </dt>
<dt>Anvendelsesnote (en) </dt>
<dd>Used to provide the primary - often legally recognised - name of the organization. An organization may only have one such name in any given language. Primary names may be provided in multiple languages with multiple instances of the preferred label property.</dd>	
<!--
<dt>Definition (da) </dt>
<dd>Den foretrukne leksikalske betegnelse for en ressource på et givet sprog. </dt>
<dt>Definition (en) </dt>
<dd>The preferred lexical label for a resource, in a given language. </dd>
-->
<dt>Udfaldsrum</dt>
<dd>rdf:PlainLiteral</dd>
<dt>Underegenskab af</dt>
<dd>rdfs:label </dd>
<dt>Kravniveau</dt>
<dd>Obligatorisk</dd>
</dl>


### alternativt navn

<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/2004/02/skos/core#altLabel</dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>alternativt navn</dd>  
<dt>Alternativ term på dansk</dt>  
<dd>alternativ betegnelse</dd>  	
<dt>Foretrukken term på engelsk</dt>  
<dd>alternative label</dd>  
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at angive et accepteret - men ikke foretrukkent - navn for organisationen</dt>	
<dt>Anvendelsesnote (en) </dt>
<dd>Used to provide an accepted - not not preferred - name for the organisation</dt>	
<!--
<dt>Definition på dansk</dt>  
<dd>en alternativ leksikalsk betegnelse for en ressource</dd>  
<dt>Definition på engelsk</dt>  
<dd>An alternative lexical label for a resource.</dd>  

<dt>Defineret af</dt>  
<dd>http://www.w3.org/2004/02/skos/core#</dd>  
<dt>Udfaldsrum:</dt>
<dd>rdf:langString</dd>
-->
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### beskrivelse 
<dl class="def"><dt>URI</dt>  
<dd>http://purl.org/dc/elements/1.1/description</dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>beskrivelse</dd>  
<dt>Foretrukken term på engelsk</dt>  
<dd>description</dd>  
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at angive en tekstbaseret beskrivelse af organisationens formål og arbejde</dt>	
<dt>Anvendelsesnote (en) </dt>
<dd>Used to provide a textual description of the purpose and avtivity of the organisation</dt>	
<!--
<dt>Definition på dansk</dt>  
<dd>en forklaring af en ressource</dd>  
<dt>Definition på engelsk</dt>  
<dd>An account of the resource. </dd>  
-->
<dt>Defineret af</dt>  
<dd>http://purl.org/dc/elements/1.1/</dd>  
<dt>Udfaldsrum:</dt>
<dd>rdf:langString</dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>
</dl>


### oprettelsesdato
<dl class="def"><dt>URI</dt>  
<dd>http://schema.org/foundingDate</dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>oprettelsesdato</dd>  
<dt>Alternativ betegnelse (da)</dt>
<dd>grundlæggelsesdato</dd>		
<dt>Foretrukken term på engelsk</dt>  
<dd>founding date</dd>  
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at angive den dato hvorpå organisationen blev oprettet</dt>	
<dt>Anvendelsesnote (en) </dt>
<dd>Used to specifying the date on which the organisation was created</dt>
<!--
<dt>Definition på dansk</dt>  
<dd>den dato organisationen blev oprettet</dd>  
<dt>Definition på engelsk</dt>  
<dd>The date that this organization was founded.</dd>  
-->
<dt>Defineret af</dt>  
<dd>http://schema.org/</dd>  
<dt>Udfaldsrum:</dt>
<dd>xsd:date</dd>
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>



### nedlæggelsesdato
<dl class="def"><dt>URI</dt>  
<dd>http://schema.org/dissolutionDate </dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>nedlæggelsesdato</dd>	
<dt>Alternativ betegnelse (da)</dt>	
<dd>opløsningsdato</dd>  
<dt>Foretrukken term på engelsk</dt>  
<dd>dissolution date</dd>  
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at angive den dato hvorpå organisationen blev nedlagt</dt>	
<dt>Anvendelsesnote (en) </dt>
<dd>Used to specifying the date on which the organisation was dissolved</dt>	
<!--
<dt>Definition på dansk</dt>  
<dd>den dato organisationen blev nedlagt</dd>  
<dt>Definition på engelsk</dt>  
<dd>The date that this organization was dissolved. </dd>  
-->
<dt>Defineret af</dt>  
<dd>http://schema.org/</dd>  
<dt>Udfaldsrum:</dt>
<dd>xsd:date</dd>-->
<dt>Multiplicitet</dt>
<dd>[0..1]</dd>
</dl>


### er underorganisation af 
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/ns/org#subOrganizationOf</dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>er underorganisation af</dd>  
<dt>Foretrukken term på engelsk</dt>  
<dd>sub-organization of</dd>  
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at angive en organisation som omfatter denne organisation. Bemærk at denne undeorganisation har en selvstændig eksistens - modsat en organisationsenhed</dt>	
<dt>Anvendelsesnote (en) </dt>
<dd>Used to specifying an organisation which contains this organisation. Note that this sub-organisation has an independent eksistence - unlike an organisational unit</dt>	<!--	
<dt>Definition på dansk</dt>  
<dd>Repræsenterer hierarkisk indhold af organisationer eller organisatoriske enheder. Den angiver en organisation, som omfatter denne organisation. </dd>  
<dt>Definition på engelsk</dt>  
<dd>Represents hierarchical containment of Organizations or OrganizationalUnits; indicates an Organization which contains this Organization. Inverse of `org:hasSubOrganization`. </dd>  
-->
<dt>Defineret af</dt>  
<dd>http://www.w3.org/ns/org#</dd>  
<dt>Udfaldsrum:</dt>
<dd>http://www.w3.org/ns/org#FormalOrganization</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
</dl>  


### har underorganisation 
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/ns/org#hasSubOrganization </dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>har underorganisation</dd>  
<dt>Foretrukken term på engelsk</dt>  
<dd>has sub-organization</dd>
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at angive en organisation som er omfattet af denne organisation</dt>	
<dt>Anvendelsesnote (en) </dt>
<dd>Used to specifying an organisation which contain this organisation/dt>	
<!--	
<dt>Definition på dansk</dt>  
<dd>Repræsenterer hierarkisk indhold af organisationer eller organisatoriske enheder. Den angiver en organisation, som er en del eller et barn af denne organisation. </dd>  
<dt>Definition på engelsk</dt>  
<dd>Represents hierarchical containment of Organizations or Organizational Units; indicates an organization which is a sub-part or child of this organization. Inverse of `org:subOrganizationOf`. </dd>  
-->
<dt>Defineret af</dt>  
<dd>http://www.w3.org/ns/org#</dd>
<dt>Udfaldsrum:</dt>
<dd>http://www.w3.org/ns/org#FormalOrganization</dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
</dl>  


### har enhed 
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/ns/org#hasUnit </dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>har enhed</dd>  
<dt>Foretrukken term på engelsk</dt>  
<dd>has unit </dd>  
<!--
<dt>Definition på dansk</dt>  
<dd>Angiver en enhed, som er del af denne organisation, f.eks. en afdeling i en større organisation </dd>  
<dt>Definition på engelsk</dt>  
<dd>Indicates a unit which is part of this Organization, e.g. a Department within a larger FormalOrganization. Inverse of `org:unitOf` </dd>  
-->
<dt>Defineret af</dt>  
<dd>http://www.w3.org/ns/org#</dd>  
<dt>Udfaldsrum:</dt>
<dd>http://www.w3.org/ns/org#OrganizationalUnit</dd>
<dt>Multiplicitet</dt>
<dd>[0..*]</dd>  
</dl>  



## Organisationsenhed

<dl class="def">  
<dt>URI</dt>  
<dd>http://www.w3.org/ns/org#OrganizationalUnit</dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>organisationsenhed</dd> 
<dt>Alternativ betegnelse (da)</dt>	
<dd>organisatorisk enhed</dd>  	
<dt>Foretrukken term på engelsk</dt>  
<dd>organizational unit</dd>  
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at beskrive en enhed som er del af en større organisation og kun har en fuld anerkendelse i forbindelse med den organisation. Organisationer består typisk af mange organisationsenheder som såsom afdelinger, kontorer, enheder, teams, grupper osv. </dt>		
<dt>Anvendelsesnote (en) </dt>
<dd>Used for describing a unit which is part of some larger organization and only has full recognition within the context of that organization. Typically, organisations consist of many organisational units such as deparments, divisions, units, teams, groups etc. </dt>		
<!--
<dt>Definition på dansk</dt>  
<dd>En organisation som en afdeling eller en supportenhed, der er del af en større organisation og kun har fuld anerkendelse i forbindelse med den organisation. Det gælder især, at enheden ikke i sig selv kan opfattes som en juridisk enhed. </dd>  
<dt>Definition på engelsk</dt>  
<dd>An Organization such as a department or support unit which is part of some larger Organization and only has full recognition within the context of that Organization. In particular the unit would not be regarded as a legal entity in its own right. </dd>  
-->
<dt>Defineret af</dt>  
<dd>http://www.w3.org/ns/org#</dd>  
<dt>Specialisering af </dt>
<dd>http://www.w3.org/ns/org#Organization </dd>
<dt>Kravniveau</dt>
<dd>Valgfri</dd>
</dl>  

### navn

### alternativt navn

### beskrivelse

### oprettelsesdato

### nedlæggelsesdato

### er enhed af
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/ns/org#unitOf </dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>enhed af</dd>  
<dt>Foretrukken term på engelsk</dt>  
<dd>unit of</dd>  
<dt>Definition på dansk</dt>  
<dd>Angiver en organisation, som denne enhed er en del af, f.eks. en afdeling i en større organisation. </dd>  
<dt>Definition på engelsk</dt>  
<dd>Indicates an Organization of which this Unit is a part, e.g. a Department within a larger FormalOrganization. This is the inverse of `org:hasUnit`. </dd>  
<dt>Defineret af</dt>  
<dd>http://www.w3.org/ns/org#</dd>  
<dt>Multiplicitet</dt><dd>[1..1]</dd>  
<dt>Rækkevidde</dt><dd>FormalOrganization</dd></dl>  

### er underenhed af 
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/ns/org#subOrganizationOf</dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>er underenhed af</dd>  
<dt>Foretrukken term på engelsk</dt>  
<dd>sub-organization of</dd>  
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at angive en organisationsenhed som omfatter denne organisationsenhed. </dt>	
<dt>Anvendelsesnote (en) </dt>
<dd>Used to specifying an organizational unit which contains this organizational unit.</dt>	
<dt>Defineret af</dt>  
<dd>http://www.w3.org/ns/org#</dd>  
<dt>Udfaldsrum:</dt>
<dd>http://www.w3.org/ns/org#FormalOrganization</dd>
<dt>Multiplicitet</dt><dd>[0..1]</dd>  
</dl>  


### har underenhed 
<dl class="def"><dt>URI</dt>  
<dd>http://www.w3.org/ns/org#hasSubOrganization </dd>  
<dt>Foretrukken term på dansk</dt>  
<dd>har underenhed</dd>  
<dt>Foretrukken term på engelsk</dt>  
<dd>has sub-organization</dd>
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at angive en organisationsenhed som er omfattet af denne organisationsenhed</dt>	
<dt>Anvendelsesnote (en) </dt>
<dd>Used to specifying an organizational unit which contains this organizational unit/dt>	

<dt>Defineret af</dt>  
<dd>http://www.w3.org/ns/org#</dd>
<dt>Udfaldsrum:</dt>
<dd>http://www.w3.org/ns/org#FormalOrganization</dd>
<dt>Multiplicitet</dt><dd>[0..*]</dd>  
</dl>  





## Offentlig organisation

<img src="img/PublicOrganisation.png" alt="offentlig organisation">
<dl class="def">
<dt>URI</dt>
<dd>http://data.europa.eu/m8g/PublicOrganisation </dd>
<dt>Foretrukken betegnelse (da)</dt>
<dd>offentlig organisation</dd>		
<dt>Anvendelsesnote (da) </dt>
<dd>Bruges til at beskrive organisationer der defineres som værende en del af den offentlige sektor under en juridsk ramme på ethvert niveau</dd>
<dt>Anvendelsesnote (en)</dt>
<dd>Used for describing organisations that are defined as being part of the public sector by a legal framework at any level </dd>

<dt>Definition (da) </dt>
<dd>Any Organization that is defined as being part of the public sector by a legal framework at any level.</dt>
<dt>Definition (en) </dt>
<dd>Enhver organisation, der er defineret som værende en del af den offentlige sektor under en juridisk ramme på ethvert niveau.</dd>	

<dt>Specialisering af </dt>
<dd>http://www.w3.org/ns/org#Organization </dd>
<dt>Kravniveau</dt>
<dd>Valgfri</dd>
</dl>	 
Klassens egenskaber:	

-->

<!--
## Klassen org:Site (sted)  
## Klassen locn:Address (adresse)  
## Klassen schema:ContactPoint (kontaktpunkt) 
## Klassen schema:OpeningHoursSpecification (åbningstider) 
## Klassen schema:ImageObject (billedobjekt)   
## Klassen org:Membership (medlemskab)  
## Klassen org:Role (rolle)  
## Klassen foaf:Person (person)  
## Klassen foaf:Document (dokument) 
## Klassen cpsv:FormalFramework (formel ramme)  
## Klassen cpov:FoundationEvent (grundlæggelseshændelse)  
## Klassen org:ChangeEvent (ændringshændelse)  

## Klassen dagi:AdministrativInddeling (administrativ inddeling) 
## Klassen ?:FormalOrganizationType (offentlig organisationstype)  
## Klassen ?:PublicFormalOrganizationType (offentlig organisationstype)  
## Klassen ?:OrganizationalUnitType (organisatorisk enhedstype)  
## Klassen ?:PublicOrganizationalUnitType (offentlig organisatorisk enhedstype)  
## Klassen ?:PublicAdministrativeTaskType (type af forvaltningsopgave)  
-->




#  Referencer

#  Bilag

## UML-diagrammer
## Eksempler 

<!--
## FormalOrganizationTypes (offentlig organisationstype)  
## PublicFormalOrganizationTypes (offentlig organisationstype)  
## OrganizationalUnitTypes (organisatorisk enhedstype)  
## PublicOrganizationalUnitTypes (offentlig organisatorisk enhedstype)  
## PublicAdministrativeTaskTypes (type af forvaltningsopgave)  
-->



================

[arkitektur.digst.dk](arkitektur.digst.dk)

