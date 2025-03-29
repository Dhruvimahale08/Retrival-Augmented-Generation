# Retrival-Augmented-Generation
# EduQuest NCERT Assistant

[![Project Banner](https://img.shields.io/badge/EduQuest-AI%20Learning%20Assistant-blue)](https://your-project-link.com)
![Python Version](https://img.shields.io/badge/Python-3.10%2B-brightgreen)

An intelligent AI-powered assistant for NCERT textbook queries, combining document retrieval with large language model capabilities.



## 📚 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Installation Guide](#-installation-guide)
- [System Architecture](#-system-architecture)
- [Usage Instructions](#-usage-instructions)
- [Configuration](#-configuration)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [Contact](#-contact)

## 🌐 Project Overview
EduQuest is an AI-powered learning assistant that helps students quickly find answers in NCERT textbooks using natural language queries. The system combines:

- **Document Understanding**: PDF text extraction and processing
- **Semantic Search**: FAISS-based vector similarity search
- **AI Generation**: Mistral-7B language model for answer formulation
- **Secure Access**: User authentication and session management

## 🚀 Key Features
- **Instant Textbook Answers**
- **Multi-Subject Support** (Physics, Chemistry, Biology)
- **PDF Upload & Processing**
- **Context-Aware Responses**
- **Answer Confidence Scoring**
- **User Authentication System**
- **Cross-Chapter Search**
- **Responsive Web Interface**

## 🛠 Technology Stack

### Core Components
| Component | Technology | Purpose |
|-----------|------------|---------|
| Text Embedding | Sentence Transformers (all-mpnet-base-v2) | Text vectorization |
| Vector Database | FAISS (Facebook AI Similarity Search) | Efficient similarity search |
| Language Model | Mistral-7B-Instruct-v0.1 | Answer generation |
| PDF Processing | PyMuPDF | Text extraction |
| Web Interface | Gradio | UI framework |
| Authentication | Bcrypt | Password hashing |

### Supporting Infrastructure
- **Pandas**: User database management
- **NumPy**: Numerical operations
- **scikit-learn**: Similarity calculations
- **PyTorch**: Model inference


