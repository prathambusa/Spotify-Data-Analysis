# Spotify Listening Data Analysis  
Uncovering patterns, insights, and surprises in my own Spotify listening data—because data never lies, but my playlists might! 

### 📌 Overview  
Ever wondered what your Spotify listening history reveals about you? This project dives deep into my personal Spotify data, uncovering trends, patterns, and insights through data analysis and visualization. From identifying peak listening hours to understanding artist preferences, this project showcases the power of data storytelling.

### 🚀 Project Highlights  
- Extracted personal Spotify listening data using the **Spotify API**  
- Processed and cleaned the data with **Pandas**  
- Created detailed visualizations using **Matplotlib & Seaborn**  
- Explored listening habits, peak hours, and artist preferences  
- Attempted (and failed) to extract **audio features** due to API limitations, leading to key lessons in data adaptability  

---

## 🔧 Tech Stack  
- **Python** (Data processing, API requests)  
- **Pandas** (Data wrangling & transformation)  
- **Matplotlib & Seaborn** (Data visualization)  
- **Spotify API** (Data extraction)  

---

⚙️ Prerequisites
Before you start, ensure you have:

✅ A Spotify Developer Account – Sign up at Spotify for Developers
✅ Python 3.x installed
✅ The following Python libraries:

Spotipy (for API requests)
Pandas (for data manipulation)
Matplotlib & Seaborn (for data visualization)
To install dependencies, run:

''pip install spotipy pandas matplotlib seaborn''


🚀 Step-by-Step Implementation

# Step 1: Get Spotify API Credentials
- Log in to the Spotify Developer Dashboard.
- Click on Create an App and note down:
- Client ID
- Client Secret
- Set a redirect URI (e.g., http://localhost:9000/callback/).

# Step 2: Authenticate and Fetch Data
Spotify requires OAuth authentication to access user data.

I used Spotipy, a Python wrapper for the Spotify API, to extract recently played tracks from my account.
The extracted data includes track name, artist, album, popularity, explicit content, duration, and timestamp of when the track was played.

# Step 3: Data Cleaning & Preprocessing
- Converted timestamps into a datetime format for trend analysis.
- Removed duplicate entries and handled missing values.
- Sorted tracks by listening time to track trends accurately.

# Step 4: Data Visualization & Insights
- ## Top Artists & Most Played Songs
Identified top 10 artists based on play count.
Visualized artist distribution using bar charts.
- ## Listening Trends Over Time
Analyzed hourly listening trends to find peak hours of music consumption.
Created a histogram to show the distribution of listening activity throughout the day.
- ## Day-Wise Listening Patterns
Identified which days of the week had the highest music engagement.
Compared weekday vs. weekend listening behavior using bar plots.
- ## Track Duration Analysis
Analyzed the distribution of track durations in my listening history.
Plotted a histogram to identify patterns in the types of songs I listen to (short bursts or longer tracks).

# Step 5: Challenges & Workarounds
I initially attempted to extract audio features (danceability, energy, tempo, etc.), but ran into Spotify API rate limits and authentication issues. Despite multiple workarounds, I had to pivot and focus on time-based and artist-based insights—a great lesson in real-world data adaptability.

📊 Key Takeaways
- Music habits reveal powerful insights—my listening peaks in early mornings & late nights.
- Data cleaning is crucial—timestamps, duplicates, and missing values required handling.
- APIs are unpredictable—working around authentication & rate limits was a major challenge.
- Visualization brings data to life—trends became clearer when plotted.


## 🔗 Connect with Me  
- **LinkedIn:** [[Your Profile Link]  ](https://www.linkedin.com/in/prathambusa15/)
- **GitHub:** [[Your GitHub Link] ](https://github.com/prathambusa?tab=repositories) 

---
