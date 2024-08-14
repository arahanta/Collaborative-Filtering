# Book Recommendation System

## Overview

This project aims to develop a book recommendation system using two key approaches: **Popularity-Based Recommendation** and **Collaborative Filtering**. Additionally, the project includes **Exploratory Data Analysis (EDA)** to understand the underlying patterns in the book, user, and rating data. The dataset used for this project consists of books, users, and ratings information.

## Features

   - **Popularity-Based Recommendation**: Recommends books that are popular among users, either by the number of ratings or by average ratings.
   - **Collaborative Filtering**: Provides personalized book recommendations based on user behavior and preferences.
   - **Exploratory Data Analysis (EDA)**: Analyzes and visualizes key insights from the data, including book ratings, user demographics, and rating trends.

## Datasets
### Books Dataset

The books dataset contains information on various books, including:
-  ISBN: Unique identifier for the book.
-  Book-Title: Title of the book.
-  Book-Author: Author of the book.
-  Year-Of-Publication: Year the book was published.
-  Publisher: Publisher of the book.
-  Image-URL-S, Image-URL-M, Image-URL-L: URLs for the book's images in different sizes.

### Users Dataset

The users dataset includes:
    -  User-ID: Unique identifier for the user.
    -  Location: User's location (city, state, country).
    -  Age: Age of the user.

### Ratings Dataset

The ratings dataset provides:
    -  User-ID: Unique identifier for the user.
    -  ISBN: Unique identifier for the book.
    -  Book-Rating: Rating given to the book (range from 0 to 10).

## Installation and Setup

Clone the repository:
```bash
git clone https://github.com/yourusername/book-recommendation-system.git
```

To begin, install the required packages:

```bash
pip install pandas numpy seaborn matplotlib

```
