# Data folder

# Folders

### Source Data

[Kaggle Song Data](https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019?resource=download)

### Folder Structure

- **raw**  
  Original, unmodified data after downloading, scraping, etc.

- **final**  
  Data after all cleaning, processing, and analyzing.

---

# Data Dictionary

| Column       | Type    | Source | Description                                               |
| ------------ | ------- | ------ | --------------------------------------------------------- |
| artist       | Text    | Both   | Song's artist                                             |
| song         | Text    | Both   | Name of the track                                         |
| release_year | Numeric | Both   | Release year of track                                     |
| popularity   | Numeric | Both   | The higher the value, the more popular the song           |
| energy       | Numeric | Both   | Represents a measure of intensity and activity            |
| loudness     | Numeric | Both   | Overall loudness of a track in decibels                   |
| danceability | Numeric | Both   | Value of 0.0 is least danceable and 1.0 is most danceable |
| key          | Numeric | Both   | The key the track is in                                   |
| tempo        | Numeric | Both   | The number of beats per minute                            |
