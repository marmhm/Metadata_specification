# Metadata_specification

Knowledge Graph (KG) Metadata Specification and Validation

This project aims to create a specification for the description of knowledge graphs.

The KG specification spreadsheet and SHACL was developed.
Link to [community spreadsheet](https://docs.google.com/spreadsheets/d/1g6ypMzaRt6Z6rhNu4MMwgVdFJO0W47astvhXcxx66N4/edit?gid=0#gid=0)

# setup the environment
prepare the local environment
        
        python -m venv .venv

activate the local environment
        
        source .venv/bin/activate

install the python packages

        python -m pip install -r requirements.txt

# run the test
run the shape validation with kg metadata and the KG shacl specification.

        python validate.py -i wikidata.ttl -s kg-full.shacl.ttl

# demonstration 

We aim to publish Food-Claims-KG, an RDF KG for food health claims. First, we use the proposed specification to create a metadata file in Turtle format using Schema.org vocabularies. Then, we run the specification and validate its conformance to the standard. If any violations occur, we fix them. Finally, we add an index.html file with structured metadata and upload it to the project's GitHub repository. 
        