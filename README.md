# EDA - Netflix Shows-Movies Analysis

This project analyzes Netflix’s movie and TV show catalog using Python and Pandas, uncovering trends in release patterns, genres, and content types.

🔍 Key Insights

2018 had the highest number of releases (1,147 titles).

Movies dominate the platform with 6,131 titles, compared to TV shows.

International Movies is the most common genre (2,752 titles).

Custom category column added to group titles into broader categories such as Kids & Family, Comedies, Action & Adventure, etc.

⚙️ Features

Data cleaning and preprocessing.

Yearly trend analysis of releases.

Genre frequency analysis.

Content type distribution (Movies vs TV Shows).

Feature engineering: added a category column for simplified analysis.

📂 Dataset

Name: netflix_titles.csv

Source: Public Netflix dataset from Kaggle.

Size: ~8,800 rows × 12 columns.

Columns:

show_id → Unique identifier for each title

type → Movie or TV Show

title → Name of the content

director → Director(s) of the title

cast → Main cast members

country → Country of origin

date_added → Date when it was added to Netflix

release_year → Year of original release

rating → Content rating (e.g., PG, TV-MA)

duration → Length in minutes or number of seasons

listed_in → Genres/categories

description → Short plot summary

category → Custom column created in this project to classify titles into simplified genre groups based on keywords in listed_in.

🛠 Tech Stack

Python

Pandas

Matplotlib

Seaborn 

RELEASE TREND CHART

<img width="1980" height="1180" alt="image" src="https://github.com/user-attachments/assets/86882c5e-6738-4754-9055-95604b5545d6" />

Chart Description:

The chart above shows the trend of Netflix content releases over the years. It highlights a significant growth in releases during the mid-2010s, peaking in 2018 with over 1,100 titles released. After 2018, there’s a slight decline, possibly due to changes in Netflix’s production strategy and the global pandemic’s impact on content creation.




