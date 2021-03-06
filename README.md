# AniX - Stream Animes

<img style="object-fit: contain; border-radius: 4px; margin-bottom: 16px" src="screenshots/cb.png" alt="banner" height="280">

AniX uses scraped data to allow the users watch, download their favorite animes. The scraping part is managed by python scrapy framework. If you are interested in looking at the backend code, [click here](https://gitlab.com/manikandanraji/anix-backend).

## Features

1. Watch Animes
2. Download Animes
3. Dark/light theme

## Running Locally

- Make sure to setup the [backend](https://gitlab.com/manikandanraji/anix-backend) first

- Create a .env file at the root directory with the following contents:

```bash
# CF stands for cloud function
REACT_APP_CF_ENDPOINT=https://cloud-functions-qem9p2auy.vercel.app/api
REACT_APP_SCRAPER_ENDPOINT=[X] # eg: http://localhost:9080/crawl.json
```

- Run <code>npm i && npm start</code> to start watching animes

## UI

<details>
<summary>View Screenshots</summary>

### Home

<img style="border-radius: 4px;" src="screenshots/home.png" alt="home">

### Anime Page

<img style="border-radius: 4px;" src="screenshots/anime_page.png" alt="anime page">

### Anime Page 2

<img style="border-radius: 4px;" src="screenshots/anime_page2.png" alt="anime page 2">

### Video Player

<img style="border-radius: 4px;" src="screenshots/video_player.png" alt="video player">

</details>

## TODO

1. Queue Videos
2. Create playlists
