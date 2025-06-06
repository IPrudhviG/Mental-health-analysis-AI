# Reddit Mental Health Analysis with OpenAI
This project analyzes mental health-related posts from Reddit using Python, OpenAI, SQL, BigQuery, and Tableau. It demonstrates a complete data workflow — from extracting real-time data via Reddit API, applying AI-based emotion classification, to uncovering insights through visual analytics.

---

## Project Objective

To identify emotional patterns in user-generated Reddit posts (e.g., depression, anxiety, suicidal ideation) using AI-driven tagging and data analytics. The aim is to support early detection, raise awareness, and potentially assist in mental health interventions through data.

---

## Tech Stack :

| Tool                  | Purpose                                       |
| --------------------- | --------------------------------------------- |
| **Python**            | Data extraction, transformation, and analysis |
| **PRAW (Reddit API)** | Accessing and scraping Reddit posts           |
| **OpenAI GPT-3.5**    | Emotion classification using prompt-based AI  |
| **SQL**               | Querying structured datasets                  |
| **Google BigQuery**   | Scalable cloud data storage and analytics     |
| **Tableau**           | Interactive dashboards and visualization      |

---

## Project Components

- Reddit Data Collection: Fetches posts from mental health subreddits using the PRAW API

- AI-Powered Emotion Detection: Classifies each post's emotion using OpenAI (e.g., happy, sad, anxious, depressed, suicidal, or neutral)

- Clean Data Pipeline: Cleans and preprocesses raw data for structured storage and analysis

- Cloud Integration: Uploads processed data to Google BigQuery for further querying

- Interactive Visualization: Visualizes emotion trends and distributions across time and categories using Tableau

- Scalable Architecture: Easily extendable to support more subreddits, emotion categories, or platforms
