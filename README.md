# NHC-Ontology

The NHC-Ontology (Natural History Collections Ontology) is an extension of the Darwin-SW ontology used to semantically describe present-day biodiversity data. The NHC-Ontology is an application ontology that extends the Darwin-SW and serves to structure the entities in natural history collections through semantic annotation. It connects to digitized manuscript scans with the Web Annotation Data Model<sup>1</sup>.

In the application ontology you can find the following ontologies: Natural Collection Description (NCD) from TDWG for describing collections, the Dublin Core for items, Darwin Core for describing Biodiversity, Darwin-SW and some classes taken from NCIT, Uberon and Geonames. See figure 1 for a graphical representation of the model. 

<sup>1</sup>The Web Annotation Model [Link](https://www.w3.org/TR/annotation-model/).

Figure 1: The NHC-Ontology
![alt text](https://github.com/lisestork/NHC-Ontology/blob/master/Images/OccurrenceModel.png)

Figure 2: Example occurrence record annotated with the NHC-Ontology. 
![alt text](https://github.com/lisestork/NHC-Ontology/blob/master/Images/example_occurrence.png)

Figure 1 shows one fully linked observation record that was produced in compliance with all three researchers. Orange nodes indicate IRIs and thus instances of classes from the ontology. Purple nodes also indicate IRIs but from different data providers. The IRI viaf:45106482 for instance refers to "Heinrich Kuhl", a german naturalist and zoologist and the writer of this field book. The IRI is an instance of the foaf:Person class. Further, purple nodes connect to the Uberon Ontology and the NCI Thesaurus and finally, green nodes indicate labels connected to the IRIs with the rdfs:label property. 

Figure 2: Example of an annotation that connects to the NHC-Ontology. 
![alt text](https://github.com/lisestork/NHC-Ontology/blob/master/Images/AnnotationExample.png)

