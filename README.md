# Spotify_Tracks_Analysis
Exploratory Data Analysis on Spotify Tracks Dataset

# Analysis of Spotify Tracks Dataset
## Exploratory Data Analysis Project

*Presented by:* Swargashri Shit, Team: DS Explorers

## Project Overview

This repository contains a comprehensive Exploratory Data Analysis (EDA) of the Spotify Tracks Dataset. The project aims to uncover trends, relationships, and patterns within music features to provide valuable insights for mixing engineers and music production professionals.

## Team Members

- Rishov Paul - Key Insight writer , Recommedation writer , Presentation Maker , Top N Analysis
- Prithujit Ghosh - Preprocessing, Univariate & Bivariate Analysis , Multivariate analysis, Time-Series Analysis, Visualization Expert
- Parama Dey - Preprocessing, Univariate & Bivariate Analysis , Multivariate analysis, Time-Series Analysis, Visualization Expert
- Swargashri Shit - Story Telling , Helping Role

## Project Objectives

- Understand patterns in song features
- Explore relationships between variables
- Identify trends across time periods
- Provide actionable insights for mixing engineers

## Dataset Information

*Dataset Size:*
- Number of rows: 49,234
- Number of columns: 22
- Time period: 1971 - 2024

*Key Features Analyzed:*
- Popularity
- Danceability
- Energy
- Acousticness
- Valence
- Tempo
- Duration
- Loudness
- Speechiness
- Liveness
- Mode
- Key
- Language
- Artist information

## Install Dependencies and Run Analysis


pandas
numpy
matplotlib
seaborn


## Project Roadmap

1. Data Collection & Preprocessing
   - Removing unknowns and missing values
   - Eliminating duplicates
   - Data type conversions
   - Deriving new features

2. Exploratory Data Analysis (EDA)
   - Univariate Analysis (Numerical and Categorical)
   - Bivariate Analysis (Numerical vs Numerical, Numerical vs Categorical)
   - Multivariate Analysis

3. Time Series Trends
   - Track releases over years
   - Popularity trends
   - Music feature evolution
   - Solo vs collaboration patterns
   - Correlation changes over time

4. Top N Analysis
   - Top artists by track count
   - One-hit wonders analysis
   - Artists with longest careers
   - Most popular artists

5. Recommendations & Insights
   - Data-driven guidance for mixing engineers

## Key Insights & Findings

*Popularity Distribution:*
- Most tracks have very low popularity scores with a highly right-skewed distribution
- Top 1% of tracks start at a popularity score of 71
- Top 10% controls over one-third (35.81%) of all popularity

*Musical Features:*
- Strong positive correlation exists between danceability, energy, and valence (0.49-0.65)
- Acousticness has dramatically declined from the 1970s to present
- Energy levels have steadily increased, especially since 2000

*Temporal Trends:*
- The 2020s and 2010s dominate with nearly 80% of all tracks
- Major inflection point occurred in 2019-2020 across all languages
- Maximum popularity shows upward trend while median remains suppressed

*Duration Analysis:*
- Medium-length songs (3-5 minutes) dominate with 70% of popular tracks
- Strong negative correlation between duration and popularity
- Extremely short or long tracks tend to be less popular

*Language Insights:*
- English dominates at 47.5% of dataset and 69.3% of top 1% tracks
- Korean shows highest median energy (~0.8) and explosive recent growth
- Tamil exhibits highest danceability and valence (positivity)
- Hindi tracks are predominantly Bollywood film soundtracks

*Solo vs Collaboration:*
- Solo work slightly dominates at 55.2% while collaborations make up 44.8%
- Solo tracks achieve higher average popularity (~18) vs collaborations (~14)

*Feature Correlations:*
- All individual features show weak correlations with popularity (under ±0.2)
- Correlation between popularity and danceability dropped from 0.77 (1970s) to near zero
- Energy remains the most relevant feature but much weaker than historical trends

*Tempo Patterns:*
- Most languages maintain consistent moderate tempo (100-140 BPM median)
- Fast songs dominate high popularity clusters
- High popularity songs span 80-200 BPM range

## Repository Structure


README.md (This file)
Analysis of Spotify Tracks Dataset.pptx.pdf (Complete presentation with visualizations)
spotify_tracks_data.csv (Raw dataset - if available)
analysis.ipynb (Jupyter Notebook with analysis code - if available)


## Key Recommendations for Mixing Engineers

Based on our comprehensive analysis, mixing engineers should:

- Optimize for high energy levels (0.6-0.8 range) and danceability
- Target 3-5 minute song duration for maximum commercial appeal
- Reduce acoustic elements and embrace modern electronic/digital production
- Maintain moderate tempo in the 100-140 BPM range
- Balance loudness appropriately as it correlates with energy
- Adapt mixing approach based on language-specific characteristics
- Understand that no single feature guarantees success - focus on holistic quality
- Stay current with 2010s-2020s production trends
- Recognize the highly competitive landscape where top 10% controls majority of popularity

## Analysis Highlights

*Univariate Analysis:*
- Comprehensive distribution analysis of all numerical variables
- Categorical breakdown by year groups, solo vs collaboration, and languages

*Bivariate Analysis:*
- Joint plots revealing duration, danceability, and energy relationships with popularity
- Correlation heatmap showing feature interdependencies
- Box plots comparing features across languages and categories

*Multivariate Analysis:*
- Language-wise analysis of numerical variables over year groups
- Complex interactions between tempo, energy, and popularity

*Time Series Analysis:*
- Evolution of track releases showing exponential growth post-2019
- Popularity trends revealing increasing inequality
- Feature trends showing acousticness decline and energy increase
- Changing patterns in solo vs collaboration by language

*Top N Analysis:*
- Top 10 one-hit wonders by popularity across languages
- Artists with most albums and longest careers
- Distribution of top tracks by language and duration categories

## Future Work Directions

- User listening behaviors analysis
- Recommendation system development
- Exploring lyrics aspects and their correlation with popularity

## Conclusion

This analysis reveals that modern music success on Spotify is characterized by high energy, danceable tracks in the 3-5 minute range with reduced acoustic elements. However, with weak individual feature correlations to popularity (all under ±0.2), success requires balanced, high-quality production rather than optimizing single attributes. The increasing concentration of popularity in the top 10% of tracks highlights the competitive nature of the modern music landscape.

For detailed visualizations, statistical analysis, and comprehensive findings, please refer to the complete presentation PDF.
