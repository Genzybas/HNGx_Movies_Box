# HNGX-stage-two

## Moviebox

### 🎯 Objective:
Create a movie discovery web application that allows users to search for movies, view details about them, and save their favorite movies. You’ll be consuming data from the TMDB API.

### ✍ Requirements
1. User Interface:
Create a responsive and visually appealing user interface for the application. Here's the link to the design you're expected to replicate: https://www.figma.com/file/tVfgoNfhYkQaUkh8LGqRab/MovieBox-(Community)?type=design&node-id=1220-324&mode=design&t=6998DWtjQrxz8mOf-0
You should list the top 10 movies on the homepage.
They should be displayed in a grid layout with their movie posters.
The Card component should display the movie title and release date.
card - [data-testid: movie-card]
movie poster - [data-testid: movie-poster]
movie title - [data-testid: movie-title]
movie release date - [data-testid: movie-release-date]
2. Movie Search:
Implement a search feature that allows users to search for movies by title.
Display search results, including movie posters, titles, and release dates.
Show a loading indicator while fetching search results.
3. Movie Details:
When i go to to /movies/:id route (where :id is the imdb_id), I should see the movie details page.
I should see
title - [data-testid: movie-title]
release date (in UTC) - [data-testid: movie-release-date]
runtime (in minutes) - [data-testid: movie-runtime]
overview - [data-testid: movie-overview]
API Integration:
Consume the TMDB API to fetch movie data.
Use the following API endpoints:
Fetch movie details by ID: https://api.themoviedb.org/3/movie/{movie_id}
Error Handling:
Implement error handling to display meaningful error messages to users in case of API failures or other issues.


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://facebook.github.com/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.com/create-react-app/docs/running-tests) for more information.

### `npm run app`

Builds the app for production to the `app` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.


Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.com/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https:/facebook.github.com/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).


### Deployment

 [https://github.io/create-react-app/docs/deployment](https://facebook.github.com/create-react-app/docs/deployment)

### `npm run build` 

 [https://github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.com/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
