#  ReactMovieDB Web Application

## Synopsis

Name:  ReactMovieDB

* Simple movie web application with home page, search feature and movie detail page.  
* App uses ReactJS which consumes the "The Movie Database (TMDB)" API. 


Try it out!   
<https://hillc255.github.io/ReactMovieDB/>



<p align="center">
 <kbd><img width="900" height="400" src="readme_asset/moviereactdb.gif"></kbd>
</p>



## Code Description

* ReactMovieDB developed with ReactJS, Node, HTML, and CSS using Visual Studio.


## Motivation

Application is a code-along project in Udemy's Beginner React (2019) "Create a Movie Web App" course taught by Thomas Weibenfalk.


## Installation

1. Clone the repo: git clone https://github.com/hillc255/ReactMovieDB.git
2. Obtain your own API key from "The Movie Database" website and add to config.js
3. Navigate to the folder `cd ./ReactMovieDB`
4. Install all the dependencies: `npm install`
5. Start the server: `npm start`


## Deployment

1. Add your repo name in App.js:  `<BrowserRouter basename="/[repo name]">`
2. Save repo link in package.json "homepage": `"https//[your github account]/.github.io/[ repo name]"` 
3. Save github pages for viewing app:  `npm install --save gh-pages`
4. Create a production build:  `$npm run build`
5. Deploy application:  `$ npm run deploy`


## Features

* Movie home page
* HeroImage header
* Movie images display in responsive grid
* Loader - load more movies
* Search movies
* Scollbar  to view more moview
* Movie detail display including plot, rating, director, budget, actors
* Minimal Design


## Tests

Future consideration

## Contributors

Claudia Hill worked on this project.

## License

Only to be used for educational purposes.

