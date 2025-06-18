📊 Netflix Movies & TV Shows EDA Project
A comprehensive exploratory data analysis (EDA) of Netflix’s catalog to uncover trends in content type, release patterns, regional contributions, genres, and participation by actors and directors.

🎯 Objective
The objective of this project is to analyze the Netflix dataset and extract actionable insights that can help:

Understand the type and volume of content available.

Explore genre and duration distributions.

Identify key contributing countries, actors, and directors.

Reveal release trends and patterns in content addition.

Support strategic decisions in content curation and recommendations.

📁 Dataset
The dataset used is titled "NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv", containing details like:

Title, type (Movie/TV Show), country, release year, duration, cast, director, genre (listed_in), and date added.

🧰 Libraries Used
Pandas – Data manipulation and cleaning

NumPy – Numerical operations

Matplotlib – Basic plotting

Seaborn – Advanced visualization

Warnings – To suppress unnecessary warnings

Datetime – Date operations for columns like date_added

🔍 Key Explorations & Visualizations
1. Content Type Distribution
Pie chart showing share of Movies vs TV Shows.

📌 Insight: Movies dominate the Netflix catalog.

2. Top Genres
Bar chart of top 10 most frequent genres.

📌 Insight: Drama and International content lead genre-wise.

3. Content Duration Breakdown
Separated duration into time and unit (e.g., minutes vs seasons).

📌 Insight: TV shows mostly span 1-2 seasons, while movies cluster around 90-120 minutes.

4. Top Countries
Bar plot of top 10 countries producing Netflix content.

📌 Insight: United States, India, and UK are top contributors.

5. Release Trend Over Time
Countplot showing yearly content release trends.

📌 Insight: Peak in releases observed after 2015.

6. Release Year vs Year Added
Pairplot among release_year, year_added, and duration_time.

📌 Insight: Most content is added shortly after its release.

7. Top Actors and Directors
Pie charts for top 5 actors/directors from US, India, UK.

📌 Insight: Content is driven by a few high-frequency contributors.

8. Pairplot Insights
Relationship between release year, content duration, and addition year.

📌 Insight: No strong linear correlation, but newer content is more frequently added.

📈 Business Impact
Helps Netflix identify regional strengths and gaps.

Aids in talent acquisition (popular actors/directors).

Supports genre-focused content production and localized content strategies.

Offers data-driven inputs for recommender systems and UI personalization.

🧼 Data Cleaning
Removed or replaced all missing values with 'Not Known' or 'Unknown'.

Extracted duration_time and duration_type from the original duration column.

Converted date_added into separate year_added for time-based analysis.
