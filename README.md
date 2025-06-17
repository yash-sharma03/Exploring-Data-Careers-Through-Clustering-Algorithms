# Exploring-Data-Careers-Through-Clustering-Algorithms

This project was developed for OMIS 115: Predictive Analytics at Santa Clara University. Our goal was to explore what a career in data looks like through real-world job postings by applying clustering and text analysis techniques.

## Project Objective
Aimed to analyze over 600+ data job postings and answer:
- What skills are most in-demand for data roles?
- How are these roles clustered by location?
- What patterns emerge when we group job descriptions by keyword similarity?

## Technique Used
- **TF-IDF Vectorization:** To convert job summaries into keyword-based vectors
- **KMeans Clustering (k=4):** To identify groups of job roles by similar language
- **Agglomerative Clustering:** For geographic clustering of postings
- **Data Cleaning & Preprocessing:** Lowercasing, noise removal, stop word filtering
