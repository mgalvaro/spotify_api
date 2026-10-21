# 🎵 Music Landscape Analysis: Billboard Hot 100 & Spotify

## Project Description

Data analysis project developed in Python to explore the music landscape through songs featured on the **Billboard Hot 100** chart and their characteristics on **Spotify**.

The goal is to explore patterns, trends, and differences among the chart's most prominent songs by analyzing their popularity, musical features, evolution over time, and associated genres.

The project implements a complete **ETL (Extract, Transform, Load)** pipeline, incorporating data visualization and hypothesis testing to draw evidence-based conclusions.

## Objectives

- Automatically extract historical Billboard Hot 100 data through web scraping.
- Retrieve additional song information through the Spotify API.
- Clean, transform, and combine data using Python, pandas, and NumPy.
- Store processed data in Airtable through its API.
- Analyze music trends, popularity, chart longevity, and song characteristics.
- Investigate statistical differences between music genres.

## Technologies Used

- **Python**: Process development and automation.
- **Requests and BeautifulSoup**: Data extraction through web scraping.
- **Spotipy**: Access to the Spotify API.
- **pandas and NumPy**: Data cleaning, transformation, and analysis.
- **Airtable API**: Data storage and retrieval.
- **Matplotlib and Seaborn**: Statistical data visualization.
- **Plotly**: Interactive charts.
- **Jupyter Notebook**: Development, documentation, and presentation of the analysis.

## ETL Process

1. **Extract:** Retrieve historical Billboard Hot 100 chart rankings and enrich the data with information from Spotify.
2. **Transform:** Handle missing values, remove duplicates, normalize variables, calculate song durations, and combine datasets.
3. **Load:** Automatically upload processed data to Airtable and retrieve it later for analysis.

## Analysis and Visualizations

The project includes:

- Correlation matrices and scatter plots.
- Distributions of popularity, danceability, energy, and tempo.
- Analysis of songs with the longest chart runs and those that reach number one.
- Time-series analysis of songs and seasonal trends.
- Analysis of music genres, artists, and popularity.
- Hypothesis testing to compare the popularity of songs in pop, Atlanta hip-hop, and contemporary country.

## Key Findings

The analysis identifies pop, Atlanta hip-hop, and contemporary country among the genres with the strongest representation in the dataset. It also highlights the importance of seasonality, new releases, and diverse trends in shaping chart dynamics over time.

The statistical tests reveal significant differences in popularity between pop and Atlanta hip-hop songs, as well as between pop and contemporary country songs, at a **95% confidence level**.

## Project Structure

The analysis is primarily developed in Jupyter notebooks, which document the extraction, transformation, loading, visualization, and conclusion stages.

## Security

Spotify and Airtable credentials should be stored in environment variables or local files excluded through `.gitignore`. Tokens, private keys, and files containing credentials must never be published.

## Author

Academic data analysis project — Team A.
