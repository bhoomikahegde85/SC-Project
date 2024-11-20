# Knowledge Graph Creation and Querying

This repository contains a Jupyter Notebook that demonstrates the process of creating, managing, and querying a Knowledge Graph using Python.

## Features

- **Library Installation**: Automatically installs required libraries like `rdflib`, `datasets`, and `sentence-transformers`.
- **Knowledge Graph Construction**: Builds a Knowledge Graph using `rdflib` with RDF, RDFS, and SPARQL support.
- **SPARQL Queries**: Includes examples of how to interact with the Knowledge Graph using SPARQL queries.
- **Data Integration**: Utilizes `pandas` for preprocessing and handling data inputs.

## Dependencies

Ensure you have Python installed. The following libraries are required:

- `rdflib`
- `datasets`
- `pandas`
- `sentence-transformers`

## Installation

You can install the necessary dependencies using the commands provided in the notebook:

```bash
!pip install rdflib
!pip install datasets
!pip install sentence-transformers
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

## Future Enhancements

- Expand to integrate additional data sources.
- Implement advanced querying and visualization techniques.
- Utilize machine learning models for semantic enrichment.

## License

This project is open-source and available under the MIT License.
