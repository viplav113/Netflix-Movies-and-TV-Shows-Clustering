# Project Files Description

**Executable Files:**
- **NETFLIX MOVIES AND TV SHOWS CLUSTERING.ipynb:** Includes all functions required for classification operations.

**Output:**
- Google Colab: All the outputs are visible in the provided Colab notebook.

**Input Files:**
- **NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv:** Input dataset containing information about different shows/movies available on Netflix.

**Data Source:** [Netflix Movies and TV Shows Clustering](https://learn.almabetter.com/courses/take/team-capstone-projects/texts/27395237-netflix-movies-and-tv-shows-clustering)

---

## Introduction

Netflix, the world’s largest on-demand internet streaming media and online DVD movie rental service provider, was founded on August 29, 1997, in Los Gatos, California by Marc and Reed. With 69 million members in over 60 countries enjoying more than 100 million hours of TV shows and movies per day, Netflix is the world’s leading internet entertainment service, offering TV series, documentaries, and feature films across a wide variety of genres and languages. This analysis aims to visualize Netflix content and find similar groups of people.

## Problem Statement

The goal is to find similarity within groups of people to build a movie recommendation system for users. Analyzing a dataset from the Netflix database will explore the characteristics that people share in movies, addressing the common issue of spending more time deciding what to watch than actually watching.

## Data Summary

This dataset comprises TV shows and movies available on Netflix as of 2019, collected from Fixable, a third-party Netflix search engine. It's noteworthy that the number of TV shows on Netflix nearly tripled since 2010 while the number of movies decreased by more than 2,000 titles. Integrating this dataset with other external datasets such as IMDB ratings, Rotten Tomatoes, etc., could yield interesting findings.

- **show_id:** Unique ID for every Movie / TV Show
- **type:** Identifier - A Movie or TV Show
- **title:** Title of the Movie / TV Show
- **director:** Director of the Movie
- **cast:** Actors involved in the movie / show
- **country:** Country where the movie / show was produced
- **date_added:** Date it was added on Netflix
- **release_year:** Actual Release Year of the movie / show
- **rating:** TV Rating of the movie / show
- **duration:** Total Duration - in minutes or number of seasons
- **listed_in:** Genre
- **description:** Summary description

---

## Exploring Solutions

- **Improve rating system:** Utilize star ratings for better decision-making.
- **Separate recently watched:** Hide watched content to streamline selection.
- **Randomize a Movie:** Provide a random selection based on viewing history.
- **Show popular/trending films:** Create a category for trending content.
- **Connect with Friends:** Incorporate friend recommendations.
- **Organize films by mood:** Categorize content by emotional experience.

## Steps Involved

The code for this project is implemented in Python, using various clustering algorithms. The general approach includes:

1. **Data cleaning and pre-processing:** Handling missing and duplicate variables.
2. **Exploratory Data Analysis:** Extracting statistical insights.
3. **Clustering:** Grouping unlabelled data to find similar patterns.

## Conclusion

Tailored recommendations based on movie and TV show information can significantly improve selection times and enhance content satisfaction. Similar models can be developed to provide valuable recommendations in various domains, fostering user engagement and trust in content recommendations.

---
