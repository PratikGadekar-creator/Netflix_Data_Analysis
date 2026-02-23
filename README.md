# Netflix_Data_Analysis
Netflix Data Analysis using Python
📌 Project Overview

This project performs structured Exploratory Data Analysis (EDA) on the Netflix dataset to identify content trends, distribution patterns, and key business insights.
The analysis focuses on understanding the growth of Movies and TV Shows, content ratings, release trends, and country-wise distribution.

🎯 Objectives

Compare Movies vs TV Shows distribution
Analyze content ratings percentage
Study release trends over the years
Understand movie duration distribution
Identify top content-producing countries
Visualize trends using multiple chart types

🛠 Workflow Followed

Data Loading – Imported dataset using Pandas
Data Cleaning – Handled missing values, removed duplicates
Data Understanding – Used head(), info(), describe()
Question Framing – Defined analytical questions
Exploratory Data Analysis (EDA) – Built visualizations using Matplotlib
Report Generation – Saved final charts using plt.savefig()

📊 Key Insights

Movies dominate Netflix's content library compared to TV Shows.
Content production increased significantly after 2015.
Peak additions occurred between 2017–2020.
TV-MA and TV-14 are the most common content ratings.
A small group of countries contributes the majority of content.

🛠 Tech Stack

Python
Pandas
NumPy
Matplotlib
Google Colab

📂 Repository Structure

Netflix-Data-Analysis/
│
├── netflix_analysis.ipynb
├── content_by_year.png
├── movies_vs_tv.png
├── ratings_distribution.png
├── duration_histogram.png
├── README.md
