# 🎧 Spotify Tracks Analysis  

**Exploring the Science Behind Music Popularity with Data & Rhythm**  
by **Dipanjan Halder (Team DataMinds)**  

---

## 🧭 Project Overview  

This repository contains an **Exploratory Data Analysis (EDA)** project on the Spotify music dataset — decoding how sound, structure, and emotion come together to shape hit songs.  

**Objective:** Analyze Spotify’s audio features and uncover how factors like **energy**, **danceability**, **valence**, and **tempo** drive a track’s success and listener engagement across decades.  

---

## 🚀 How to Run  

To reproduce the analysis:  
1. Clone the repository  
2. Open **Spotify.ipynb** in Jupyter Notebook or VS Code  
3. Run all cells sequentially  

### 🔧 Dependencies  
```bash
pandas  
numpy  
matplotlib  
seaborn

### 📊 Dataset Description

Two CSV files are provided in the repository:

File Name	Description
spotify_tracks.csv	Primary dataset containing Spotify song-level data (track, artist, popularity, and audio features).
spotify_data_description.csv	Metadata providing column definitions and types.
🎼 Key Columns

track_name: Name of the track

artist_name: Artist or group performing

popularity: Spotify popularity score (0–100)

danceability, energy, valence, tempo: Audio features representing rhythm, intensity, and emotion

duration_ms: Track length in milliseconds

year: Year of release

🔍 EDA Highlights
🎚️ 1. Univariate Analysis

Explored distributions of major attributes such as popularity, energy, and danceability to understand dataset balance and feature spread.

🔗 2. Bivariate & Multivariate Insights

Energy ↗ Popularity: High-energy songs are more likely to trend.

Danceability ↔ Valence: Tracks that are upbeat and happy tend to cluster near the top of popularity metrics.

Acousticness ↘ Loudness: Soft, acoustic songs generally perform better in niche categories, not mass hits.

🕓 3. Time Series Evolution

Rise of streaming-era songs (2010s–2020s) shows shorter, high-energy patterns.

Average track length has declined steadily since early 2000s.

Energy and danceability show similar growth patterns reflecting upbeat music trends.

🎯 Key Insights

Shorter songs dominate: Listeners prefer 2.5–4 minute formats with early hooks.

Energy + Danceability = Replay Value: A moderate balance (0.6–0.8 range) keeps songs engaging.

Positivity Matters: Tracks with mid-to-high valence achieve higher popularity.

Modern sound design: Streaming-era music favors punchier loudness levels and digital clarity.

Genre impact: Highly energetic and rhythm-driven tracks outperform acoustic or slow-paced ones.

🧩 Repository Structure
File	Description
Spotify.ipynb	Main Jupyter notebook (EDA & visualization)
spotify_tracks.csv	Dataset used for analysis
spotify_data_description.csv	Column description file
Presentation_EDA_Spotify.pdf	Final presentation slides
README.md	This documentation file
💡 Learnings & Future Work

Extend analysis using machine learning for hit prediction models

Cluster songs based on mood and genre similarity

Deploy interactive dashboards for real-time exploration of Spotify trends

👨‍💻 Author

Dipanjan Halder
2nd Year B.Tech, GCECT Kolkata
Team: DataMinds
📍 Kolkata, India

🎶 Closing Note

This project combines music intelligence with data storytelling — decoding how creativity and analytics harmonize in the modern music era.

💫 “Great music feels effortless — but behind every hit lies the rhythm of data.”
