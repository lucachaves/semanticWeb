<!-- # WEB SEMÂNTICA -->
title: #1 História
class: segue dark nobackground

---

title: Cenário
content_class: flexbox vcenter

[![linkeddata1](images/ws/Semantic-Web.jpg)](http://www.urenio.org/wp-content/uploads/2011/11/Semantic-Web.jpg)

---

title: Desafio
content_class: flexbox vcenter

[![linkeddata1](images/ws/linkeddata1.png)](https://www.youtube.com/watch?v=4x_xzT5eF5Q)

---

title: Desafio
content_class: flexbox vcenter

[![linkeddata1](images/ws/linkeddata2.png)](https://www.youtube.com/watch?v=4x_xzT5eF5Q)

---

title: Desafio
content_class: flexbox vcenter

<http://www.geonames.org/2950159/berlin.html>
[[rdf](http://sws.geonames.org/2950159/about.rdf)]

É IGUAL A

<http://en.wikipedia.org/wiki/Berlin>
[[rdf](http://dbpedia.org/page/Berlin)]

???????

---

title: Registros

* Tim Berners-Lee no [Ted](http://www.ted.com/speakers/tim_berners_lee): 
	* <http://www.ted.com/talks/tim_berners_lee_on_the_next_web>
	* <http://www.ted.com/talks/tim_berners_lee_the_year_open_data_went_worldwide>

* "Linked Data - The Story So Far":
	* <http://tomheath.com/papers/bizer-heath-berners-lee-ijswis-linked-data.pdf>

---

title: #2 Fundamentos
subtilte: Web Semântica, Linked Data
class: segue dark nobackground 

---

title: Web Semântica (WS)

Segundo o W3C a [WS](http://www.w3.org/standards/semanticweb/):

* Refere-se a visão da Web como dados ligados;
* Transforma a "Web of documents" para "Web of data";
* Sugere: "...develop systems that can support trusted interactions over the network.";
* Permite: "...people to create **data stores** on the Web, build **vocabularies**, and write **rules** for handling data.";
* Envolve tecnologias como: RDF, SPARQL, OWL, and SKOS.

---

title: Web Semântica (WS)

Para consilidar a WS o W3C idealizou:

* [Linked Data](http://www.w3.org/standards/semanticweb/data)
* Vocabulários ([Ontologia](http://www.w3.org/standards/semanticweb/ontology))
* Linguagem de consulta específica ([SPARQL](http://www.w3.org/standards/semanticweb/query))
* [Inferência](http://www.w3.org/standards/semanticweb/inference)
* Aplicações verticais
	* [Government Linked Data Working Group](http://www.w3.org/2011/gld/)
	* [Semantic Web Health Care and Life Sciences Interest Group](http://www.w3.org/2001/sw/hcls/)
	* [Outros casos de uso e estudo](http://www.w3.org/2001/sw/sweo/public/UseCases/)

---

title: Web Semântica (WS)
content_class: flexbox vcenter

[![linkeddata1](images/ws/ws-stack.png)](http://www.w3.org/2006/Talks/0718-aaai-tbl/#(14))

---

title: Linked Data (LD)

Segundo o [Bizier](http://linkeddatabook.com/editions/1.0/):

* Use URIs as names for things.
* Use HTTP URIs, so that people can look up those names.
* When someone looks up a URI, provide useful information, using the standards (RDF, SPARQL).
* Include links to other URIs, so that they can discover more things.

---

title: Linking Open Data Cloud
class: nobackground fill

* [LOD Cloud](http://lod-cloud.net/)
* [State of the LOD Cloud](http://lod-cloud.net/state/)

[![The Linking Open Data cloud diagram](images/ws/lod-cloud_colored-min.png)](http://lod-cloud.net/versions/2011-09-19/lod-cloud_colored.svg)

---

title: REPOSITÓRIOS

Exemplos:

* dbpedia - <http://wiki.dbpedia.org/>
* freebase - <http://www.freebase.com/>
* geonames - <http://www.geonames.org/>
* yago - <http://www.mpi-inf.mpg.de/yago-naga/yago/>
* dados.gov.br - <http://dados.gov.br/>
* dados.gov.uk - <http://data.gov.uk/>

Os repositórios podem ter essa [classificação](http://5stardata.info/).
---

title: Ontologia

Exemplos de vocabulários:

* RDF <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
* RDF Schema <http://www.w3.org/2000/01/rdf-schema#>
* OWL <http://www.w3.org/2002/07/owl#>
* DC <http://purl.org/dc/terms/>
* FOAF <http://xmlns.com/foaf/0.1/>
* e-Vog <http://vocab.e.gov.br/>

Repositório de vocabulários 

* LOV <http://lov.okfn.org/dataset/lov/> 
* DAML <http://www.daml.org/ontologies/keyword.html>
* Prefix <http://prefix.cc/popular/all>

Também existe a possibilidade de se criar ontologias;

---

title: Estrutura

Segundo [Gandon](http://www.slideshare.net/Culturadigital/an-introduction-to-semantic-web-and-linked-data):

* Os dados são representados através de Resource Description Framework (RDF);
* O RDF é um modelo de tripla onde tudo é representado por:

![image](images/ws/rdf-structure.png)
![image](images/ws/rdf-min.png)

* O RDF é também um modelo gráfico que liga descrição com recursos (URI).

---

title: Exemplos
content_class: flexbox vcenter

[![linkeddata1](images/ws/ze-wiki.png)](http://en.wikipedia.org/wiki/Z%C3%A9_Ramalho)

---

title: Exemplos

DBPedia <http://dbpedia.org/page/Z%C3%A9_Ramalho>:

(<span class="subject">Zé Ramalho</span>, <span class="predicate">instrument</span>, <span class="object">Singing</span>)

(<span class="subject">Zé Ramalho</span>, <span class="predicate">genre</span>, <span class="object">Pop music</span>)

(<span class="subject">Zé Ramalho</span>, <span class="predicate">hometown</span>, <span class="object">Brejo da Cruz</span>)

(<span class="subject">Zé Ramalho</span>, <span class="predicate">homepage</span>, <span class="object">http://www.zeramalho.com.br</span>)

(<span class="subject">Zé Ramalho</span>, <span class="predicate">sameAs</span>, <span class="object">http://yago-knowledge.org/resource/Z\u00E9_Ramalho</span>)

---

title: Exemplos
content_class: flexbox vcenter

![linkeddata1](images/ws/ze-graph2.png)

---

title: Exemplos
content_class: flexbox vcenter

![linkeddata2](images/ws/ze-graph1.png)

<http://yago-knowledge.org/resource/Z\u00E9_Ramalho> é recurso Zé Ramalho no Yago

---

title: Exemplos
content_class: flexbox vcenter

![linkeddata2](images/ws/ze-graph3.png)

---

title: Exemplos
content_class: flexbox vcenter

![linkeddata2](images/ws/ze-graph4.png)

---

title: Exemplos

1. Zé Ramalho

	* Resource 
		* [DBPedia](http://dbpedia.org/resource/Zé_Ramalho) ([HTML](http://dbpedia.org/page/Z%C3%A9_Ramalho) e [RDF](http://dbpedia.org/data/Z%C3%A9_Ramalho.rdf));
		* [Yago](http://yago-knowledge.org/resource/Zé_Ramalho) ([HTML](http://lod.openlinksw.com/describe/?uri=http://yago-knowledge.org/resource/Z%C3%A9_Ramalho) e [RDF](http://lod.openlinksw.com/sparql?query=define%20sql%3Adescribe-mode%20%22LOD%22%20%20DESCRIBE%20%3Chttp%3A%2F%2Fyago-knowledge.org%2Fresource%2FZ%C3%A9_Ramalho%3E&output=application%2Frdf%2Bxml));
	* Preview
		* [LOD Browser](http://browse.semanticweb.org/?uri=http%3A%2F%2Fdbpedia.org%2Fresource%2FZ%C3%A9_Ramalho&days=7) ([fluidops](http://iwb.fluidops.com/resource/?uri=http%3A%2F%2Fdbpedia.org%2Fresource%2FZ%C3%A9_Ramalho) e [Triplr](http://triplr.org/html/dbpedia.org/resource/Z%C3%A9_Ramalho));
		* VisualRDF - [Zé Ramalho DBPedia](http://graves.cl/visualRDF/?url=http%3A%2F%2Fdbpedia.org%2Fdata%2FZ%25C3%25A9_Ramalho.rdf)

2. Pesquisa

	* [RKBExplorer](http://www.rkbexplorer.com/):
		* <http://acm.rkbexplorer.com/browse/?uri=social+network+analysis&type=literal>
		* <http://acm.rkbexplorer.com/id/964776>

---

title: FORMATOS

Principais:

* RDF
	* RDF/XML 
	* JSON-LD 
	* Turtle 
	* Notation3 (n3)
	* N-Triples
* RDFa
* eRDF
* microformats
* microdata

---

title: SPARQL

* Linguagem de consulta para WS;
* Utilizada nos repositórios através dos SPARQL endpoint: 
	* DBpedia <http://dbpedia.org/sparql>;
	* Freebase <http://www.freebase.com/query>.
* Lista de SPARQL endpoint:
	* <http://datahub.io/>;
	* <http://www.w3.org/wiki/SparqlEndpoints>;
* Geralmente o Frontend dos SPARQL endpoint utiliza [Pubby](http://wifo5-03.informatik.uni-mannheim.de/pubby/);

<!-- http://sparqles.okfn.org/ -->

---

title: SPARQL

Exemplo 1 - capitais da Europa:

	SELECT * WHERE {
		?subject rdf:type <http://dbpedia.org/class/yago/CapitalsInEurope>.
		?subject rdfs:label ?label.
		?subject rdfs:comment ?abstract.
		FILTER (lang(?label) = "en" && lang(?abstract) = "en")
	} LIMIT 20

[Resultado](http://dbpedia.org/sparql?default-graph-uri=http%3A%2F%2Fdbpedia.org&query=SELECT+*+WHERE+%7B%0D%0A%09%09%3Fsubject+rdf%3Atype+%3Chttp%3A%2F%2Fdbpedia.org%2Fclass%2Fyago%2FCapitalsInEurope%3E.%0D%0A%09%09%3Fsubject+rdfs%3Alabel+%3Flabel.%0D%0A%09%09%3Fsubject+rdfs%3Acomment+%3Fabstract.%0D%0A%09%09FILTER+%28lang%28%3Flabel%29+%3D+%22en%22+%26%26+lang%28%3Fabstract%29+%3D+%22en%22%29%0D%0A%09%7D+LIMIT+20&format=text%2Fhtml&timeout=30000&debug=on)

---

title: SPARQL

Exemplo 2 - estados brasileiros:

	PREFIX foaf:  <http://xmlns.com/foaf/0.1/>
	PREFIX dbpedia-owl: <http://dbpedia.org/ontology/>
	PREFIX dbpprop: <http://dbpedia.org/property/>
	SELECT ?label
	WHERE {
		?state rdfs:label ?label .
		?state dbpedia-owl:type <http://dbpedia.org/resource/States_of_Brazil> .
		FILTER (lang(?label) = 'en')
	} ORDER BY ?label
	limit 1000

[Resultado](http://dbpedia.org/sparql?default-graph-uri=http%3A%2F%2Fdbpedia.org&query=PREFIX+foaf%3A++%3Chttp%3A%2F%2Fxmlns.com%2Ffoaf%2F0.1%2F%3E%0D%0A%09PREFIX+dbpedia-owl%3A+%3Chttp%3A%2F%2Fdbpedia.org%2Fontology%2F%3E%0D%0A%09PREFIX+dbpprop%3A+%3Chttp%3A%2F%2Fdbpedia.org%2Fproperty%2F%3E%0D%0A%09SELECT+%3Flabel%0D%0A%09WHERE+%7B%0D%0A%09%09%3Fstate+rdfs%3Alabel+%3Flabel+.%0D%0A%09%09%3Fstate+dbpedia-owl%3Atype+%3Chttp%3A%2F%2Fdbpedia.org%2Fresource%2FStates_of_Brazil%3E+.%0D%0A%09%09FILTER+%28lang%28%3Flabel%29+%3D+%27en%27%29%0D%0A%09%7D+ORDER+BY+%3Flabel%0D%0A%09limit+1000&format=text%2Fhtml&timeout=30000&debug=on)
	
---

title: #3 Referências
class: segue dark nobackground 

---

title: Referências

* Curso/Tutorial
	* <http://www.w3c.br/cursos/dados-abertos/banco.htm>
	* <http://www.slideshare.net/fabien_gandon/w3c-tutorial-on-semantic-web-and-linked-data-at-www-2013>
	* <http://www.inf.ufsc.br/~ronaldo/ine5454/LinkedData.pdf>
	* <http://www.urenio.org/2011/11/17/semantic-web-for-smart-cities/>

* Book
	* <http://www.w3.org/wiki/SwBooks>
	* <http://linkeddatabook.com/editions/1.0/>
	* <http://wifo5-03.informatik.uni-mannheim.de/bizer/pub/LinkedDataTutorial/>

---

title: Referências


* Vídeo
	* <https://www.youtube.com/watch?v=4x_xzT5eF5Q>
	* <https://www.youtube.com/watch?v=vioCbTo3C-4>

* Artigos

---

title: Referências

* Ferramentas
	* [LOD2](http://stack.lod2.eu/blog/) e [LMF](https://code.google.com/p/lmf/);
	* LOD Browser: [Visinav], [Marbles], [Disco], [Triplr](http://triplr.org/);
	* Link: [Silk](https://www.assembla.com/spaces/silk/wiki/Home), [Limes](http://aksw.org/Projects/LIMES.html), [RDFai](https://code.google.com/p/rdfai/), [Serimi](https://github.com/samuraraujo/SERIMI-RDF-Interlinking);
	* Graph RDF: [Graves](http://graves.cl/visualRDF/);
	* Extração de RDF: [UriBurner](http://linkeddata.uriburner.com/);
	* Triple store: [Sesame](http://www.openrdf.org/ ), [Apache Marmotta](http://marmotta.incubator.apache.org/), [Openlink Virtuoso](http://virtuoso.openlinksw.com/);
	* Ontologia: [Protégé](http://protege.stanford.edu/);
	* API: [Alignment API](http://alignapi.gforge.inria.fr/), [OWL API](http://owlapi.sourceforge.net/), [Jena API](http://jena.apache.org/), [OpenRDF](http://www.openrdf.org/);
	* String Match: [Stringmetrics](http://rockymadden.com/stringmetric/) e [Simmetrics](https://github.com/Simmetrics/simmetrics);

---

title: Referências

* Apresentações
	* <http://www.w3.org/2006/Talks/0718-aaai-tbl/#(1)>
	* <http://www.w3.org/2007/11/Talks/y2013.html>
	* <http://www.w3.org/2014/Talks/0123_phila_lata/>
	* <http://www.slideshare.net/Yasodara/web-semntica-uma-introduo>
	* <http://www.w3.org/2013/Talks/1016_phila_ldpoint/>
	* <http://www.w3.org/2014/Talks/0220_phila_lod2014/>
	* <http://www.w3c.es/Presentaciones/2013/0514-openData_WSIS-MA/0514-openData_WSIS-MA.pdf>