# Product Review Analysis (NLP Exploration)

## Project Summary
This project explores product reviews using **NLP preprocessing** and text visualization to identify themes associated with positive and negative feedback.

## What I Built
- Text preprocessing pipeline (cleaning, tokenization, stopword handling where applicable)
- Word frequency analysis
- WordCloud comparisons:
  - all reviews
  - positive reviews
  - negative reviews

## Key Results (Observed in Notebook)
- Star rating distribution indicates review imbalance:
  - **5-star:** 7532
  - **1-star:** 2468

## Interpretation & Conclusion
- The dataset contains significantly more **positive (5-star)** than **negative (1-star)** reviews.
- Word frequency and WordCloud views reveal:
  - the most repeated terms in general feedback
  - distinct vocabulary patterns between positive and negative experiences
- Conclusion: The analysis provides a fast, interpretable overview of customer sentiment drivers and highlights themes that can inform product improvements or marketing messages.

## How to Read the Visuals
- **Top word frequency**
  - identifies repeated issues/praises at scale
- **Positive vs Negative WordCloud**
  - highlights contrasting themes:
    - positives often reflect value and satisfaction
    - negatives often reflect defects, usability, or service issues (depending on the dataset)

## Key Visuals
- ![Top Words](images/top_words.png)
- ![WordCloud - All](images/wordcloud_all.png)
- ![WordCloud - Positive](images/wordcloud_positive.png)
- ![WordCloud - Negative](images/wordcloud_negative.png)

## Skills Demonstrated
NLP Preprocessing · Text EDA · Sentiment Theme Discovery · Visualization · Insight Communication
