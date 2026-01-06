**Investigating Netflix Movies: A 1990s Exploratory Analysis**


**Project Overview**

This project revisits and extends an exploratory data analysis of Netflix movie data with a focused lens on the 1990s decade (1990–1999). The objective is to understand how movie durations and genre patterns looked before the rise of streaming-era content, and to identify trends in short-form movies, particularly within the Action genre.
The project has been updated with improved data cleaning, clearer feature definitions, and more structured visual analysis.

**Key Questions**

The analysis seeks to answer the following:
What was the most frequent movie duration in the 1990s?
How common were short movies (less than 90 minutes) during this decade?
How many short Action movies were released in the 1990s?
How does movie duration vary across genres and release years?

**Dataset**
File: netflix_data.csv
Scope: Netflix titles metadata

**Key fields used:**
title
genre
release_year
duration
type

Only movies were included in this analysis; TV shows were excluded.

**Data Preparation**
The following preprocessing steps were performed:
Filtered the dataset to include only movies
Isolated movies released between 1990 and 1999
Converted duration values from strings (e.g., "90 min") to integers
Defined a short movie as one with a duration under 90 minutes
These steps ensured numerical accuracy and consistency in the analysis.

🔍 Exploratory Data Analysis

The EDA includes:

Distribution analysis of movie durations in the 1990s

Identification of the mode (most frequent duration) for the decade

Genre-based segmentation, with a focus on Action movies

A scatter plot visualizing movie duration vs. release year, with genre-based color coding

🎨 Visualization

Movie Duration by Year of Release

X-axis: Release Year

Y-axis: Duration (minutes)

Colors indicate genre categories (Children, Documentaries, Stand-Up, Other)

This visualization highlights long-term duration trends and the emergence of shorter formats in specific genres.

📊 Key Results

Most frequent movie duration in the 1990s: stored as duration

Number of short Action movies in the 1990s: stored as short_movie_count

These values summarize the core findings and serve as reference points for further exploration.

🛠️ Tools & Technologies

Python

pandas

matplotlib

Jupyter Notebook

📁 Project Structure
