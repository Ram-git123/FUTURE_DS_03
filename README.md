# FUTURE_DS_03
"NLP-driven Student Feedback Analysis for Task 3 of the Future Interns Internship. Utilizes VADER and TextBlob to perform sentiment analysis, word cloud visualization, and gap analysis on student reviews."

College Event Feedback Analysis (NLP)

Task Number: 03

*ABOUT THIS PROJECT :*

"This project focuses on analyzing student response data to evaluate university performance and student satisfaction. By leveraging Natural Language Processing (NLP), I transformed raw text reviews into structured insights. The analysis identifies key 'pain points' in the student experience—such as wifi and campus facilities—and tracks satisfaction trends over time to provide data-backed recommendations for university administration."

*📌 Project Overview :*

The objective of this project was to analyze student feedback data to understand the "voice of the student". By applying Natural Language Processing (NLP) techniques, I identified key satisfaction drivers and pinpointed specific areas (like Wifi and Campus facilities) that require administrative attention.

*📊 Visual Discovery :*

<img width="607" height="317" alt="Screenshot 2026-01-02 170954" src="https://github.com/user-attachments/assets/0eee24f3-ea18-41c5-8b3b-426ebf7a7dda" />



*🛠️ Technical Workflow :*

*Data Cleaning:* Used Regex to strip special characters and normalized text for processing.

*Sentiment Scoring:* Implemented both TextBlob and NLTK VADER to categorize feedback into Positive, Neutral, and Negative sentiments.

*Trend Analysis:* Resampled data by month to track how student satisfaction evolved over the academic year.

*Gap Analysis:* Calculated the "performance gap" between individual facilities and the university-wide average score.

*Key Features (Technical Highlights):*

*Multi-Engine Sentiment Analysis:* Implemented both TextBlob for polarity and NLTK VADER for compound sentiment scoring to ensure high accuracy.

*Text Preprocessing:* Built custom cleaning pipelines using Regex to normalize text by removing special characters and noise.

*Time-Series Tracking:* Developed a monthly satisfaction trend analysis to monitor how student sentiment fluctuates throughout the academic year.

*Advanced Visualizations:* Created Word Clouds to identify recurring issues in negative feedback and Correlation Heatmaps to see how specific facility ratings (like Wifi) impact the overall score.

*Performance Gap Analysis:* Automated a comparison between individual facility performance and the university-wide average to highlight areas of underperformance.

*🗝️ Actionable Insights :*

*Pain Point Discovery:* The analysis revealed that students in the 'Negative' category frequently mention "Wifi" and "Slow" connections as primary frustrations.

*Correlation:* A heatmap confirmed a strong correlation between Campus ratings and the Overall Satisfaction score, suggesting campus environment is a top priority for students.

*Executive Summary:* The average satisfaction stands at 4.43 / 5.0 , with CAMPUS being the highest-rated area.

*🚀 How to Run the Analysis:*

Ensure you have the reviews.csv file in the root directory.

*Install dependencies:* pip install pandas seaborn matplotlib textblob nltk wordcloud (everything available within Google colab)

*Run the script:* python students_response_feedback_study.py.



