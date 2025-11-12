# Project Overview

This project was created during my Data Intelligence internship. The goal was to design and build an end-to-end AI system that uses Retrieval-Augmented Generation (RAG) and intelligent agents to answer questions and reason through real data.

The work combines data preprocessing, machine learning, and large language model integration into one pipeline. I focused on making the system practical, explainable, and easy to extend, bridging the gap between raw data and conversational AI.

---

## What the Project Does

This system allows a user to ask complex questions, and it:

1. Retrieves relevant information from stored documents using FAISS vector search  
2. Understands the query through a large language model  
3. Generates a structured and context-aware answer  

I also explored CrewAI, which allows multiple AI agents (like a researcher, writer, and critic) to collaborate, improving reasoning and the overall quality of responses.



## How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/reefc1/rag_project.git
   cd rag_project
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv rag_env
   source rag_env/bin/activate   # For Mac
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Open the notebook**
   ```bash
   jupyter notebook
   ```
   Then open `Untitled.ipynb` and run each cell step-by-step.

---



