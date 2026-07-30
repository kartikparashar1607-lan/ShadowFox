\# X (Twitter) Sentiment Analysis using VADER



\## 📌 Task Description



This project performs sentiment analysis on posts/tweets from X (formerly Twitter) using \*\*VADER\*\* (Valence Aware Dictionary and sEntiment Reasoner) — a rule-based sentiment analysis tool. The goal is to classify posts as positive, negative, or neutral and compare the results with existing human-annotated labels.



\## 📂 Files



\- `X\_Sentiment\_Analysis\_VADER.ipynb` - Complete notebook with data loading, sentiment scoring, visualizations, and conclusions



\## 🛠️ Tools \& Libraries Used



\- Python

\- Pandas, NumPy

\- Matplotlib

\- VADER Sentiment Analyzer

\- WordCloud



\## 🔍 Approach



1\. Loaded and explored the dataset containing tweet text and sentiment labels

2\. Applied VADER's Sentiment Intensity Analyzer to compute compound sentiment scores

3\. Classified posts as positive/negative/neutral based on score thresholds

4\. Visualized sentiment distribution and generated word clouds for each sentiment category

5\. Compared VADER's predictions with the original human-annotated labels



\## 🎯 Key Learnings



\- Applying lexicon-based sentiment analysis on real-world social media text

\- Handling and visualizing sentiment score distributions

\- Understanding the limitations of rule-based sentiment tools on domain-specific/code-mixed text

\- Generating word clouds to identify key themes driving sentiment



\## 📝 Conclusion



The analysis shows a mix of positive and neutral posts dominate the dataset, with VADER's classifications broadly aligning with human-annotated labels. For more nuanced, domain-specific text (e.g., sarcasm, code-mixed language), a fine-tuned transformer-based model would likely perform better than a purely lexicon-based approach.

