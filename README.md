# Neo4j Graph-Based Financial Fraud Detection

## Project Overview
Financial fraud is no longer limited to banks or high-net-worth individuals. It has spread to common users, with fraudsters creating fake UPI accounts and deceiving innocent people with fabricated stories. This project leverages Neo4j and Graph Data Science (GDS) to understand Banking and transaction data using Graph Queries and Algorithms in Neo4J. 

## Repository Contents
This repository contains all necessary files using Neo4j.

### Included Files:
1. **Dataset Overview Summary**
   - `Dataset_overview_summary.pdf`: Provides an explanation of the dataset used for fraud detection, including sources, schema, and key attributes.

2. **Graph Data Model and Architecture Diagrams**
   - `Graph_data_model.json`: JSON file representing the graph schema.
   - `Graph_data_model.png`: Image file illustrating the schema.

3. **Cypher Queries and GDS Code**
   - `Cypher_GDS_code.ipynb`: Contains Cypher queries used for detecting fraud patterns and scripts for implementing Neo4j Graph Data Science (GDS) algorithms.

4. **Presentation Slide Deck**
   - `Neo4J_Banking_Usecases.pdf`: presentation explaining the problem statement, solution approach, and outcomes.

5. **Demo Video**
   - [Watch the Demo Video](https://youtu.be/78lDCSg9AYY)

## Setup Instructions
### Prerequisites
- Install [Neo4j Desktop](https://neo4j.com/download/) or set up [Neo4j AuraDB](https://neo4j.com/cloud/aura/).
- Install Python 3.8+ (if using GDS with Python).
- Install necessary Python libraries: `pip install neo4j pandas`.

### Steps to Run
1. **Start Neo4j Database**
   - Import the dataset into Neo4j.
   - Use `Graph_data_model.json` to create the schema.

2. **Run Cypher Queries**
   - Execute queries from `Cypher_GDS_code.ipynb` to identify fraudulent activities and analyze the data.
   - Run the scripts to apply community detection, anomaly detection, and other graph algorithms.

3. **Review Results**
   - Visualize detected fraud patterns in Neo4j Browser.
   - Analyze outputs from the GDS notebook.

4. **Presentation & Demo**
   - Use `Neo4J_Banking_Usecases.pdf` for stakeholder presentations.
   - Watch the demo video.
