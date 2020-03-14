# popular-movies-stage-2
Submission for Udacity Android Nano-Degreee Project - Popular Movies, Stage 2

## Instructions:
Please replace api key for theMovieDB API in [`app/src/main/res/values/apikey.xml`](https://github.com/lowspin/popular-movies-stage-2/blob/master/app/src/main/res/values/apikey.xml)

## Project Overview
In this project, we continue building the movies app in [stage 1](https://github.com/lowspin/popular-movies-stage-1), which will:
- Show a list of available trailers for each movie.
- Launch Youtube link for trailer when clicked.
- Show a list of reviews for each movie if available.
- Allow user to favorite a movie by toggling a favorite icon.
- Allow filtering by favorite movies in the main list, in addition to sorting by most popular and top-rated.
- Save favorite movies in database using Android Architecture Components:
  - Room to read and write to database
  - Live Data to observe changes in database
  - Model View to cache Live Data to minimize database queries, e.g. when rotating.

## Data Source
All movie data used in this project are obatined from [themoviedb.org API](https://www.themoviedb.org/documentation/api)
