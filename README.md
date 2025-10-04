# Spotify-data-analysis
A comprehensive Exploratory Data Analysis (EDA) of the Spotify dataset that dissects audio features and their relationship with popularity to uncover insights for music recommendation and understanding trends.
# Exploratory Data Analysis of Spotify Tracks

### A Deep Dive into the "Formula for a Hit"

This project is a deep dive into Exploratory Data Analysis (EDA) using a dataset of over 586,000 Spotify tracks. The goal is to perform a comprehensive analysis to understand the characteristics of music, identify key relationships between different audio features, and uncover insights into the drivers of song popularity.

**Author:** Jeba Rahath

---

### 🛠️ Tech Stack & Libraries

This analysis was performed using Python and the following key libraries:
* Pandas (for data manipulation)
* Matplotlib & Seaborn (for data visualization)
* Scikit-learn (for machine learning - clustering, PCA, and predictive modeling)

---

###  Repository Contents

* **`Spotify main.ipynb`**: The main Jupyter Notebook containing all the code, visualizations, and detailed findings.
* **`Spotify main.pdf`**: A presentation that summarizes the key insights and business recommendations from the analysis.
* **`spotify_tracks.csv`**: The dataset used for this project.
* **`spotify_data_description.csv`**: The data description used for this project.
* **`README.md`**: This summary file.

---

###  Key Insights & Findings

Our deep-dive analysis of the Spotify dataset yielded several key insights:

1.  **The "Hit Formula" is Driven by Production:** A song's popularity is not random. It is most strongly correlated with **high loudness** and **high energy**. Conversely, high **acousticness** is a negative predictor of success. This suggests that the "sound" of a hit is defined by its production intensity.

2.  **Nostalgia is a Powerful Force:** There is a clear "golden era" in the data. Songs released in the **late 1970s** have a timeless quality, showing a significantly higher average popularity than music from any other period, including the modern era.

3.  **Success Can Be Predicted:** Using the audio features as inputs, we successfully built a machine learning model that acts as a **"cautious but reliable" hit detector**. It can identify potential hit songs with high precision, providing a valuable tool for filtering new music.

4.  **Some Common Assumptions Are False:** The data shows that a song's musical key (**major vs. minor**) has **no significant impact** on its overall popularity or its historical trends.

---

###  Business Recommendations

Based on the findings, we propose the following data-driven recommendations:

* **For Artists & Labels:** Focus on the "hit formula." Prioritize **high-energy and powerfully produced tracks** to maximize commercial potential. Use the predictive model as a screening tool to identify demos with the highest sonic chance of success.
* **For Playlist Curators:** Look beyond genre. **Capitalize on the "golden era"** by creating and promoting 1970s "throwback" playlists. Use the data-driven "sonic profiles" (e.g., "happy and energetic") from our clustering analysis to create more effective mood-based playlists.
* **For Marketing Teams:** Market the "vibe." Launch campaigns based on a song's specific sonic profile to better connect with the listener's context, promoting high-energy tracks for parties and mellow tracks for focus or relaxation.
