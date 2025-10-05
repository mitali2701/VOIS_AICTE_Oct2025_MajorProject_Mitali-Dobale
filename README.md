# Netflix Content Trends Analysis

## Project Overview
This project analyzes Netflix’s content library to uncover trends in Movies and TV Shows, genres, and country-wise contributions. The aim is to provide **strategic insights** and **recommendations** for content acquisition, production, and global expansion.

## Dataset
- Source: Netflix dataset (CSV) with **7,789 records** and multiple attributes.
- Key columns: `title`, `director`, `cast`, `country`, `release_year`, `rating`, `duration`, `type`, `listed_in`, `description`.
- Years covered: 2008 – 2021
- Includes both **Movies** and **TV Shows** across various genres and countries.

## Objectives
- Analyze distribution of Movies vs TV Shows over the years.
- Identify top genres and trends in their popularity.
- Compare country-wise contributions to Netflix’s catalog.
- Build a **recommendation system** based on content similarity.
- Forecast content trends using **time series analysis**.
- Generate **business insights and recommendations**.

## Technologies Used
- **Python**: Programming and data analysis
- **Pandas & NumPy**: Data cleaning and processing
- **Matplotlib, Seaborn, Plotly**: Data visualization
- **NLTK & WordCloud**: Text processing and visualization
- **Scikit-learn**: ML models (Random Forest, KMeans, PCA) and similarity measures
- **Prophet / fbprophet**: Forecasting content trends
- **ydata-profiling**: Automated data profiling
- **Pycountry**: Country ISO codes for choropleth maps
- **Google Colab**: Development and execution environment

## Project Features
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA) and interactive visualizations
- NLP analysis: word clouds and top keywords
- Clustering & PCA for content archetypes
- Recommendation engine for similar titles
- Forecasting trends of Movies vs TV Shows
- Supervised learning: Predict Movie or TV Show
- Automated insights and business recommendations

## How to Run
1. Open `netflix_analysis.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Upload the dataset (`Netflix Dataset.csv`) if not already included.
3. Run the notebook **cell-by-cell** to:
   - Clean and preprocess data
   - Perform analysis and visualizations
   - Generate forecasts and recommendations
4. Download outputs: cleaned dataset, profile report, and plots as needed.

## End Users
- Netflix **business & strategy teams** for content planning
- **Content creators & marketing teams** for trend analysis and localization
- **Data analysts & ML engineers** for building recommendation systems
- **Researchers & students** for learning and experimentation

## Outputs / Deliverables
- `netflix_cleaned_advanced.csv` – Cleaned dataset
- `netflix_profile.html` – Automated profile report
- Visualizations for EDA, clustering, and forecasts
- Recommendation engine results and content similarity table

## Future Scope
- Enhance recommendation system using **collaborative filtering**
- Perform **sentiment analysis** on user reviews
- Extend forecasting to **genre-wise and regional trends**
- Integrate analysis into a **web dashboard** for interactive insights
