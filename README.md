# Spotify Insights Project

This repository contains two Python Jupyter notebooks designed to extract and analyze Spotify data using Spotify's API, with insights stored and managed using SQLite.

### Overview
- **`spotify_insights.ipynb`**:
  - Authenticates and interacts with Spotify’s API.
  - Extracts data related to playlists, tracks, and artists.
  - Processes and structures the data into pandas DataFrames for analysis.

- **`spotify_insights_sql.ipynb`**:
  - Initializes and manages a SQLite database for storing Spotify data.
  - Defines and creates database tables for artists, playlists, and tracks.
  - Connects seamlessly with the data extraction notebook to store and manage Spotify data persistently.

### Features
- Seamless integration between Spotify API data extraction and SQLite database management.
- Robust error handling and data validation to ensure data integrity.
- Structured, reusable code facilitating further Spotify-related data projects.

### Technologies Used
- Python (requests, pandas)
- SQLite (sqlite3)
- Spotify API

### Setup Instructions
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install requests pandas
   ```
3. Obtain Spotify API credentials and replace placeholders in `spotify_insights.ipynb`.
4. Execute notebooks sequentially (`spotify_insights.ipynb` first, then `spotify_insights_sql.ipynb`) to extract and store data.

### Potential Use Cases
- Analyzing music trends across genres or decades.
- Building recommendation systems based on playlist and artist data.
- Academic research on music streaming patterns.

