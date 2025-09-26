# 🍄🥾 Spores & Outdoors: Weather-Driven Outdoor Activity Recommender

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://spores-outdoors-iuuvvacjpqlqmg6ejunewm.streamlit.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black)](https://github.com/ferdaousbouzaiene/Spores-Outdoors)

## What it does

A full-stack web application that combines real-time weather data with machine learning to provide personalized outdoor activity recommendations. The app integrates weather APIs, PostgreSQL database, and custom scoring algorithms to deliver actionable insights for outdoor enthusiasts like moi to decide the best times to go mushroom foraging or hiking. 


## How it works

### 🔗 Data & Backend 🔗
- **OpenWeather API** – Live weather data
- **PostgreSQL** – Stores user queries and scores
- **SQLAlchemy** – Handles database operations

### 🖥️ Frontend 🖥️
- **Streamlit** – Web UI framework
- **Scoring Engine** – Custom scores:
  - *Mushroom Score* (0–10): Based on humidity, rain, temp, season
  - *Hiking Score* (0–10): Based on temp, wind, UV index, rain
- **Pandas** – Data cleaning and feature engineering


### 🚀 Deployment 🚀 
- Hosted on **Streamlit Cloud**
- Weather API handled with **rate limits** and **caching**
- Uses environment variables for API key security

## 🔧 Development Process 🔧

### 1. Requirements Gathering & System Design
- Identified user needs (me) for weather-informed outdoor activity planning
- Designed scoring algorithms based on meteorological research
- Created database schema for user interaction tracking

### 2. Backend Development
- Implemented weather data ingestion pipeline
- Built PostgreSQL integration
- Created scoring algorithms factoring temperature, humidity, precipitation, wind conditions

### 3. Frontend Development
- Developed Interactive, user-friendly interface
- Implemented real-time weather visualization with dynamic backgrounds (in progress 🚧⏳🔄🔜)
- Created intuitive user flow from location input to actionable recommendations (🚧⏳🔄🔜)

### 4. Production Deployment
- Configured environment variables for secure API key management
- Implemented error handling and graceful degradation for API failures
- Set up database connection pooling for potential scalability

## Technical Implementation Details

### Weather  Engine
function: calculate_mushroom_score(weather_data)
Considers:
- Humidity levels (optimal 70-90%)
- Recent precipitation patterns
- Temperature range (50-75°F optimal)
- Seasonal factors


### Database Tables
- **weather_queries**: User search history and preferences
- **recommendations**: Generated scores with reasoning
- **user_feedback**: Optional rating system for model improvement

### Performance Optimization (in progress 🚧⏳🔄🔜)
- **Caching Strategy**: Redis-like caching for frequently requested locations
- **Database Indexing**: Optimized queries for weather data retrieval
- **API Rate Limiting**: Intelligent batching to minimize external API calls

## 💡 Features 💡

### Intelligent Scoring System
- **Mushroom Foraging Score**: Considers humidity, recent rain, temperature, and seasonal factors
- **Hiking Comfort Score**: Factors in wind speed, temperature, UV index, and precipitation probability
- **Dynamic Recommendations**: Contextual advice based on current conditions


## Business Impact & Scalability

### Current Metrics
- **Response Time**: <2 seconds for weather data retrieval and processing


### Coming Soon
- **Mobile App Development**: React Native implementation for iOS/Android
- **Machine Learning Integration**: Predictive modeling for optimal activity timing
- **Social Features**: Community-driven activity planning and reviews
- **Premium Features**: Extended forecasts and personalized activity calendars
