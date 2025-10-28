# What Makes a Film Oscar-Worthy?


## Project Overview
This project analyzes what makes a film "Oscar-Worthy" using historical Oscar and IMDb data. The goal is to uncover the common characteristics, such as genre, rating, runtime, and release year, that correlate with Oscar wins.

The project is built in Python, using pandas, numpy, matplotlib, and SQLite. SQLite queries were used to merge IMDb tables with Oscar data, and to calculate summary statistics. Matplotlib was used to generate data visualizations.

## Objectives
- Combine IMDb and Oscar datasets to examine what types of films receive nominations and wins.

- Use SQL queries to calculate trends by year and genre.

- Explore how ratings, runtime, and genre relate to Oscar outcomes.

- Summarize key insights about audience reception and film characteristics.

## Data Description
- IMDb datatset - contains film metadata, release year, genre, runtime, and IMDb user ratings.
- Oscars data - includes Oscar nominees and winners across multiple genres, categories (Actor, Director etc.), and ceremony years.
### Key Variables

| **Variable** | **Description** |
|---------------|-----------------|
| `primaryTitle` | Film title |
| `startYear` | Year of release |
| `runtimeMinutes` | Duration of the film in minutes |
| `genres` | Film genres (e.g., Drama, Action, Biography) |
| `averageRating` | IMDb average user rating |
| `numVotes` | Number of IMDb user votes |
| `oscar_nomination` | Binary flag indicating if the film was nominated |
| `oscar_win` | Binary flag indicating if the film won an Oscar |


## Key Findings 
- Genre was the strongest distinguishing factor. Serious or historical genres converted nominations to wins more often than other genres comedies or action films.

- IMDb rating correlated positively with Oscar recognition; winning films tended to have slightly higher average ratings.

- Runtime showed a mild trend: longer films performed marginally better.

- Nomination count didn’t guarantee wins; quality and tone mattered more than sheer visibility.

## Conclusion 

From nearly 3,200 films analyzed, the data suggest that Oscar success favors:

- Fact-based or emotionally powerful narratives

- Strong audience ratings on IMDb

- Moderate-to-long runtimes

- Dramatic genres with historical or biographical themes
