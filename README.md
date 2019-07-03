# Simple Node Imdb Scraper

This is a simple NodeJS IMDB scraper project which scrapes all the movies based on search input and caches results on redis. Uses cheerio for scraping the detail page and uses Imdb API for search. Support movie detail just pass imdb title id. Sorting based on ratings and also limit the number of results for faster response.

##Features

- ES6/ES7 style
- Express
- Cheerio
- Redis caching
- Search/Autocomplete
- Eslint rules
- esm
- Export/Import style

**Clone the Repo**
```
git clone https://github.com/p-rk/imdb-scraper.git
```

## Download Redis

Install Redis & Start Redis Server
```
wget http://download.redis.io/releases/redis-5.0.5.tar.gz
tar xzf redis-5.0.5.tar.gz
cd redis-5.0.5
make
src/redis-server

```

## Installing Dependencies

Go to cloned working directory and run

```
npm install
```

## Development

```
npm run dev
```

## Production

For Running the project in production mode

```
npm run start
```

## Documented

 - By Rama Krishna
