<h1 align="center">:movie_camera: MovieMate :movie_camera:</h1>
A universal desktop app that changes your movie night experience. You feed it your movie files and it does all the :boom: magic :boom:.  
  
![Alt Screenshot](https://github.com/daedlock/MovieMate/raw/master/resources/screenshot.png)
___

### :zap: Idea
Decided to start the project after discussion on reddit https://redd.it/5hq84d
### :wrench: Built With
* React
* Redux
* Webpack
* Electron
* Lots of love :heart:
  
### :package: Features
* Sync it with your movie library (folders, external hdd..etc) 
* Get movies presented as covers with scraped ratings
* Get movie information from imdb, rottentomatoes 
* Get movie reviews and critiques from imdb 
* Watch the trailer 
* Sort movies by genre, rating, year
* Get movie subtitles from opensubtitles, subscene..etc   
   
   
### :rocket: How it Works  
After adding your media sources (files and folders) MovieMate does the following
* Extract movie title from file name
* Scrapes movie information from imdb, rottentomatoes
* Caches the scraped movies in local database


All the above happens in a harmonic unique experience similar to that of xbmc tv app with a much simpler model. The only input required to get started is a list of file names. The app parses the file names and then scrapes all the relevant data for all the movies in the library.

Welcoming feedback and ideas!


#TODO
- [ ] Build Process & CI
- [ ] IMDB Scraper (Cast, Reviews, Rating, Cover Photos, Plotlines, Genre)
- [ ] RottenTomatoes Scraper (Cast, Reviews, Rating, Cover Photos, Plotlines, Genre)
- [ ] OpenSubtitles Scraper (Get subtitles for a movie title, year)
- [ ] Subscene Scraper (Get subtitles for a movie title, year)
- [ ] Data Layer
- [ ] Movie Player
- [ ] RTP Streaming

Roadmap on https://trello.com/b/yhLFm248/moviemate-roadmap

# Development
Development has just started. To run locally
```
git clone https://github.com/daedlock/MovieMate && cd $_
npm install
npm run dev
```

# Contribution
Are always welcome

