# Hva skal vi se

Finds movies on your Norwegian Netflix, Prime Video, Viaplay and HBO Max (data from TMDB / JustWatch).

Live page: https://oleseter-star.github.io/Hva-skal-vi-se/ (GitHub Pages from the `main` branch).

## First run
1. Free TMDB account: https://www.themoviedb.org/signup
2. API key: https://www.themoviedb.org/settings/api (Personal / non-commercial). Copy the "API Key" or the "API Read Access Token".
3. In the app: Settings -> paste the key -> Save & load services.

Everything you save (key, seen list, watchlist, friend data) lives in that browser only and is tied to the page address. It does not sync between devices.

## Movies and series
The **Movies / Series** switch in the header changes Discover, Top 100, Surprise me and search between films and TV series. A series counts as seen, on the watchlist or not interested as a whole (no per-season tracking). Seen/watchlist lists mix both and mark series with "Series". Actors, Directors, Franchises and Friend are movie-only and are hidden in Series mode.

## Letterboxd
Export your data (Settings -> Data -> Export your data), then drop the zip, the unzipped folder or the loose files into **My lists**. It uses watched.csv, ratings.csv and watchlist.csv.
For a friend: ask them to export theirs, then drop it into the **Friend** tab. It uses watchlist.csv, ratings.csv, watched.csv and likes/films.csv.

## Updating the live page
Copy `index.html` into the cloned repo, commit and push to `main`.

## Backup
Settings -> Backup saves your seen, watchlist, not-interested lists, friend data and filter choices to a file (not your TMDB key). Restore it on another device or after clearing browser data. On iPhone the Home Screen app has its own storage, separate from Safari.
