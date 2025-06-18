This repo is for all the notes and contents related to Data science and AL/ML/DL learnings
## Points of improvement in resume
Perfect — let's work on:

✅ Rewriting your CV tailored for AI/ML intern roles

✅ Writing GitHub project descriptions (for your top 3 projects)

✨ Step 1: Rewritten Resume Summary + Project Section (AI/ML Intern Focus)
You should place this immediately after your contact info on your resume:

🧠 Professional Summary
Aspiring AI/ML Engineer and dual-degree student at IIT Kharagpur with hands-on experience in large language models (LLaMA 3), deep learning, and NLP. Skilled in Python, PyTorch, TensorFlow, and graph databases like Neo4j. Built and deployed AI systems for intelligent itinerary generation, disease-symptom extraction from PubMed, and real-time fault detection. Actively ranked in national data science competitions. Seeking an ML/AI internship to apply and expand these skills in a research or product environment.

💼 Highlighted Projects
(These can replace the more generic bullet points you have currently)

🔍 Chat-Based Intelligent Tour Planning Assistant
LLM + Graph + Personalization | Nov 2024

Designed a graph-based user model in Neo4j to capture dynamic preferences, personas, and constraints.

Integrated LLaMA 3 (Meta) for NLP-driven preference extraction and itinerary personalization.

Combined graph traversal logic and LLM reasoning to create real-time adaptive tour plans.

Future Scope: Deploy on Streamlit with session memory to simulate chat history.
🧪 Technologies: LLaMA 3, Neo4j, Python, NetworkX, LangChain (optional)

🧬 Disease-Symptom Relationship Mining from PubMed
NLP + Biomedical AI | Jun–Jul 2024 (Ongoing)

Scraped and parsed 1.6M abstracts from MEDLINE using BeautifulSoup and PubMed API.

Built a custom NLP pipeline using NegEx, spaCy (clinical model), and Whoosh for indexing disease-symptom pairs.

Quantified and visualized relationship frequencies between 8,514 diseases and 842 symptoms.

Goal: Enable early-stage rare disease diagnosis using knowledge graphs.
🧪 Technologies: Python, spaCy, NegEx, PubMed, NLP, Pandas

🧠 Automated Manufacturing State Prediction (Gold Medal Project)
Time Series + DL + AutoML | Feb–Mar 2023

Predicted system state using LSTM + 1D CNN + AutoGluon, achieving 94% accuracy.

Performed real-time sensor fault detection using Z-score filtering and Kalman Filter smoothing.

Ranked top 1st out of all teams in IITKGP’s analytics championship.
🧪 Technologies: PyTorch, LSTM, CNN, AutoGluon, NumPy, Pandas

✅ Step 2: GitHub Project Descriptions
When you upload projects to GitHub, create a README.md with:

Template (for each project):
pgsql
Copy
Edit
# Project Name
Brief one-liner: What does this project do?

## 🚀 Overview
Short paragraph about the problem and your solution.

## 🔍 Features
- Feature 1 (e.g., Uses LLaMA 3 for NLP-based user preference extraction)
- Feature 2 (e.g., Graph-based user profiling via Neo4j)
- Feature 3 (e.g., Real-time itinerary generation based on graph + LLM output)

## 📊 Tech Stack
Python, LLaMA 3, Neo4j, spaCy, Pandas, etc.

## 🧠 Demo / Future Scope
- You can add a Streamlit demo or placeholder.
- Or note features you plan to add.

## 🤖 How to Run
Add setup instructions, e.g.,  
```bash
pip install -r requirements.txt
python app.py
📂 Files
notebook.ipynb: data exploration and modeling

graph.py: Neo4j integration

llm_integration.py: LLaMA 3 prompt logic

pgsql
Copy
Edit

Would you like me to generate **full GitHub README.md files** for all 3 projects with real examples and prompts for LLaMA or AutoGluon?




