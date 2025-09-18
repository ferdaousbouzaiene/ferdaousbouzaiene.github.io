# 👋 Hey there! I'm [ferdaous] 
## 🧠 Full-time Data Whisperer ✨ • 🍕 Part-time Ramen Connoisseur 🍜 • 🤖 Occasional Nature Lover 🍀

Welcome to my digital playground where I turn messy datasets into meaningful stories, build recommendation engines that know you better than you know yourself, and occasionally teach machines to identify whether that mushroom will kill you or not! 🍄☠️

*Fair warning: I have a serious emoji addiction and an unhealthy obsession with making data dance* 💃📊


---

## 🛠️ Skills Matrix

| Category             | Skills & Secret Weapons |
|----------------------|-------------------------|
| **Programming**      | Python 🐍 (my spirit animal (not)), SQL 📊 (for when data needs therapy), Git 🔄 (time machine for code) |
| **Machine Learning** | End-to-end ML pipelines (from "uh oh" to "ta-da!"), Recommendation Systems 🎯 (digital cupid), Feature Engineering 🔧 (data plastic surgery) |
| **LLMs & NLP**       | Making robots talk like humans 🤖💬, RAG systems (teaching AI to Google properly), Prompt Engineering 🎭 (AI whispering) |
| **Deep Learning**    | Neural networks that actually work ⚡, Transfer Learning (because why reinvent the wheel?), PyTorch & TensorFlow (my computational paintbrushes) |
| **Data Visualization** | Turning boring spreadsheets into stories 📈✨, Streamlit apps that don't break (usually), Making data pretty enough to frame |



---

## Projects

### 🍄🥾 Spores & Outdoors
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://spores-outdoors-iuuvvacjpqlqmg6ejunewm.streamlit.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black)](https://github.com/ferdaousbouzaiene/Spores-Outdoors)

*Because sometimes you need an AI to tell you if it's mushroom weather* ☔


Ever wondered if today's weather is perfect for mushroom hunting or if you should just stick to Netflix? This cheeky little app combines real-time weather data with questionable life advice to give you scientifically-backed outdoor recommendations!

**The Magic**: Real-time weather API + PostgreSQL brain + Streamlit charm = Your new favorite procrastination tool

- Tools: Python, Streamlit, SQLAlchemy, PostgreSQL, pandas
- Highlights:
  - Real-time weather fetcher with OpenWeather API
  - Mushroom Foraging Score & Hiking Comfort Score (0–10)
  - PostgreSQL integration to log weather + user queries
  - Data science notebooks for EDA and modeling future predictions
  - Playful UI with custom fonts, blurred background image, and verdicts

---

### 🤖 AI Fitness Recommender Pro Gym Coach Fitness Trainer Buddy 🤖
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](your-deployed-app-url)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black)](your-github-repo-url)

**Multi-Agent Machine Learning System for Personalized Fitness Planning**

Developed a production-ready AI fitness recommendation system combining **multi-agent architecture** with **ML models** trained on 7,000+ workout records. The system achieves **85%+ prediction accuracy** with <100ms response times for real-time personalized workout generation.

**Key Technical Achievements**:
- **ML Pipeline**: Random Forest models (R² > 0.8) for exercise rating prediction
- **Multi-Agent AI**: CrewAI framework coordinating Data Analyst, Personal Trainer, and Nutrition Advisor agents  
- **Production Deployment**: Streamlit web app with interactive Plotly analytics and real-time ML inference

**Tech Stack**: Python, scikit-learn, CrewAI, Streamlit, Plotly  
**Impact**: Personalized recommendations for diverse equipment constraints and fitness goals


---

### 🏋️ [What is this mushroom?](https://github.com/yves-rdlb/What-is-this-Mushroom/tree/master)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://mushroom-frontend-kuiusfhsjsm5jz6og2mcig.streamlit.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black)](https://github.com/yves-rdlb/What-is-this-Mushroom/tree/master)


*Teaching computers to save lives, one fungus at a time* ⚗️

Safety-first **mushroom identification demo** using computer vision and API-first architecture. Predicts species from an image and maps to deterministic edibility with confidence gating.  

**Plot Twist**: The app will literally refuse to guess if it's not sure – because nobody wants to explain a mushroom mishap to the ER doctor! 🏥


- **Frontend**: Streamlit app (API-only client)  
- **Backend**: FastAPI with Vision Transformer (ViT) model; legacy EfficientNet path  
- **Pipeline**: Image preprocessing → ViT classification (~169 species) → CSV-driven edibility lookup → safety gate (abstain below confidence threshold)  
- **Extra**: Optional heatmap visualization from species occurrence data  

**Impact:** Demonstrates **end-to-end ML engineering** (model serving, inference API, frontend integration, Dockerization, CI/testing). Shows awareness of **safety-critical UX** by abstaining on low confidence predictions.

---
### 🎬 [Show Recommendation System with LLMs](https://github.com/ferdaousbouzaiene/showrecommender)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](url)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black)](https://github.com/ferdaousbouzaiene/showrecommender)

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
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](url)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black)](https://github.com/ferdaousbouzaiene/agentellic)

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
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](url)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black)](https://github.com/ferdaousbouzaiene/RagProject)

Implemented Retrieval-Augmented Generation (RAG) using LLMs to create a chatbot that answers questions from PDF documents.

- Tools: LangChain, OpenAI API, FAISS, Streamlit  
- Highlights:
  - Handles long PDFs and extracts relevant passages  
  - Explores different chunking strategies and embeddings  
  - Lightweight UI to demo retrieval performance  

**Impact**: Reinforces knowledge of vector search + RAG patterns, key skills for modern AI engineering.  

---
<!--
### 🍽️ [Restaurant Recommender System](https://github.com/ferdaousbouzaiene/restaurantrecommender)
Built a content-based recommendation system for restaurants using TF-IDF and cosine similarity on dish descriptions, cuisines, and customer reviews.

- Tools: Python, pandas, scikit-learn, Streamlit  
- Highlights:
  - TF-IDF vectorization + cosine similarity on menu data  
  - Interactive Streamlit app for filtering cuisines & locations  
  - Prototype for personalized dining suggestions  

**Impact**: Demonstrates classical NLP + recommender techniques applied to real-world consumer data.  
-->
---

## 🎲 Random Fun Facts About My Data Journey

- 🧮 I originally learned math in French, so I still think "vecteurs propres" sounds way cooler than "eigenvectors"
- 🍄 Built a mushroom classifier after one too many "is this edible?" hiking debates
- 🤖 Currently working on a Tamagotchi-inspired app (because apparently, I have a thing for keeping digital creatures alive)
- 📺 When not coding, I'm binge-watching TV dramas (rewattching one-tree-hill currently) and wondering if I can build a recommendation system for my next obsession
- 🎯 My code has a 78% success rate on first try (the other 22% involves creative debugging and possibly tears)

---
---

## Resumé (or CV?)

📄 [Download My Resume](resume.pdf)

## 🎪 Let's Connect & Create Chaos Together!

🔗 [GitHub](https://github.com/ferdaousbouzaiene)   ← Where my code lives (and sometimes thrives)  
🔗 [LinkedIn](https://linkedin.com/in/ferdaousbouzaiene)   ← Professional face  
📧 [ferdaous.bouzaiene@gmail.com](mailto:ferdaous.bouzaiene@gmail.com) ← For urgent matters and meme exchanges 
