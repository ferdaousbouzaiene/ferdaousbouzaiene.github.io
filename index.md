# 👋 Hi, I'm [Ferdaous] – full-time Data Scientist and part-time foodie 

I’m a data scientist passionate about building useful models, cleaning messy datasets, and turning insights into action. Whether it’s recommending your next favorite dish or analyzing product trends, I love connecting data to real-world problems.

I specialize in machine learning, data science, and storytelling.

---

## 🛠️ Skills Matrix

| Category             | Skills / Tools |
|----------------------|----------------|
| **Programming**      | Python, SQL, Git |
| **Machine Learning** | End-to-end ML workflows (data ingestion → feature engineering → training → evaluation → deployment), Ranking & Recommendation Systems, Price Prediction (projects), Feature Engineering |
| **LLMs & NLP**       | HuggingFace Transformers (BERT, T5, GPT), LangChain, Retrieval-Augmented Generation (RAG), Agentic Workflows, Prompt Engineering, Semantic Search (FAISS) |
| **Deep Learning**    | Transformers, Transfer Learning, CNNs, PyTorch, TensorFlow |
| **MLOps / LLMops**   | Google Cloud Platform (GCP), FastAPI, SQLAlchemy, Streamlit, CI/CD, Docker, Kubernetes (basics), Model/Version Tracking, Automated Evaluation (evals frameworks), Latency & Cost Monitoring |
| **Data Engineering** | PostgreSQL, SQLAlchemy, REST APIs, Data Pipelines, Containerized Services |
| **Visualization**    | Streamlit, matplotlib, seaborn, dashboards, storytelling with data |
| **Collaboration**    | Cross-functional teamwork with product & engineering, Code reviews, Best practices for reproducible ML |


---

## Projects

### 🍄🥾 [Spores & Outdoors](https://github.com/ferdaousbouzaiene/Spores-Outdoors)
[test it out 🍄🍀](https://spores-outdoors-iuuvvacjpqlqmg6ejunewm.streamlit.app/)


A playful **weather-based advisor** that tells you whether today is better for mushroom foraging or hiking. Powered by **OpenWeatherMap**, **PostgreSQL**, and **Streamlit**.

- Tools: Python, Streamlit, SQLAlchemy, PostgreSQL, pandas
- Highlights:
  - Real-time weather fetcher with OpenWeather API
  - Mushroom Foraging Score & Hiking Comfort Score (0–10)
  - PostgreSQL integration to log weather + user queries
  - Data science notebooks for EDA and modeling future predictions
  - Playful UI with custom fonts, blurred background image, and verdicts

---

### 🏋️ [AI-Powered Workout Recommendation System](https://github.com/ferdaousbouzaiene/gymcoachapp)
Built a comprehensive fitness recommendation system using ensemble machine learning models that generate personalized workout plans based on user preferences and goals.

- Tools: Python, scikit-learn, XGBoost, TensorFlow, pandas, matplotlib  
- Datasets: 3 integrated datasets (2,918 exercises, 973 user profiles, 248 calorie activities)  
- Highlights:
  - **Hybrid Recommendation Model**: collaborative + content-based filtering to predict top-rated exercises  
  - **Calorie Prediction Engine**: ensemble of Random Forest, XGBoost, and Gradient Boosting with metabolic features  
  - **Smart Workout Generator**: balanced plans by muscle groups, time constraints, and goals  
  - **Domain Knowledge Integration**: BMR calculations, MET values, exercise science principles  
  - **Interactive Jupyter Notebook**: full pipeline with visualizations and validation  

**Impact**: Delivers personalized workouts with 85%+ accuracy in preference prediction and calorie estimation within 15% error rate.  

---

### 🏋️ [What is this mushroom?](https://github.com/yves-rdlb/What-is-this-Mushroom/tree/master)
Safety-first **mushroom identification demo** using computer vision and API-first architecture. Predicts species from an image and maps to deterministic edibility with confidence gating.  

- **Frontend**: Streamlit app (API-only client)  
- **Backend**: FastAPI with Vision Transformer (ViT) model; legacy EfficientNet path  
- **Pipeline**: Image preprocessing → ViT classification (~169 species) → CSV-driven edibility lookup → safety gate (abstain below confidence threshold)  
- **Extra**: Optional heatmap visualization from species occurrence data  

**Impact:** Demonstrates **end-to-end ML engineering** (model serving, inference API, frontend integration, Dockerization, CI/testing). Shows awareness of **safety-critical UX** by abstaining on low confidence predictions.

---
### 🎬 [Show Recommendation System with LLMs](https://github.com/ferdaousbouzaiene/showrecommender)
Built a hybrid movie recommender combining traditional collaborative filtering with a GPT-powered semantic engine that generates personalized suggestions from movie metadata.

- Tools: Python, pandas, scikit-learn, OpenAI GPT-4, Streamlit
- Highlights:
  - Collaborative filtering (using user ratings)
  - Content-based similarity (based on genres, keywords)
  - LLM-generated movie suggestions: “If you liked X, try Y because...”
  - Interactive Streamlit app with natural language input

[More about project:](/projectrecommendation)

---

### 📚 [Agentellic](https://github.com/ferdaousbouzaiene/agentellic)
Implemented Retrieval-Augmented Generation (RAG) using LLMs to create a chatbot that answers questions from PDF documents.

- Tools: Python, pandas, scikit-learn, OpenAI GPT-4, Streamlit  
- Highlights:
  - Collaborative filtering from user ratings (matrix factorization)  
  - Content-based similarity with genres and keywords  
  - LLM-generated recommendations: “If you liked X, try Y because…”  
  - Streamlit app with natural language input for interactive querying  

**Impact**: Showcases how to blend classical ML with modern LLMs to create intuitive, explainable recommendations.  

---

### 📚 [PDF Q&A Chatbot with RAG](https://github.com/ferdaousbouzaiene/RagProject)
Implemented Retrieval-Augmented Generation (RAG) using LLMs to create a chatbot that answers questions from PDF documents.

- Tools: LangChain, OpenAI API, FAISS, Streamlit  
- Highlights:
  - Handles long PDFs and extracts relevant passages  
  - Explores different chunking strategies and embeddings  
  - Lightweight UI to demo retrieval performance  

**Impact**: Reinforces knowledge of vector search + RAG patterns, key skills for modern AI engineering.  

---

### 🍽️ [Restaurant Recommender System](https://github.com/ferdaousbouzaiene/restaurantrecommender)
Built a content-based recommendation system for restaurants using TF-IDF and cosine similarity on dish descriptions, cuisines, and customer reviews.

- Tools: Python, pandas, scikit-learn, Streamlit  
- Highlights:
  - TF-IDF vectorization + cosine similarity on menu data  
  - Interactive Streamlit app for filtering cuisines & locations  
  - Prototype for personalized dining suggestions  

**Impact**: Demonstrates classical NLP + recommender techniques applied to real-world consumer data.  

---

## Resumé (or CV?)

📄 [Download My Resume](resume.pdf)

## Contact

🔗 [GitHub](https://github.com/ferdaousbouzaiene)  
🔗 [LinkedIn](https://linkedin.com/in/ferdaousbouzaiene)  
📧 [ferdaous.bouzaiene@gmail.com](mailto:ferdaous.bouzaiene@gmail.com)
