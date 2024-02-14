# Lifestyle and Wellbeing Data Analysis

## Source of Information
For more details about the dataset and survey, please refer to [this source](https://www.kaggle.com/datasets/ydalat/lifestyle-and-wellbeing-data).

## Table of Contents
- [Context of Data](#context-of-data)
- [Our Approach](#our-approach)
- [Issues Along the Way](#issues-along-the-way)
- [Cleaning & Visualizing the Data](#cleaning--visualizing-the-data)

## Context of Data
This project focuses on the analysis of Lifestyle and Wellbeing data. The dataset comprises responses from nearly 16,000 contributors who answered 24 survey questions. These questions cover a range of topics, from the number of places visited to whether contributors donated to their daily step count as a measure of wellbeing (happiness). The survey was conducted from January 2016 to September 2020.

## Our Approach
Our team meticulously examined the dataset to identify potential inferences and trends. After uncovering noteworthy patterns, we formulated a set of questions to explore correlations further. These questions were then assigned to team members for coding, with the primary objective of visualizing each question to ascertain potential correlations.

## Issues Along the Way
During the data cleaning process, we encountered challenges when attempting to visualize specific values with time on the x-axis. A particular row in the 'Timestamp' index returned as an object, leading to visualization issues with our graphs.

## Cleaning & Visualizing the Data
The data cleaning process involved utilizing methods such as mean to compute the averages of survey responses, .groupby to aggregate responses within specific time windows, and .map to convert string column values (e.g., female to 1, male to 2). We imported seaborn to create heatmaps and distributional representations. To address visualization challenges, we opted to drop the problematic row and subsequently removed it from our data source. Standard exploration techniques such as .info, .head/tail, .unique, and more were employed. Seaborn proved essential for generating insights, particularly through heatmaps illustrating correlations across multiple columns in our dataset.
