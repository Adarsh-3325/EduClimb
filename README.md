# 🚀 EduClimb — Personalized Learning Path Generator

EduClimb is an intelligent system that generates **personalized learning roadmaps** based on a user’s current skills and target goals. It combines **graph-based algorithms** with **semantic understanding using BERT embeddings** to recommend the most efficient path for skill development.

---

## 📌 Overview

Most learners struggle with *what to learn next*. EduClimb solves this by:

* Analyzing current skills
* Identifying missing skills (skill gap analysis)
* Respecting prerequisite dependencies
* Recommending a structured learning path
* Suggesting relevant learning resources

---

## 🧠 Key Features

* 🔍 **Skill Extraction (NLP-based)**
  Extracts skills from user input (text/resume) using BERT-based embeddings.

* 📊 **Skill Gap Analysis**
  Compares user skills with required skills for a target role.

* 🔗 **Graph-Based Learning Path**
  Models skills as a Directed Acyclic Graph (DAG) and generates a valid sequence using topological sorting.

* 🎯 **Personalized Recommendations**
  Uses cosine similarity on embeddings to match users with relevant learning resources.

* 🌐 **Interactive UI**
  Built with Streamlit for easy user interaction.

---

## ⚙️ Tech Stack

* **Programming Language:** Python
* **ML / NLP:**

  * BERT (via Sentence Transformers)
  * Cosine Similarity
* **Core Logic:**

  * Graph (DAG)
  * Topological Sorting
* **Libraries:**

  * scikit-learn
  * pandas
  * sentence-transformers
* **Frontend:** Streamlit

---

## 🏗️ System Architecture

User Input (Skills / Resume / Goal)
↓
BERT → Skill Extraction + Embeddings
↓
Skill Gap Analysis (Set Operations)
↓
Graph Construction (Skill Dependencies)
↓
Topological Sorting
↓
Recommendation Engine (Cosine Similarity)
↓
📈 Personalized Learning Path Output


## 🚀 Future Improvements

* Resume upload → automatic skill extraction
* Time estimation for each learning step
* Adaptive learning based on user progress
* Integration with real course APIs (Coursera, Udemy)
* Knowledge graph expansion

---

## 🎯 Why EduClimb?

Unlike traditional recommendation systems, EduClimb:

* Respects **skill dependencies**
* Provides **structured learning paths**, not just suggestions
* Uses **semantic intelligence (BERT)** for better matching
* Focuses on **real-world usability**


---
