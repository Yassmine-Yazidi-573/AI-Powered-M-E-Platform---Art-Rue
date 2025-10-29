# AI-Powered-M&E-Platform-Art-Rue
# Monitoring & Evaluation Data Tools

This project is a **Streamlit-based dashboard** for data-driven monitoring and evaluation, featuring multiple tools for analyzing feedback and candidate data.

## Features:

1. **Feedback Sentiment Analysis = FSA**
   - Preprocesses text by removing stopwords and non-alphabetic characters.
   - Uses TF-IDF vectorization and Logistic Regression to classify feedback as positive or negative.
   - Visualizes sentiment distribution with pie charts.

2. **Funnel Chart Generation**
   - Visualizes candidate progress through stages (Total  Candidates → Preselected → Selected) by region of origin and residence.
   - Generates interactive funnel charts using Plotly.

3. **Migration Pattern Analysis**
   - Creates heatmaps of candidate movement between regions.
   - Handles missing or unspecified data separately for clarity.

4. **Word Cloud Generator**
   - Generates word clouds from a list of words for qualitative analysis.
   - Visualizes the most frequent terms in uploaded datasets.

## Improvements to be considered:
   -Working on a multiclass classification model instead of a simple Binary one: Adding "Neutral" as a third class in FSA
   /Adding more charts/Visuals Options
   
## Notes:
   - Data used to train and test the model is synthetic data and not the Organization's original data! 

