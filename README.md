This ontology is modeled based on the event markup schema of the project [The Lives and Afterlives of Material Infrastructures](https://www.infrastructurelives.eu/). The project is constructing a corpus of inscriptions, cataloging material infrastructures sourced from digitized gazetteers and annotating events linked to these infrastructures in the corpus, as a groundwork for further event-based historical analysis.  
  
This ontology graph shows how the properties in the annotated events relate to each other. Vocabularies integrated with the [CIDOC model](https://www.cidoc-crm.org/) where applicable are shown in blue text. 
  
- The “inscription” class connects “event” and the material “object” or its specific components. The metadata of the inscription source are described with data properties and the relationship with time/location/person classes.  
- Different types of actors related to the event and different types of events are described by object properties.
- Considering the condition that different parts of one same infrastructure may be impacted by different kinds of “events” each with a different time-span, the “object_part” class is set as a subclass of “object_main”. The descriptive information modeled as data properties for the “object_main” class are also applicable for its subclass, “object_part”.
- The lower part of the graph shows a demo of individual implementation of a specific piece of inscription. Some individuals are represented with their URIs on Wikidata.
  
Click to view the [ontology graph](https://raw.githack.com/lizaodawn/material_infrastructures_event_ontology/main/ontology_graph_update.html) in the browser. 
