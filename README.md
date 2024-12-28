# SMBUD-project

This repository showcases a university project focused on creating a bibliographic database for managing and querying large-scale datasets of scientific publications. The project was completed as part of the **Systems and Methods for Big and Unstructured Data (SMBUD)** course held at Politecnico di Milano by Prof. Marco Brambilla (academic year 2022-23).

## Project Overview

The project involves the design and implementation of a bibliographic database to store and analyze metadata related to scientific publications, such as:

- Titles, authors, and affiliations.
- Publishing venues (journals, conferences, books).
- Unique identifiers like DOI and ORCID.
- Relationships between articles, such as citations and references.

Deliverables include:

### First Delivery

- An Entity-Relationship (ER) model for data design.
- A graph-based implementation using Neo4j.

### Second Delivery

- A document-based implementation using MongoDB.

### Third Delivery

- Query examples using Apache Spark.
- Minor fixes to previous deliveries

**NOTE**: Python scripts for data import, preprocessing, and querying can be found in the report pdf files.

## Repository Structure

- **/Deliveables**: Comprehensive documentation of the project, including ER diagrams, query examples, and analysis.

## Features

### Data Design

- **ER Model**: Defines the entities (e.g., articles, authors) and their interrelationships.
- **Graph Schema**: Implements the ER model in a graph database, enabling complex and efficient queries.
- **Document Model**: A MongoDB implementation for storing and querying hierarchical and unstructured data.

## Data Queries

The project showcases advanced querying capabilities using:

- **Cypher (Neo4j)**: Graph-based queries for analyzing relationships and shortest paths.
- **MongoDB Aggregation Framework**: Queries to extract insights from document-based data.
- **Apache Spark**: Distributed data processing for large-scale computations, including advanced filtering, transformations, and aggregations.

Example queries include:

- Retrieving all articles authored by a specific individual.
- Finding the shortest path between two articles using Neo4j.
- Aggregating publication data by author or venue in MongoDB.
- Performing keyword-based searches and complex joins using Spark.

## Getting Started

### Prerequisites

- **Neo4j Database**: Install and configure a local or cloud-based Neo4j instance.
- **MongoDB**: Install MongoDB for document-based storage and querying.
- **Apache Spark**: Set up Spark for distributed data processing.
- **Python**: Use the provided scripts for database interaction.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bibliographic-database.git
   ```
2. Review the reports in `/Deliverables` to understand the project architecture and methodology.

## References

- [DBLP XML Dumps](https://dblp.uni-trier.de/xml/)
- [DOI System](https://www.doi.org/)
- [ORCID](https://orcid.org/)

## Authors

- Alessio Buda
- Leonardo Cesani
- Fausto Lasca
- Gabriele Munafo'
- Matteo Paraboschi
