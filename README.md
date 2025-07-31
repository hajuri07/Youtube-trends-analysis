# youtube-trends-analysis
YouTube Trends Dashboard (Mini Project)
This project analyzes YouTube trending videos from India and USA using real-world data. It involves data cleaning, category mapping, and insightful visualizations to understand video performance, user engagement, and content trends.

📁 Dataset Used
CSV Files: in.csv, us.csv — contain trending video data such as views, likes, comment counts, tags, and publish times.

JSON Files: IN.json, US.json — contain category IDs mapped to readable names.

🔧 Tech Stack
Language: Python 🐍

Libraries: pandas, matplotlib, seaborn, json


✅ Steps Performed
1. Loading and Merging Datasets
Loaded both CSV and JSON files for India and US.

Merged them into one single DataFrame.

2. Data Cleaning
Dropped unnecessary columns and duplicates.

Mapped categoryId to human-readable category using JSON.

Removed missing/null values.

3. Feature Engineering
Calculated an engagement ratio:

engagement_ratio
=
likes
+
comment_count
views
engagement_ratio= 
views
likes+comment_count
​
 
Selected key columns: publish_time, views, likes, comment_count, category_id, and engagement_ratio.

4. Visualization
Top 10 video categories by total views.

Engagement trends over time.

Likes vs Comments scatter to detect engagement.

📌 Key Insights
Certain categories like Entertainment and Music dominated in views.

High engagement ratios are common in News, People & Blogs.

Visual trends help content creators understand what performs best.

💾 Output
Cleaned data saved in: clean_data.csv

Visualizations saved/shown via matplotlib.

🚀 Future Work
Push cleaned data into MySQL/PostgreSQL for scalable querying.

Build a Streamlit dashboard to make trends interactive.

Add NLP analysis on video titles and tags.

