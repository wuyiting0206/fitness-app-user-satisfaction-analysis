# What Drives User Satisfaction in Fitness Apps?
A Google Play Health & Fitness App Analysis

## Project Overview
This project explores what drives user satisfaction in Google Play Health & Fitness apps. Using publicly available app metadata and user review data, it examines which app characteristics and user-mentioned themes are associated with higher ratings and more positive feedback.

The project is designed for **fitness app product managers, app developers, and digital health startups** who want evidence-based insights into what users value most and what issues reduce satisfaction.

## Business Problem
Fitness app teams need to understand what improves user satisfaction and what causes dissatisfaction. By analyzing app ratings, installs, review volume, pricing model, and review themes, this project provides practical suggestions for product improvement and feature prioritization.

## Target Users
- Fitness app product managers  
- App developers  
- Digital health startups  

## Research Questions
This project focuses on the following questions:

1. What app characteristics are associated with higher ratings in fitness apps?
2. What themes appear most often in positive user reviews?
3. What complaints appear most often in negative user reviews?

## Data Sources
This project uses publicly available datasets from Kaggle:

1. **Google Play Store app metadata dataset**  
   - Includes app name, category, rating, reviews, installs, type, price, and related metadata  
   - Source: https://www.kaggle.com/datasets/lava18/google-play-store-apps
   - Access date: 2026.4.23

2. **Google Play user reviews dataset**  
   - Includes app name, translated review text, and sentiment information (if available)  
   - Source: https://www.kaggle.com/datasets/lava18/google-play-store-apps
   - Access date: 2026.4.23

> Note: If the data files are too large to upload to GitHub, the source links and access instructions are provided here instead.

## Methods
The project uses Python for data cleaning, transformation, analysis, and visualization. The main steps include:

- loading app metadata and review datasets
- filtering apps in the **Health & Fitness** category
- cleaning rating, review count, installs, and pricing fields
- merging metadata with review information where possible
- comparing app characteristics associated with higher ratings
- identifying common themes in positive and negative user reviews
- visualizing patterns with charts and summary tables

## Tools and Libraries
- Python
- pandas
- numpy
- matplotlib
- seaborn
- [Optional: nltk / wordcloud / re / scikit-learn]

## Repository Structure
```text
fitness-app-user-satisfaction-analysis/
│
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   └── fitness_app_analysis.ipynb
├── images/
├── requirements.txt
└── README.md
```
## Key Findings
The analysis suggests that higher-rated fitness apps tend to have stronger user engagement indicators, such as higher install counts and more review activity. Positive reviews often mention useful workout guidance, progress tracking, and ease of use. Negative reviews frequently focus on bugs, app crashes, intrusive ads, and subscription or payment-related frustration.

## How to Run
1. Download or clone this repository.
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
3.Open the notebook file:
```text
notebook.ipynb
```
4.Run the notebook from top to bottom to reproduce the analysis and charts.
## Limitations
1. The dataset may not include all Health & Fitness apps available on Google Play.
2. Publicly available app data may contain missing values or inconsistencies.
3. Ratings and reviews do not fully represent long-term user retention or satisfaction.
4. Review theme analysis may simplify complex user opinions, especially when using keyword-based methods.


