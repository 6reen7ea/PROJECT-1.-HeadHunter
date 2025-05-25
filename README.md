# Job Market Analysis (Russia, HeadHunter.ru)

## About the project  
This project was developed as part of a data science bootcamp based in Russia. The main objective was to analyze real-world job listings on the HeadHunter.ru platform (the largest job board in Russia) to identify hiring trends, required skills, and salary ranges for Data Science and IT-related jobs in Moscow.

## My role  
- Collected data using the HeadHunter public API  
- Performed preprocessing and feature extraction from text data  
- Created visualizations to analyze salary distributions, word frequencies, and skill demand  
- Applied TF-IDF vectorization to extract meaningful keywords from job descriptions

## Dataset  
The dataset includes over 4,000 job postings with details such as:
- Job title and category  
- Required experience level  
- Salary (min, max, currency)  
- Description text  
- Employer and location metadata  

## Key insights  
- Data Science jobs in Moscow showed salary variation from ~$500/month to $5,000/month  
- High-paying jobs were correlated with keywords like `Python`, `ML`, `SQL`, and `Deep Learning`  
- Junior-level roles rarely mentioned tools like Docker or Airflow, suggesting those are senior-skewed skills  
- TF-IDF analysis helped distinguish common vs. high-impact terms in job postings

## Tools and technologies  
- Data analysis: `pandas`, `numpy`  
- Visualization: `matplotlib`, `seaborn`, `wordcloud`  
- NLP & Feature Engineering: `nltk`, `sklearn`, `TF-IDF`  
- Environment: Jupyter Notebook

## What I learned  
- How to work with a real-world API to collect structured data  
- How to clean and analyze unstructured text using TF-IDF  
- Practical use of WordClouds and barplots to communicate insights  
- Gained experience building a full exploratory analysis pipeline from scratch

## Language note  
The original notebook and comments are in Russian, as this was a Russian-language bootcamp.


