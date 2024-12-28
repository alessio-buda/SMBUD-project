# SMBUD-project

# Bibliographic Database for Scientific Publications

This repository showcases a university project focused on creating a bibliographic database for managing and querying large-scale datasets of scientific publications. The project was completed as part of the **Systems and Methods for Big and Unstructured Data (SMBUD)** course.

## Project Overview

The project involves the design and implementation of a bibliographic database to store and analyze metadata related to scientific publications, such as:

- Titles, authors, and affiliations.
- Publishing venues (journals, conferences, books).
- Unique identifiers like DOI and ORCID.
- Relationships between articles, such as citations and references.

Key deliverables include:

- An Entity-Relationship (ER) model for data design.
- A graph-based implementation using Neo4j.
- Python scripts for data import, preprocessing, and querying.
- Documentation and analysis of the project's outcomes.

## Repository Structure

- **/reports**: Comprehensive documentation of the project, including ER diagrams, query examples, and analysis.
- **/examples**: Python scripts for interacting with the database, such as importing data and running queries.
- **/resources**: References and links to external tools and datasets used.

## Features

### Data Design

- **ER Model**: Defines the entities (e.g., articles, authors) and their interrelationships.
- **Graph Schema**: Implements the ER model in a graph database, enabling complex and efficient queries.

### Data Queries

The project demonstrates advanced querying capabilities using Neo4j's Cypher language. Examples include:

- Retrieving all articles authored by a specific individual.
- Finding the shortest path between two articles.
- Aggregating publication data by venue or author.

### Python Integration

Python scripts support the database operations, including:

- Importing bibliographic data from XML sources.
- Executing Cypher queries to extract insights.
- Analyzing relationships and metadata.

## Getting Started

### Prerequisites

- **Neo4j Database**: Install and configure a local or cloud-based Neo4j instance.
- **Python**: Use the provided scripts for database interaction.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bibliographic-database.git
   ```
2. Review the reports in `/reports` to understand the project architecture and methodology.
3. Use the Python scripts in `/examples` to set up the database and run queries.

## References

- [DBLP XML Dumps](https://dblp.uni-trier.de/xml/)
- [DOI System](https://www.doi.org/)
- [ORCID](https://orcid.org/)

## Contact

For any queries or suggestions, feel free to contact:

- **Author**: Alessio Buda
- **Instructor**: Marco Brambilla ([marco.brambilla@polimi.it](mailto:marco.brambilla@polimi.it))
