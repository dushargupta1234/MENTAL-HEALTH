Mental Health Trend & Sentiment Analysis

This project analyzes mental health related discussions from Reddit and search behaviour from Google Trends to identify emotional patterns, sentiment distribution, geographical variations and time-based trends. The aim is to understand public mental health behaviour using real-world social data

Project Overview
Mental health awareness is growing, but identifying real patterns is difficult.
This project uses:
1.Reddit mental health discussions
2.Google Trends search data
3.NLP based sentiment analysis
4.Data visualization techniques
to analyze how mental health issues vary over time, geography and online communities.

DATASET DESCRIPTION

| File                                       | Description                                |
| ------------------------------------------ | ------------------------------------------ |
| `reddit_mentalhealth_cleaned.csv`          | Cleaned Reddit mental health posts         |
| `google_trends_cleaned.csv`                | Processed Google search trend data         |
| `geoMap.csv`                               | Geographical mental health mapping dataset |
| `mentalhealth_2018_features_tfidf_256.csv` | TF-IDF extracted features                  |

TOOLS AND TECHNOLOGIES

| Category             | Tools                                            |
| -------------------- | ------------------------------------------------ |
| Programming Language | Python                                           |
| Libraries            | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| Notebook             | Jupyter Notebook                                 |
| NLP Technique        | TF-IDF                                           |
| Visualization        | Heatmaps, Boxplots, Geo Mapping                  |
| IDE                  | VS Code                                          |

KEY VISUAL OUTPUTS

| File                                     | Insight                                        |
| ---------------------------------------- | ---------------------------------------------- |
| `reddit_sentiment_distribution.png`      | Overall sentiment distribution                 |
| `reddit_weekly_sentiment_trend.png`      | Weekly sentiment variation                     |
| `reddit_subreddit_sentiment_boxplot.png` | Sentiment comparison across subreddits         |
| `google_trends_correlation_heatmap.png`  | Correlation between mental health search terms |
| `google_top_states.png`                  | State-wise mental health interest              |

PROJECT STRUCTURE 

mental health/
│
├── final.ipynb
├── reddit_mentalhealth_cleaned.csv
├── google_trends_cleaned.csv
├── geoMap.csv
├── mentalhealth_2018_features_tfidf_256.csv
│
├── reddit_sentiment_distribution.png
├── reddit_weekly_sentiment_trend.png
├── reddit_subreddit_sentiment_boxplot.png
├── google_trends_correlation_heatmap.png
└── google_top_states.png

How to Run the Project:
Step 1 – Install Dependencies - pip install pandas numpy matplotlib seaborn scikit-learn jupyter
Step 2 – Run Notebook - jupyter notebook
Open final.ipynb and run all cells.

Workflow

Load Reddit & Google Trends datasets
Clean & preprocess textual data
Generate TF-IDF features
Perform sentiment analysis
Analyze geographical mental health patterns
Visualize correlations and trends

Author 
DUSHAR 
(INFORMATION TECHNOLOGY AND AI ENGINEER)
NSUT (B.TECH), GEORGIAN COLLEGE , BARRIE , CANADA (POST GRADUATION)





