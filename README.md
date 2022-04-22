# Movies-Metadata
This project contains two parts: the first part is the cleaning data set with Python, and the second part is the analysis data with Tableau.
[TABLEAU PROJECT](https://public.tableau.com/app/profile/kristina.klimenchuk/viz/TheMoviesDataset/TheMoviesDataset)

## Context
This data set contains metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts, and vote averages. This dataset also has files containing 26 million ratings from 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.

## Goal
The final data should be clean and have all the necessary information to answer the main question:
__"What are the main features differences between the top 100 movies from other remaining profitable movies released between 2000 and 2017, with a minimum profit of 40%?'__

## Summarize the cleaning process
The data set had __45463 rows and 24 columns__; after cleaning, it is __5129 rows and 12 columns.__

It was a routine cleaning: checking the df information and converting the columns' values into the correct format. But without putting too much time, because Tableau can handle it very well.

All unneeded columns were removed. In the release_date columns, we changed centuries; if the year was after 2017, it was clear that it was the wrong year and had to be changed into 19' century.

Columns genres and production_companies contain multiple variables, which lead to overlapping for this analysis. The first genre and production company were extracted and put into individuals columns. 

The original data set had a "budget" and "revenue" columns but not a profit and profit ratio. 

## Tableau Analysis
<img width="1398" alt="image" src="https://user-images.githubusercontent.com/84743536/164616325-eecb9146-d31a-4c95-b1bc-4df7f3b9af3f.png">
<img width="1397" alt="image" src="https://user-images.githubusercontent.com/84743536/164616379-ac646e66-b149-4156-88d8-7a244e411f85.png">
<img width="1395" alt="image" src="https://user-images.githubusercontent.com/84743536/164616427-d600ac46-ce86-4a66-9574-8616a660ee33.png">
<img width="1391" alt="image" src="https://user-images.githubusercontent.com/84743536/164616469-075efd9e-892c-4984-bf40-28794b76add7.png">
<img width="1394" alt="image" src="https://user-images.githubusercontent.com/84743536/164616502-44b45189-a87d-4ce9-a0c2-9d30e88cfb2d.png">
