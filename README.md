# Relational Knowledge graph for question answering on relational databases

This repository contains a Jupyter Notebook that demonstrates the process of creating, managing, and querying a Relational Knowledge graph for question answering on relational databases .

## Features

- **Library Installation**: Automatically installs all the required libraries.
- **SPARQL Queries**: Includes examples of how to interact with the Knowledge Graph using SPARQL queries.
- **Data Integration**: Utilizes `pandas` for preprocessing and handling data inputs.

## Dependencies

Ensure you have Python installed. The following libraries are required:

- `rdflib`
- `datasets`
- `pandas`
- `sentence-transformers`
- `torch`
- `elasticsearch`
- `datasets`
- `pandas tqdm fastapi pydantic chromadb huggingface_hub`
- `bitsandbytes`
- `SPARQLWrapper`
- `rdflib-sqlalchemy`
- `networkx pyvis`

## Installation

You can install the necessary dependencies using the commands provided in the notebook:

```bash
!pip install rdflib
!pip install datasets
!pip install transformers
!pip install torch
!pip install elasticsearch
!pip install datasets
!pip install pandas tqdm fastapi pydantic chromadb huggingface_hub
!pip install bitsandbytes
!pip install SPARQLWrapper
!pip install rdflib-sqlalchemy
!pip install networkx pyvis
```

## How to Use

1. **Setup**: Open the notebook file in Jupyter or any compatible IDE.
2. **Run the Cells**: Execute the cells sequentially to:
   - Install dependencies.
   - Construct the Knowledge Graph.
   - Query the graph using SPARQL.
3. **Modify**: You can adapt the code to integrate your own datasets and explore Knowledge Graphs for different use cases.

## File Overview

- **Notebook**: Contains the complete workflow for Knowledge Graph setup and interaction.

## License

This project is open-source and available under the MIT License.
