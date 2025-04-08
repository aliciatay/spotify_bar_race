# Spotify Genre Hits Bar Chart Race

This visualization shows the evolution of music genres popularity over time, based on hit songs across different platforms (Spotify, YouTube, TikTok, Apple Music, Sirius XM, Deezer, Amazon, Pandora, and Shazam).

## Features

- Dynamic bar chart race showing top genres for each year
- Smooth animations with transitions between years
- Color-coded genre bars
- Play, pause, and reset controls
- Automatic looping through all years

## Data

The visualization uses data from the `final_df_cleaned.csv` file, which contains information about songs, their genres, and whether they were hits on various platforms. A song is considered a "hit" if it has at least one "True" value in any of the platform hit columns.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- D3.js v7

## How to View

Visit the [GitHub Pages site](https://aliciatay.github.io/spotify_bar_race/) to see the visualization in action.

## Local Development

To run this visualization locally:

1. Clone this repository
2. Open `index.html` in a web browser or use a local server (recommended to avoid CORS issues)

## Credits

This visualization was created for the CS5346 Information Visualization course. 