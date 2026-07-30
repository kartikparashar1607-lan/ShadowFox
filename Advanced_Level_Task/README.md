\# 📊 Student Performance Dashboard



!\[Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)

!\[Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)

!\[Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)

!\[Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red?logo=streamlit)

!\[Status](https://img.shields.io/badge/Project-Completed-brightgreen)



An interactive data science dashboard that analyzes what actually drives student exam performance — habits, support factors, and machine learning-based predictions across 1,494 students. Built with Python for analysis and deployed as a live Streamlit web app with an HTML/Chart.js frontend.



\---



\## 📌 Project Overview



This project explores which daily habits and support factors (study hours, sleep, social media usage, tutoring, parental education, etc.) most strongly influence a student's exam score. It goes beyond simple EDA by using statistical testing, feature importance ranking (Random Forest), and unsupervised clustering to profile different types of students.



\*\*Key Question:\*\* \*What Actually Drives Exam Scores?\*



\---



\## 🚀 Live Demo



🔗 \*\*\[Student Performance Dashboard](https://student-performance-dashboard-mrftbaaxzxadzsjfxecant.streamlit.app/)\*\*



\---



\## 📊 Dataset



Dataset Used: \*\*student\_performance.csv\*\* (1,494 students)



\### Features

\- student\_id, age, gender

\- study\_hours\_per\_day, sleep\_hours\_per\_day, social\_media\_hours\_per\_day

\- attendance\_pct

\- part\_time\_job, extracurricular, tutoring

\- parental\_education, internet\_access

\- stress\_level, previous\_score, exam\_score (target)



\### Snapshot Stats

| Metric | Value |

|---|---|

| Avg Exam Score | 80.6 |

| Avg Study Hrs/Day | 3.48 |

| Avg Sleep Hrs/Day | 6.78 |

| Best Model R² | 0.73 |



\---



\## 🖼️ Dashboard Preview



\### 1️⃣ Overview \& Correlation Analysis

Key metrics at a glance, correlation matrix, and study hours vs. exam score relationship.



!\[Overview and Correlation](./images/chart1.png)



\### 2️⃣ Daily Habits Impact

How sleep bands and social media time (split by study-hour groups) relate to exam scores.



!\[Daily Habits](./images/chart2.png)



\### 3️⃣ Feature Importance

Random Forest ranking of which factors matter most in predicting exam scores, plus student clustering.



!\[Feature Importance and Clustering](./images/chart3.png)



\---



\## 🚀 Features



\- ✅ Data Cleaning \& Preprocessing

\- ✅ Exploratory Data Analysis (EDA)

\- ✅ Correlation Analysis

\- ✅ Statistical Significance Testing (p-values for tutoring, parental education)

\- ✅ Random Forest Feature Importance Ranking

\- ✅ K-Means Clustering (Student Profiling)

\- ✅ Interactive HTML/Chart.js Dashboard

\- ✅ Live Deployment via Streamlit



\---



\## 🧠 Key Insights



| Rank | Factor | Importance |

|---|---|---|

| 1 | Study hours per day | 53.2% |

| 2 | Previous score | 16.2% |

| 3 | Attendance % | 10.0% |

| 4 | Social media hours/day | 7.4% |

| 5 | Sleep hours/day | 6.0% |

| 6 | Stress level | 2.8% |



\*\*Statistical tests:\*\* Tutoring (p = 0.00001) and Parental Education (p = 0.00029) both show statistically significant effects on exam scores.



\*\*Clustering:\*\* K-Means groups students into 4 natural habit-based profiles (without using exam score), useful for targeted, non-grade-based interventions.



\---



\## 🛠️ Tech Stack



\- Python (Pandas, NumPy, Scikit-learn) — data analysis \& ML (Student\_Performance\_Analysis.ipynb)

\- HTML + Chart.js — interactive dashboard visuals

\- Streamlit — deployment/hosting



\---



\## 📁 Project Structure



Advanced\_Level\_Task/

├── Student\_Performance\_Analysis.ipynb   # EDA, feature importance, clustering

├── student\_performance.csv              # Dataset

├── app.py                               # Streamlit app (embeds dashboard)

├── student\_performance\_dashboard.html   # Chart.js dashboard

├── README.md

└── images/

&#x20;   ├── chart1.png

&#x20;   ├── chart2.png

&#x20;   └── chart3.png



\---



\## ▶️ How to Run Locally



git clone https://github.com/kartikparashar1607-lan/ShadowFox.git

cd ShadowFox/Advanced\_Level\_Task

pip install streamlit

streamlit run app.py



\---



\## 🎯 Results



\- Cleaned and analyzed data for 1,494 students.

\- Identified study hours as the single strongest driver of exam performance (53.2% importance).

\- Confirmed statistically significant impact of tutoring and parental education.

\- Segmented students into 4 distinct habit-based clusters using K-Means.

\- Deployed a fully interactive dashboard for real-time exploration.



\---



\## 🔮 Future Improvements



\- Hyperparameter tuning for the Random Forest model

\- Add more ML models for comparison (XGBoost, Gradient Boosting)

\- Add prediction input form (enter your habits → get predicted score)

\- Docker deployment



\---



\## ⭐ Support



If you found this project useful, consider giving it a ⭐ on GitHub.





