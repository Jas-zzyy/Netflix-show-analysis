# social-media-time-spent.csv

## Introduction
This project involves analyzing the `Average Time Spent By User on Social Media` dataset by importing it into MySQL Workbench. The goal is to explore the data and document any interesting findings.

## Dataset
I chose the `Average Time Spent By User on Social Media` dataset, which contains information about how much time users spend on different social media platforms. The dataset includes columns such as `user_id`, `platform`, `average_time_spent`, and `date`.

## Import Process
1. Downloaded the dataset file `social_media_time_spent.csv`.
2. Created a new database in MySQL Workbench:
   ```sql
   CREATE DATABASE social_media;
   USE social_media;

## I created a table to match the csv structure;
CREATE TABLE time_spent (
  user_id INT PRIMARY KEY,
  platform VARCHAR(255),
  average_time_spent INT,
  date DATE
);
## I then imported the csv file using MYSQL data import feature.

## Difficulties

One difficulty I encountered was ensuring that the `date` format in the CSV was compatible with MySQL’s `DATE` type. I had to clean the data to ensure all dates were in the correct format.

## Interesting Findings

One interesting thing I noticed about the dataset is the significant variation in the average time spent on different platforms. For instance, users spend more time on platforms like Facebook and YouTube compared to newer platforms like TikTok and Snapchat. This data could be used to analyze user behavior and platform engagement trends over time.

### Step 4: Commit and Push to GitHub
1. **Initialize a Local Repository**:
   ```sh
   git init
   git add README.md
   git commit -m "Initial commit with README"



