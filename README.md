# 📊 Northwind Graph Visualization — Retail & Supply Chain

This project visualizes the **Northwind Dataset** using **Neo4j Graph Database** as a case study in the retail & supply chain domain.  
The data is transformed into nodes and relationships to make entity connections more intuitive and interactive for analysis.

---

## 📝 Project Description

The Northwind dataset is a classic retail dataset that includes entities such as **Customer**, **Order**, **Product**, **Supplier**, **Employee**, **Shipper**, **Category**, **Region**, and **Territory**.

In this project, the dataset is:
- Imported into Neo4j
- Modeled as nodes and relationships using Cypher queries
- Visualized as graphs for analytical purposes, including:
  - Top suppliers by number of products  
  - Most active shippers  
  - Employee performance based on processed orders  
  - Customer distribution for best-selling products  

---

## 🛠️ Technologies Used

- 🧠 **Neo4j (Desktop / AuraDB)**  
- 📝 **Cypher Query Language (CQL)**  
- 🌐 **GitHub** for project hosting & documentation  
- 🗃️ **Northwind Dataset** as the primary data source (from the official Neo4j repository)

---

## 💡 Key Insights

- Graph Databases are highly suitable for **retail and supply chain** because they allow direct modeling of relationships between entities.  
- Nodes with high-degree connections represent strategic roles, such as best-selling products, top customers, or main shippers.  
- *Hub-and-spoke* graph visualization makes it easy to identify central entities (hubs) like key shippers or popular products.  
- These kinds of relationship insights are harder to achieve using only relational databases or plain SQL.

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   https://github.com/zaidanathallah/Desain-Basis-Data-Graf-untuk-Retail-Supply-Chain-Studi-Kasus-Dataset-Northwind-
Open Neo4j Desktop or AuraDB.

Create a new project / database instance.

Import the CSV dataset into the database's import/ folder.

Run DDL (constraints) followed by DML (LOAD CSV & relationships) queries.

Use Neo4j Browser or Bloom to visualize the graph.

📚 Data Source
The dataset used in this project comes from the official Neo4j Northwind examples:
👉 https://github.com/neo4j-graph-examples/northwind
📝 Conclusion
Graph Databases simplify the understanding of complex relationships within the retail and supply chain domain.
Through graph visualization, we can extract valuable insights about product popularity, supplier networks, shipping activity, and key customers — insights that are difficult to uncover from traditional relational tables.

👤 Author
Name: Zaidan Athallah

Field: Data Science / Data Analytics

Project: Northwind Graph Visualization using Neo4j

Year: 2025

🪪 License
The Northwind dataset is public and free to use for educational purposes.
This project is intended for learning and research activities.

