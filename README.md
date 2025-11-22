#Customer Review Intelligence System (AI + NLP Project)
This project analyzes mobile app customer reviews using AI-powered sentiment analysis and NLP-based theme extraction.
It identifies customer pain points, trends in sentiment over time, and summarizes key feedback themes.
A Tableau dashboard presents the insights visually and interactively.
📌 1. Project Overview
Modern apps receive thousands of user reviews. Manually analyzing them is slow and inaccurate.
This project solves that problem using:
AI (Groq Llama model) for sentiment classification
NLP theme extraction for identifying complaint categories
Tableau for creating a clean dashboard
Python for data processing
The result: a complete Customer Review Intelligence System that helps understand what users love and hate.
🧠 2. Key Features
✔ AI-Powered Sentiment Analysis
Classifies each review into Negative / Neutral using Groq Llama 3.1 model.
✔ NLP Theme Extraction
Extracts the Top 5 complaint categories and overall summary.
✔ Trend Analysis Over Time
Visualizes how sentiment changes across app versions/dates.
✔ Interactive Dashboard
Tableau dashboard containing:
Sentiment distribution
Sentiment trend over time
Complaint themes (AI summary)
✔ End-to-End Automation
Python scripts generate all required outputs automatically.
🛠 3. Tech Stack Used
Programming:
Python
Libraries:
Pandas
AI / NLP:
Groq Llama (LLM)
Visualization:
Tableau Public
Tools:
VS Code, CSV dataset, GitHub
📁 4. Project Structure (TEXT FORMAT)
project/
• data/
 – reviews.csv
 – reviews_with_sentiment.csv
 – sentiment_summary.txt
 – topic_summary.txt
• scripts/
 – check_sentiment.py
 – sentiment_summary.py
 – topic_summary.py
• dashboard/
 – Customer_Review_Dashboard.twbx
🔍 5. How the System Works
Step 1 — Data Loading & Cleaning
App review dataset loaded
Only important columns kept: content, score, reviewCreatedVersion, at
Null reviews removed
Step 2 — Sentiment Analysis (AI)
Each review passed to Groq Llama-3.1 model
Classifies as: Negative / Neutral
New column “sentiment” added in CSV
Summary saved as sentiment_summary.txt
Step 3 — Topic Extraction (NLP)
AI extracts:
Top 5 Complaint Themes
Top 5 Positive Themes (if available)
Feature requests
Short summary paragraph
Saved as topic_summary.txt
Step 4 — Visualization (Tableau)
Dashboard includes:
Sentiment Bar Chart
Sentiment Trend Chart
AI Summary (Text Box)
📈 6. Dashboard Highlights
✔ Sentiment Distribution:
Shows count of Negative and Neutral reviews.
✔ Trend Over Time:
Shows how sentiment changes across dates.
✔ AI Summary Box:
Displays top customer complaint themes and overall insight summary.
📝 7. Output Files
This project generates the following final outputs:
reviews_with_sentiment.csv → Data with sentiment
sentiment_summary.txt → Sentiment distribution summary
topic_summary.txt → AI complaint/theme extraction
Customer_Review_Dashboard.twbx → Tableau interactive dashboard
🎯 8. Key Insights (Example)
Top 5 Complaint Themes:
App crashing & freezing
Premium pricing frustration
Missing features in free version
Poor user experience
Difficult login & setup process
Sentiment Breakdown:
Negative reviews dominate overall feedback
Very few positive reviews in the sample
Overall Observation:
Users want stability, more features, and smoother experience.
🚀 9. How to Run This Project
Install required library:
pip install groq
Add your Groq API key in the script
Run: check_sentiment.py
Run: topic_summary.py
Open Tableau → load dashboard file
🧾 10. Future Improvements
Add topic clustering using ML
Add word clouds for visual NLP
Integrate dashboard auto-refresh
Add positive theme extraction
🙌 11. Author
Akash Yadav
Aspirant Data Analyst | Python | AI | Tableau
GitHub: github.com/akxyverse
LinkedIn: linkedin.com/in/akash-yadav
