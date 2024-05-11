# Netflix Content Analysis Project

## Overview

Welcome to the Netflix Content Analysis Project! This project aims to analyze various aspects of Netflix's extensive library, including the growth of movies and TV shows, genre distribution, country of origin, content duration, rating categories, release patterns, director and cast involvement, genre popularity over time, and much more.

## Project Structure

- `data/` https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows:
  - Contains datasets used for analysis.
- `notebooks/`: https://github.com/rajbhuwan1510/NetFlixDataAnalysis/blob/main/Netflix_project.ipynb
  - Jupyter notebooks containing code for data analysis.
- `results/`: Output files, visualizations, and summary reports.

### Data Cleaning

- Checked for missing values and handled them appropriately (dropping rows/columns, imputation).
- Ensured correct data types for each column.
- Identified and handled outliers or anomalies in the data.

### Data Understanding

- Number of rows and columns: [8807,9]
- `data/` https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows:
  - Contains datasets used for analysis.
- `notebooks/`: https://github.com/rajbhuwan1510/NetFlixDataAnalysis/blob/main/Netflix_project.ipynb
  - Jupyter notebooks containing code for data analysis.
- `results/`: Output files, visualizations, and summary reports.

### Data Cleaning

- Checked for missing values and handled them appropriately (dropping rows/columns, imputation).
- Ensured correct data types for each column.
- Identified and handled outliers or anomalies in the data.

### Data Understanding

- Number of rows and columns: [8807,9]
  - Data types :
    - `show_id`         : **object**  *A unique identifier for each title.*
    - `type` :             **object**  *The category of the title, which is either 'Movie' or 'TV Show'.*
    - `title` :            **object**  *The name of the movie or TV show.*
    - `director` :       **object**  *The director(s) of the movie or TV 8show. (Contains null values for some entries, especially TV shows where this information might not be applicable.)
    - `cast`:            **object**  *The list of main actors/actresses in the title. (Some entries might not have this information.)*
    - `country`:         **object**  *The country or countries where the movie or TV show was produced.*
    - `date_added`:      **datetime64[ns]**  *The date the title was added to Netflix.*
    - `release_year`:    **int64**  *The year the movie or TV show was originally released.*
    - `rating`:        **object**  *The age rating of the title.*
    - `duration`:        **object**  *The duration of the title, in minutes for movies and seasons for TV shows.*
    - `listed_in`:       **object**  *The genres the title falls under.*
    - `description`:     **object**  *A brief summary of the title.*
- Summary of central tendency and dispersion for numerical features.
- Distribution of categorical features.

## Data Exploration and Visualization

- Created histograms to visualize the distribution of numerical features.
- Visualized the distribution of categorical features using bar charts or pie charts.
- Used boxplots to compare distributions across different groups or categories.
- Explored relationships between variables using scatter plots or correlation matrices.
- Employed Seaborn for more advanced visualizations like pairplots, heatmaps, etc.

## Insights and Conclusion

- Key findings from the EDA, including patterns or relationships discovered.
- Discussion on the implications of the findings and their relevance.
- Conclusions drawn from the analysis and proposed avenues for further research or analysis.

## Questions Explored

1. Growth of Movies and TV Shows
![CategoryVSyear](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/50c593bd-0c44-475b-aa04-12d3640a543e)

2. Distribution of Genres
![Different GenreDistribution](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/27a8b4f6-c220-430c-94b3-3f2ff5cfc74b)

3. Distribution by Country of Origin


4. Content Duration over Years
![durationOverYear](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/12f28298-fc12-4ea7-a50c-b24f8c355c6a)

5. Distribution by Rating Categories
![Distribution of Content Across Different Rating Categories](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/5ecfddbe-fb5d-4379-b361-301ff02e29ad)

6. Volume of Releases Over Time
7. Content Addition Activity Over Months/Quarters
8. Patterns in Release Dates
9. Frequent Directors and their Content Distribution
10. Frequent Cast Members and their Involvement
11. Changes in Genre Popularity Over Time
![Popularity of Genres Over Time](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/1b3c67f0-0227-4e6d-812d-2a2b8526e526)

12. Relationship Between Content Duration and Rating
![RatingCount](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/f03147db-7e9b-41c3-9c98-93167ad8dc07)


13. Correlation Between Rating and Country of Origin
![countryVgenre](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/cbe9a620-6fc5-4c9a-a1e3-28cb5f9061b6)


14. Director-Genre Associations
![country_genre_visual (2)](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/5dc123b0-9580-43fa-b34c-f8db95bafce4)

15. Cast-Genre Associations
![CastVSgenre](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/96f7d3d8-4021-4e48-9c75-236d476911aa)

16. Co-occurrence of Genres
![relationBetweenGenreandCount (1)](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/b7a8afa5-d7a4-462b-b3ce-000852824260)

![relationBetweenGenereandcount2](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/06cf604a-2cef-4547-9d2a-9bc8e6b0c5bb)


17. Evolution of Content Themes Over Time

18. Comparison Between Original and Licensed Content
![NetflixOriginalVSlicensed](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/552489fa-0ee2-4139-9b62-ea28f19e9913)

19. Changes in Diversity of Content Over Time
![GenreVSratingVScountry](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/328392d2-71f5-4eaf-a671-8f2209f74591)

20. Correlation Between Age of Content and Popularity/Rating
![audienceVSyear](https://github.com/rajbhuwan1510/NetFlixDataAnalysis/assets/92216824/f7256416-a0c8-44e5-b198-42ad66f433b6)


## Technologies Used

- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- itertools
- Statistics
- Jupyter Notebook
