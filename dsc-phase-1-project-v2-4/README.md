## Questions to answer

1. Which genre is the best performing?<br>
2. How much money do you need to spend to make a high earning movie? Does the money spent in production influence the profits realized?<br>
3. What is the optimum length of a movie?<br>
4. When is the best time of year to release a movie?<br>

## DATA DESCRIPTION<br>

Datasets used in this project were extracted from the following sites:<br>

1. Box Office Mojo<br>
2. IMDB<br>
3. Rotten Tomatoes<br>
4. TheMovieDB<br>
5. The Numbers<br>
<br>
Because it was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that I opened using pd.read_csv, while the data from IMDB is located in a SQLite database.<br>

## ACCESSING INFORMATION AND CLEANING DATA<br>
In this section, I am finding out more information about the datasets, including whether or not they have null values, duplicates, etc.<br>

## MERGING DATASETS<br>
Merging datasets is the process of bringing two datasets together into one, and aligning the rows based on common attributes or columns. In this case, df_gross and df_movieinfo share a common column "studio". I merged the 2 datasets into one (df_mydata) then merged that with df_budgets. However, in the latter case, the shared attribute had a different column name so I renamed one to match the other. This will be explored when merging the last datasets.<br>

## EXPLORATORY DATA ANALYSIS (EDA)
In this section, I will answer ALL the questions listed on my objectives. There are bits and pieces of data cleaning processes that I included whenever I encountered an error/blocker.