# Extrovert-Introvert Profiler

A machine learning project to predict personality type (Extrovert/Introvert) based on behavioral and social habits.

## Dataset

The dataset contains 18,524 records with the following features:

| Feature | Description |
|---------|-------------|
| Time_spent_Alone | Hours spent alone per day |
| Stage_fear | Has stage fear (Yes/No) |
| Social_event_attendance | Number of social events attended (0-10) |
| Going_outside | Frequency of going outside (0-7) |
| Drained_after_socializing | Feels tired after socializing (Yes/No) |
| Friends_circle_size | Number of close friends (0-15) |
| Post_frequency | Social media posting frequency (0-10) |
| Personality | Target variable (Extrovert/Introvert) |

## Project Structure


## EDA Notebook Contents

- **Part A:** Data exploration (shape, types, statistics, missing values)
- **Part B:** Data cleaning (imputation, duplicates, outliers)
- **Part C:** Visualizations with insights

## Key Findings

- Introverts spend more time alone and have smaller friend circles
- Extroverts attend more social events and post more on social media
- Stage fear and feeling drained after socializing are strong indicators of introversion
- Dataset is imbalanced (~74% Extroverts, ~26% Introverts)

## How to Run

1. Open in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KunalPoonia/Introvert-Extrovert-Profiler/blob/main/eda.ipynb)

2. Or run locally:
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook eda.ipynb
