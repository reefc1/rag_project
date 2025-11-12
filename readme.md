##Project Overview
This project was created during my Data Intelligence internship. The goal was to design and build an end-to-end AI system that uses Retrieval-Augmented Generation (RAG) and intelligent agents to answer questions and reason through real data.
The work combines data preprocessing, machine learning, and large language model integration into one pipeline. I focused on making the system practical, explainable, and easy to extend, bridging the gap between raw data and conversational AI.
#What the Project Does
In simple terms, this system allows a user to ask complex questions, and it:
Retrieves relevant information from stored documents using FAISS vector search
Understands the query through a large language model
Generates a structured and context-aware answer
I also explored CrewAI, which allows multiple AI agents (like a researcher, writer, and critic) to collaborate, improving reasoning and the overall quality of responses.

##How to Run the Project
Clone the repository
git clone https://github.com/reefc1/rag_project.git
cd rag_project
Create and activate a virtual environment
python -m venv rag_env
source rag_env/bin/activate   # For Mac
Install dependencies
pip install -r requirements.txt
Open the notebook
jupyter notebook
Then open Untitled.ipynb and run each cell step-by-step.
