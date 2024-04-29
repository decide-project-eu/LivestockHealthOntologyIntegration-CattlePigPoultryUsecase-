# LivestockHealthOntologyIntegration-CattlePigPoultryUsecase-
For demonstration purposes, a Python notebook with a small dataset of labs has been uploaded here. It provides a detailed guide to integrating and analyzing poultry, pig, and cattle health data while adhering to FAIR principles.

The notebook titled "PigPoultryCattleUsecase.ipynb" is a comprehensive guide to integrating and analyzing livestock health data for poultry, pig, and cattle, while adhering to FAIR principles and utilizing ontologies and RDF (Resource Description Framework).

It begans with step by step approach is shown below as shown below:
![Figure 1: Ontology-Driven Knowledge-based Farm Animal Data Management (ODKFADM)](https://github.com/decide-project-eu/LivestockHealthOntologyIntegration-CattlePigPoultryUsecase-/assets/126476000/39035ac5-9406-4ba3-b305-05bde51a2d7e)


In step 1 it acquiring data, covering various sources such as laboratory records, veterinary reports, and sensor data. The data acquisition process ensures that the data is Findable and Accessible by providing clear documentation on its sources and formats.

Next, the notebook focuses on transforming the acquired data into RDF format, which enables interoperability and enhances data Reusability. This process involves mapping the data to a predefined ontology (available in the "ontology" folder), ensuring that it is Interoperable across different datasets and systems.the general view of ontology is shown below.

![image](https://github.com/decide-project-eu/LivestockHealthOntologyIntegration-CattlePigPoultryUsecase-/assets/126476000/a172c45e-449f-4f3e-83c5-a90414b8db4c)



Once the data is converted into RDF, the notebook constructs a knowledge graph, representing the relationships between different entities such as samples, diseases, pathogen, and locations. This knowledge graph facilitates advanced querying and analysis, allowing users to extract valuable insights from the integrated data.

The notebook also provides a set of SPARQL queries in step 5 tailored for poultry, pig, and cattle use cases. These queries enable users to retrieve specific information from the knowledge graph, and hows a comprehensive view of livestock health data in a multi-layered structure as shown below

![Query](https://github.com/decide-project-eu/LivestockHealthOntologyIntegration-CattlePigPoultryUsecase-/assets/126476000/0ed960e3-d393-49bd-8acb-2b3072f0763c)


Furthermore, Tableau is used to create visualisation tools for each species. It's worth noting that the tool was initially implemented successfully for cattle case and then replicated for other species. 

Throughout the notebook, best practices for FAIR data management are emphasized, ensuring that the integrated data remains Findable, Accessible, Interoperable, and Reusable. Additionally, the use of ontologies and RDF enhances the Semantic richness of the data, enabling more advanced analysis and integration with other datasets in the future.
