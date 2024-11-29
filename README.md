# Metadata_specification

Knowledge Graph (KG) Metadata Specification and Validation

This project aims to create a specification for the description of knowledge graphs.

The KG specification spreadsheet and SHACL was developed.


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
        