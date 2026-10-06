# FromSoftware / Souls-like Explorer

A command-line Python app for exploring a CSV dataset of FromSoftware and Souls-like games. It displays game information, filters titles by release year or Metacritic score, and calculates summary statistics.

## Features

- Display all games in a readable table
- Filter games by release-year range
- Filter games by minimum Metacritic score
- Show the longest and shortest main-story playtimes
- Show the highest Metacritic score and average scores and playtime
- Read game data from a CSV file

## Requirements

- Python 3.9 or later
- No third-party packages required

## Project structure

```text
fromsoftware-stats/
├── data/
│   └── games.csv
├── src/
│   ├── main.py
└── README.md