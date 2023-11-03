Welcome to the skincare recommendation engine. To experience what the application does, 
follow the instructions in this file.

The zip GROUP_4.zip contains the following files:
- skincare_ontology.ttl
- productont.ttl
- schemaont.ttl
- Skincare_Recommendation_Engine.ipynb
- Visualization.ipynb
- Skincare_Recommendation_Engine.pdf

The first thing you must do before running the application is save the zip and extract all of its file.
Once you've done this, please open GraphDB on your PC and create a new repository called KD-Project. The ruleset
when creating this repository has to be set to OWL-Max (Optimized).
After creating the repository, go to Import in the GraphDB menu and select RDF. Click on Upload RDF files, upload
the file skincare_ontology.ttl and import its data to the repository (if a second confirmation is asked when clicking on import,
just click on import again in the pop-up).

When you have completed the previous steps, you can open the Skincare_Recommendation_Engine.ipynb file. This file contains the application
and gives you further instructions on how to run the cells. The file can be opened by opening the file's directory in jupyter lab 
can be done through your command prompt or IDE). 
In addition, after running Skincare_Recommendation_Engine.ipynb completely,
you may want to take a look at Visualization.ipynb. This is a file which contains ways in which information provided by the application
could be visualized (if it were to be a web-page) to create a more attractive and clearer output. Instructions on how to run the cells
can once again be found in this file.

For further inspection of the skincare ontology, you can open skincare_ontoloy.ttl in Protege. As the ontology uses two imports
you will be asked for an import from schema and an import from the product vocabulary. When you are asked whether you want to locate these
files yourself, click yes and select schemaont.ttl when asked for the schema ontology and productont.ttl for the product ontology.

All information about how the application was created, its purpose, used ontologies and datasets, meaningful inferences, etc. can be
found in the file Skincare_Recommendation_Engine.pdf.




