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
Title: ORG-AP-DK 1.0.0
Status: LD
URL: https://data.gov.dk/model/profile/ORG-AP-DK/
Editor Term: Udgiver, Udgivere 
Editor: Digitaliseringsstyrelsen,, arkitektur@digst.dk
Abstract: 'ORG-AP-DK 1.0.0' .
Boilerplate: copyright no, conformance no, abstract no
Shortname: ORG-AP-DK
Revision: 1.0.0 
Date: 2021-09-13
Max ToC Depth: 3
Markup Shorthands: markdown yes
Repository: digst/ORG-AP-DK
Translation: en https://digst.github.io/ORG-AP-DK/docs/index-en.html
Inline Github Issues: full
Logo: digst...
</pre>


<h1>UDKAST TIL ORG-AP-DK 1.0.0: Anvendelseprofil for organisation </h1>

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

## Klassen org:FormalOrganization 

<img src="img/FormalOrganization.png" alt="formel organisation">
<dl class="def">
<dt>URI</dt>
<dd>http://data.europa.eu/m8g/PublicOrganisation </dd>
<dt>Foretrukken betegnelse (da)</dt>
<dd>formel organisation</dd>	
<dt>Anvendelsesnote (da) </dt>
<dd>En organisation, der – især i juridisk forstand – er bredt anerkendt og har tilhørende rettigheder og ansvar. Eksempler kan være et aktieselskab eller en velgørende, statslig eller kirkelig forening. </dt>
<dt>Anvendelsesnote (en) </dt>
<dd>An Organization which is recognized in the world at large, in particular in legal jurisdictions, with associated rights and responsibilities. Examples include a corporation, charity, government or church.  </dd>
<dt>Underklasse af</dt>
<dd>http://www.w3.org/ns/org#Organization </dd>
<dt>Kravniveau</dt>
<dd>?</dd>
</dl>	 

Klassens egenskaber:	

### Egenskab: skos:prefLabel
### Egenskab: skos:altLabel
### Egenskab: dct:description 


## Klassen cpov:PublicOrganisation 

<img src="img/PublicOrganisation.png" alt="offentlig organisation">
<dl class="def">
<dt>URI</dt>
<dd>http://data.europa.eu/m8g/PublicOrganisation </dd>
<dt>Foretrukken betegnelse (da)</dt>
<dd>offentlig organisation</dd>		
<dt>Anvendelsesnote (da) </dt>
<dd>Klassen repræsenterer offentlige organisationer bredt defineret. En organisation kan bestå af flere underorganisationer, og enhver organisation kan have én eller flere organisationsmæssige enheder. Hver af disse beskrives med de samme typer af egenskaber og relationer</dd>
<dt>Anvendelsesnote (en)</dt>
<dd>The Public Organization class represents the organization. One organization may comprise several sub-organizations and any organization may have one or more organizational units. Each of these is described using the same properties and relationships. </dd>
<dt>Underklasse af</dt>
<dd>http://www.w3.org/ns/org#Organization </dd>
<dt>Kravniveau</dt>
<dd>?</dd>
</dl>	 
Klassens egenskaber:	


## Klassen org:OrganizationalUnit

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

