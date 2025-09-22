![ASENC](https://github.com/user-attachments/assets/43426bb4-4482-4aff-b2b2-1002bb664215)
g)

# Final Agent Live Demo

This repository provides a **Colab-based demonstration notebook** showcasing how to build and run an **Agentic RAG (Retrieval-Augmented Generation) system** for toxicology and overdose management.  
The notebook has been cleaned (no outputs, no secrets) and is ready to run directly in Google Colab.

---

## 💡 Project Idea

Medical professionals often face challenges when dealing with **toxicology emergencies** such as overdoses of common drugs (e.g., salbutamol, ibuprofen, paracetamol). Accessing the right protocol quickly can be life-saving.

This project demonstrates how to build an **AI-powered agent** that:
- Retrieves **reliable toxicology protocols** from trusted sources (e.g., DailyMed, NHS, MedlinePlus).
- Uses **RAG (Retrieval-Augmented Generation)** to answer user questions about overdose management, drug interactions, and monitoring.
- Organizes responses with references so that medical staff can **validate information** before action.
- Runs inside a Colab notebook for easy experimentation and extension.

The aim is to show how **AI agents + domain knowledge** can support healthcare decision-making while keeping humans in the loop.

---

## 📘 What’s Inside
- **`Final_Agent_live_Demo_sat_clean.ipynb`**  
  A cleaned Colab notebook that walks through:
  - Setting up the environment  
  - Building the retrieval pipeline  
  - Creating search agents for medical websites  
  - Demonstrating Q&A for overdose and interaction queries  

- **`README.md`**  
  This file, describing the project.

---

## 🚀 Quick Start

Launch the notebook directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhmedAlhisan/AgenticRagToxicology/blob/main/Final_Agent_live_Demo_sat_clean.ipynb)

### Steps
1. Open the notebook in Colab via the badge above.  
2. Run the cells in sequence.  
3. Ask the agent toxicology-related questions (e.g., *“What is the management protocol for ibuprofen overdose in adults?”*).  

---

## ⚙️ Requirements

To run locally instead of Colab:

```bash
# Create a fresh environment
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# Install Jupyter and dependencies
pip install -r requirements.txt
