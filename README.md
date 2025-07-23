# COGNIFYZ-INTERNSHIP
📊 Cognifyz Data Science Internship – Final Report
Welcome to the official repository of my Data Science Internship at Cognifyz Technologies. This internship focused on data analysis and visualization using real-world datasets. The tasks were categorized into three levels, each designed to progressively enhance analytical thinking, Python proficiency, and data storytelling skills.

🧠 Tools & Libraries Used:
Language: Python 3

IDE: Google Colab

Libraries: pandas, numpy, matplotlib, seaborn, plotly

🔗 Dataset Used:
Zomato Restaurants Dataset
Contains restaurant data such as name, location, cuisine, rating, votes, delivery options, table booking, etc.

📌 Task Overview
✅ Level 1 – Task 1: Data Exploration and preprocessing Analysis

Objective: To understand the structure of the dataset and explore missing values, data types, and aggregate ratings.

Steps:

Loaded dataset using pandas.read_csv() with appropriate encoding.

Checked shape, data types, and null values.

Analyzed Aggregate rating distribution and imbalance.

Outcome:

Dataset: (9551, 21)

Very few missing values (Cuisines column).

Ratings follow a skewed distribution with a majority having a rating of 0.0.

✅ Level 2 – Task 1: Table Booking and Online Delivery Analysis

Objective: To analyze availability and impact of table booking and online delivery options on ratings.

Analysis Performed:

Counted and visualized:

Restaurants with and without table booking

Restaurants with and without online delivery

Compared average ratings based on availability.

Visuals:

Two pie charts and one bar plot.

Insights:

Only 12.1% of restaurants offer table booking, yet these have higher average ratings (~3.44 vs ~2.55).

25.7% offer online delivery; these also show slightly better customer interaction.

✅ Level 3 – Task 2: Customer Preference Analysis

Objective: To identify:

Top 10 most popular cuisines by vote

Top 10 highest-rated cuisines

Approach:

Extracted primary cuisine from the dataset.

Aggregated total votes and average ratings per cuisine.

Sorted and visualized.

Findings:

Most Popular by Votes: North Indian, Cafe, American.

Highest Rated: Sunda, Scottish, Cajun.

Visuals:

Two horizontal bar charts with vote counts and average ratings.

✅Level 3 – Task 3: Data Visualization

Created multiple visualizations using matplotlib and seaborn:

Histogram + KDE for distribution of Aggregate Rating

Bar charts for:

Top 10 cuisines by average rating

Top 10 cities by average rating

Box plot to show relationship between Price range and Aggregate rating

📊 Tools & Libraries Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab

🔍 Key Insights
Most restaurants do not offer table booking or online delivery

Ratings are positively influenced by table booking availability

High price range restaurants tend to have better ratings

Less common cuisines often have higher average ratings

Certain cities consistently offer better-rated restaurants

📁 Folder Structure

📦zomato-data-analysis
 ┣ 📊 Notebooks/
 ┃ ┗ zomato_analysis.ipynb
 ┣ 📈 Visualizations/
 ┃ ┗ [All generated graphs]
 ┣ 📄 zomato.csv
 ┗ 📘 README.md
 
📬 Acknowledgements

Special thanks to Cognifyz Technologies for this valuable internship opportunity and structured learning path.


