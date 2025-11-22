# HealthData NLP Platform

> Developed during Infosys Virtual Internship Program

A sophisticated medical knowledge extraction and graph analytics platform that processes healthcare data using advanced NLP techniques. This project was developed as part of the Infosys Virtual Internship Program, demonstrating enterprise-level application development and AI integration.

## 🏆 Internship Project Highlights

- **Program**: Infosys Virtual Internship
- **Domain**: Healthcare Technology & AI
- **Technologies**: Python, Streamlit, NLP, Graph Databases
- **Focus**: Enterprise-grade medical data processing platform

## 🚀 Features

### Core Capabilities
- **Multi-Source Data Collection**: Wikipedia, ArXiv research papers, user text input, and file upload
- **Advanced NLP Processing**: Entity recognition, relationship extraction, and knowledge graph construction
- **Interactive Visualization**: Dynamic medical knowledge graphs and relationship mapping
- **Semantic Search**: Intelligent content discovery across documents and knowledge triples

### Enterprise Features
- **Role-based Access Control**: Admin and user roles with proper authentication
- **Cross-Domain Analysis**: Bridge entity identification between medical domains
- **Neo4j Integration**: Graph database export and persistence
- **Admin Dashboard**: Comprehensive system management and analytics
- **Usage Analytics**: Track user activity and platform performance

## 🛠 Technology Stack

| Category | Technologies |
|----------|-------------|
| **Frontend** | Streamlit, Plotly, NetworkX |
| **Backend** | Python, JWT Authentication |
| **NLP** | spaCy, Transformers, Sentence-BERT |
| **Database** | SQLite (users), Neo4j (knowledge graph) |
| **APIs** | Wikipedia API, ArXiv API |
| **Deployment** | Streamlit Cloud, Docker-ready |

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Neo4j Database (optional, for graph features)

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/healthdata-nlp-platform.git
cd healthdata-nlp-platform

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Download NLP model
python -m spacy download en_core_web_sm

# Run application
streamlit run HealthData_Knowmap.py
