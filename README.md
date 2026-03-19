# Data-Aware Conversational chatbot

I developed this project as a **Summer Project** to explore how nlp and currunt pre-trained model can be applied to scientific datasets.

This system is a conversational AI that answers natural language questions about internal research data. My goal was to make complex datasets easier to explore through simple, human-like interaction.

---

## 🎥 Demo Video

Below is a demonstration of the system showing how the frontend and backend interact, from user query to generated response.

[Watch the demo video](./video1350924448.mp4)

---

## 🔍 Overview

- The frontend is a web-based interface where users type their questions.
- The backend processes each query using NLP techniques, understands the intent, retrieves relevant data, and generates a response.
- The response is then sent back to the frontend and displayed to the user.

The demo video shows the full workflow from user input to AI-generated response.

---

## 🚀 Features

- **Web-Based UI**  
  I built a clean and simple interface using Flask and modern CSS.

- **Semantic Intent Recognition**  
  I use Sentence Transformers to understand meaning beyond simple keywords.

- **Data-Aware Entity Extraction**  
  I designed the system to learn the dataset structure at startup and build a knowledge graph to identify columns and values.

- **Stateful Conversation**  
  I implemented context tracking so the system can handle follow-up questions.

- **Advanced Biological Inference**  
  I integrated Hugging Face models via LangChain to answer complex scientific questions.

- **Dynamic Responses**  
  The system generates summaries, statistics, previews, and comparison tables.

---

## 🧠 Approach: Hybrid AI Architecture

I use a hybrid approach that combines multiple techniques:

### 1. Data-First Learning (Knowledge Graph)
- I analyze datasets at startup  
- I generate descriptions and synonyms for columns  
- I infer relationships across tables  

### 2. Intent Detection (Sentence Transformers)
- I convert user queries into vectors  
- I match them with predefined intents  

### 3. Entity Extraction (Rules + Heuristics)
- I use patterns and keywords to identify filters and groupings  
- This helps me build accurate data queries  

### 4. LLM-Based Reasoning (LangChain + Hugging Face)
- I first perform targeted data analysis  
- Then I send the results to an LLM for interpretation  

---

## 🧰 Technologies Used

- Flask  
- Pandas  
- SpaCy  
- Sentence Transformers  
- Hugging Face Hub  
- LangChain  

---

## 🔒 Note

The source code is not shared publicly. 

I’m happy to provide a detailed walkthrough of the system, including architecture, design choices, and technical challenges.

---