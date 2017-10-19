# NHC-Ontology

The NHC-Ontology (Natural History Collections Ontology) is an application ontology that extends the Darwin-SW, an ontology to describe present-day biodiversity information, and serves to structure the entities in the content of natural history collections through semantic annotation. It connects to digitized manuscript scans with the Web Annotation Data Model<sup>1</sup>.

On a collection and item level, we use the following standards to describe natural history collections: Natural Collection Description (NCD) from TDWG for describing collections and the Dublin Core for items. For the content, we integrate the Darwin Core and Darwin-SW for describing Biodiversity, and some classes taken from NCIT, Uberon and Geonames. See figure 1 for a graphical representation of the model. 

In this repository you can find the application ontology. The code of the Semantic Field Book Annotator for crowd-sourcing semantic annotations from Field Books using this ontology can be found in the following GIT Repository: https://github.com/lisestork/SFB-Annotator. A README file is in progress. 

<sup>1</sup>The Web Annotation Model [Link](https://www.w3.org/TR/annotation-model/).

Figure 1: The NHC-Ontology
![alt text](https://github.com/lisestork/NHC-Ontology/blob/master/Images/OccurrenceModel.png)

Figure 2: Example queries (tested) to be used to query the SPARQL endpoint (http://makingsense.liacs.nl/rdf4j-server/repositories/NC) through a SPARQL query editor such as: http://yasgui.org/. Example queries can be found in the following document: https://github.com/lisestork/NHC-Ontology/blob/master/Example_Queries.txt !!
![alt text](https://github.com/lisestork/NHC-Ontology/blob/master/Images/Example_Queries_SPARQLEndpoint.png)

Figure 3: Example occurrence record annotated with the NHC-Ontology. 
![alt text](https://github.com/lisestork/NHC-Ontology/blob/master/Images/example_occurrence.png)

Figure 3 shows one fully linked observation record that was produced in compliance with three biology and history of science researchers. Orange nodes indicate IRIs and thus instances of classes from the ontology. Purple nodes also indicate IRIs but from different data providers. The IRI viaf:45106482 for instance refers to "Heinrich Kuhl", a german naturalist and zoologist and the writer of this field book. The IRI is an instance of the foaf:Person class. Further, purple nodes connect to the Uberon Ontology and the NCI Thesaurus and finally, green nodes indicate labels connected to the IRIs with the rdfs:label property. 

Figure 4: Example of an annotation that connects to the NHC-Ontology. 
![alt text](https://github.com/lisestork/NHC-Ontology/blob/master/Images/AnnotationExample.png)

Finally, figure 5 shows an example of an annotated page. 

Figure 4: Example of an annotated page. 
![alt text](https://github.com/lisestork/NHC-Ontology/blob/master/Images/AnnotationExample.png)
