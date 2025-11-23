# HealthData NLP Platform

> Developed during Infosys Virtual Internship Program

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-Enabled-red)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen)

A sophisticated medical knowledge extraction and graph analytics platform that processes healthcare data using advanced NLP techniques. This project was developed as part of the Infosys Virtual Internship Program, demonstrating enterprise-level application development and AI integration.

---

## Internship Project Highlights

- **Program**: Infosys Virtual Internship
- **Domain**: Healthcare Technology & AI
- **Technologies**: Python, Streamlit, NLP, Graph Databases

---

## Features

### Core Capabilities
- **Multi-Source Data Collection**: Wikipedia, ArXiv research papers, user input & file upload
- **Advanced NLP Processing**: Entity recognition, relationship extraction, triple generation
- **Interactive Graph Visualization**: Knowledge graph and relations
- **Semantic Search**: Triple-based intelligent search across nodes and relations

### Enterprise Features
- **Role-Based Authentication**: Admin & user roles with secure login
- **Cross-Domain Mapping**: Identify medical entity bridging across knowledge areas
- **Neo4j Integration**: Export, analyze, and persist medical graph data
- **Admin Dashboard**: Monitor users, logs, and analytics insights

---

## Technology Stack

| Category | Technologies |
|----------|-------------|
| **Frontend** | Streamlit |
| **Backend** | Python, JWT Authentication |
| **NLP** | spaCy, Transformers, Sentence-BERT |
| **Database** | SQLite (users), Neo4j (knowledge graph) |
| **APIs** | Wikipedia API, ArXiv API |
| **Deployment** | Streamlit Cloud, Docker-ready |

---

## Module Flow

| Module | Input | Output | Purpose |
|--------|------|--------|---------|
| Data Collection | Text / URLs / Files | Raw corpus | Acquire data from multiple sources |
| NLP Processing | Corpus | Entities + Relations | Extract medical knowledge |
| Knowledge Graph | Triples | Interactive graph | Visual + analytical insights |
| Semantic Search | Keywords | Relevant triples | Intelligent query answering |
| Admin Panel | Logs + usage | Statistics dashboard | Platform monitoring |

---

## Quick Start

### Prerequisites
- Python 3.8+
- Neo4j (optional - for graph storage)

### Installation
```bash
git clone https://github.com/yourusername/healthdata-nlp-platform.git
cd healthdata-nlp-platform

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

pip install -r requirements.txt
python -m spacy download en_core_web_sm

streamlit run HealthCare_KnowMap.py
```

### Default Login Credentials

**Username**: `admin`
**Password**: `admin123`

---

## UI Screenshots

### Login and Registration

<p align="center">
  <img src="output/Registration.png" width="600">
  <img src="output/Login.png" width="600">
</p>

### Main Dashboard

<p align="center">
  <img src="output/main_dashboard.png#gh-light-mode-only" width="600">
  <img src="output/main_dashboard.png#gh-dark-mode-only" width="600">
</p>

---

## Platform Modules

### 1️⃣ Data Collection
- Multiple source integration
- File upload capabilities  
- User text input processing
<p align="center">
  <img src="output/DataCollection.png" width="600">
  <img src="output/Dataretrival.png" width="600">
</p>

### 2️⃣ NLP Processing
- Medical entity recognition
- Relationship extraction
- Confidence scoring
<p align="center">
  <img src="output/Nlp__Analysis.png" width="600">
  <img src="output/NLP_Analysis.png" width="600">
</p>

### 3️⃣ Knowledge Graph
- Interactive visualization
- Cross-domain analysis
- Semantic search
<p align="center">
  <img src="output/KnowledgeGraph.png" width="600">
</p>

### 4️⃣ Admin Dashboard
- User management
- Usage analytics
- System monitoring
<p align="center">
  <img src="output/AdminDashboard.png" width="600">
</p>

### 5️⃣ Cross Domain
Identifies entities appearing in multiple medical domains.
- Locate connecting nodes across topic clusters
- Useful for multi-disciplinary disease research 
<p align="center">
  <img src="output/CrossDomain.png" width="600">
</p>

### 6️⃣ Semantic Search
Intelligent query engine over extracted knowledge.
- Search beyond text: Return related entity connections
- Retrieves relevant knowledge triples instantly
- Helps users find insights faster  
<p align="center">
  <img src="output/SemanticSearch.png" width="600">
</p>

### 7️⃣ Neo4j Integration
Enterprise-grade graph data management.
- Export triples to Neo4j graph database
- Run graph queries in Cypher for deep analytics
- Persist knowledge for long-term storage  
<p align="center">
  <img src="output/neo4jConnection.png" width="600">
  <img src="output/Neo4jExport.png" width="600">
  <img src="output/neo4jDash.png" width="600">
</p>

---

## License

This project is licensed under the MIT License – see the LICENSE file for details.

---

## Acknowledgments

* **Infosys** for the virtual internship platform
* **Mentors** for technical support & training
* **Open Source Community** for supporting tools and libraries


