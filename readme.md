# YouTube Data Analysis Project

This repository contains Python code for analyzing a dataset obtained using the YouTube API. The dataset includes information about video titles, tags, duration, view count, like count, release date, number of days since release, and views per day.



## Dataset

The dataset used in this project was obtained through the YouTube API and is provided in the `youtube_dataset.csv` file. The columns in the dataset are as follows:
- `title`: Video title
- `tags`: Video tags (comma-separated)
- `duration_in_seconds`: Duration of the video in seconds
- `viewCount`: Number of views
- `likeCount`: Number of likes
- `Date of release`: Release date of the video
- `No of days`: Number of days since release
- `Views per day`: Average number of views per day

## Tasks

The following tasks were performed on the dataset:
1. **Word Clouds:**
   - Created word clouds for the most used words in video titles and tags.
2. **Correlation Analysis:**
   - Visualized the correlation between video duration and the number of views and likes.
   - Investigated the correlation between the number of tags and average views per tag.
3. **Most Viewed Videos:**
   - Identified the most viewed videos and extracted the most used tags in those videos.

## Prerequisites

Make sure you have the following installed:
- Python (>=3.6)
- Pandas
- Matplotlib
- Seaborn
- WordCloud

You can install the required packages using the following command:
```bash
pip install pandas matplotlib seaborn wordcloud

