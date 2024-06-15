# Note

If you want to run it locally, then follow these steps.

## Steps :

<!-- eyJhbGciOiJIUzI1NiJ9.eyJhdWQiOiIyZjJmOGI0ODc1YTgwYTE1MjcyNWYxYjY1NjFjZjNjZCIsInN1YiI6IjY2NjFlMzA3NWI0NmNhMzQ4NzIwNzc2YiIsInNjb3BlcyI6WyJhcGlfcmVhZCJdLCJ2ZXJzaW9uIjoxfQ.ky_Ubs4Ql42FClFzKONSN17k4Dhw6UPwZLkhYofQI88 -->

1. Open your terminal and run `git clone git@github.com:ebraj/MovieEBG.git`
2. Once the cloning is completed, open this cloned folder in IDE(Vscode).
3. Create the `.env.local` file in the root directory as you need to provide the TMDB api in order to fetch the movie datas.
4. Inside the `.env.local` file create the variable `REACT_APP_TMDB_KEY=_________________` (Add your own TMDB Api key from [TMDB Website](https://www.themoviedb.org/) by creating an account.)
5. Once all the above steps are done, open your terminal once again and run `npm install` to install the required modules and finally run `npm run start` to see the site live.

# Captured UIs

## Landing Page

![Landing Page](captures/Landingpage.png)

## Single Movie Page

![Single Movie Page](captures/Singlemoviepage.png)

## Trending Page

![Trending Page](captures/Trendingpage.png)

## Discover Page

![Discover Page](captures/Discoverpage.png)

## People Page

![People Page](captures/Peoplepage.png)

## Genres Page

![Genres Page](captures/Genrespage.png)
