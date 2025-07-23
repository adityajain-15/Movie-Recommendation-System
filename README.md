🎬 Movie Recommendation System
<div align="center">
[![Python](https://img.shields.iotps://img.shieldsarn](https://img.g.shieldsITds.iorecommendation system that suggests similar movies based on content analysis**

Demo - Features - Installation - Usage - API - Contributing

</div>
📖 About
This project implements a Content-Based Movie Recommendation System using machine learning techniques. It analyzes movie metadata including genres, cast, crew, keywords, and plot summaries to recommend similar movies. The system features a beautiful, responsive web interface built with Gradio and integrates with The Movie Database (TMDB) API for rich movie information and posters.

🎯 How It Works
Data Processing: Extracts and cleans movie metadata from the TMDB 5000 movies dataset

Feature Extraction: Combines genres, keywords, cast, crew, and overview into feature vectors

Vectorization: Uses CountVectorizer to convert text features into numerical vectors

Similarity Calculation: Computes cosine similarity between all movie pairs

Recommendations: Returns the top 5 most similar movies based on content similarity

✨ FeaturesCore Features
Intelligent Recommendations: Content-based filtering using cosine similarity

Rich Movie Information: Ratings, genres, release year, runtime, and detailed overviews

Movie Posters: High-quality posters fetched from TMDB API

Real-time Search: Instant movie search across 5000+ movies

Similarity Scoring: Shows percentage similarity between recommended movies

User Interface
Modern Design: Professional gradient-based UI with smooth animations

Responsive Layout: Works perfectly on desktop, tablet, and mobile devices

Tabbed Interface: Organized sections for recommendations, search, and system info

Interactive Elements: Real-time updates and hover effects

Accessibility: User-friendly design with clear visual hierarchy

Analytics
System Statistics: Database size, feature count, and algorithm details

Performance Metrics: Real-time processing information

Process Visualization: Step-by-step explanation of how recommendations work

Technologies Used
Technology	Purpose	Version
Python	Core programming language	3.8+
Pandas	Data manipulation and analysis	Latest
NumPy	Numerical computing	Latest
Scikit-learn	Machine learning algorithms	Latest
Gradio	Web interface framework	Latest
Requests	HTTP requests for API calls	Latest
KaggleHub	Dataset download and management	Latest
Machine Learning
CountVectorizer: Text feature extraction

Cosine Similarity: Similarity measurement algorithm

Content-Based Filtering: Recommendation algorithm approach

