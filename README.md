# Pay the Witcher in minted coin!

![](images/Witcher.jpg)

  In the first analysis project I will take a look at the dataset provided, try to identify the most interesting values among it and build a plots according to them so we can visualize the information easily and come up with some conclusions.

_Note: Do you know what are similar between data scientist and witcher? - They change eyes color during the work._

During general data analysis process I using basic data analysis technique with NumPy, Pandas, Seaborn, Matplotlib.
What should I do:
1. Questions - find and answering few questions which containt intresting and clearly task.
2. Data Wrangling - make it clear for work, easy to read for the user.
3. Exploratory Data Analysis - research of useful problem  and dependencies between data.
4. Drawing Conclusion

## Part 1. Work with dataset.
<details><summary><span style="font-size:18pt; font-weight:bold"> I'm only at the beginning of the journey into a fascinating world of Data Science. The work with dataset is the first location on the way.</span><br></summary>
  
In this project, I was given multiple datasets from:
* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB.org
  
_Note: Files for project: 
 * ./data/tmdb.movies.csv
 * ./data/imdb.title.crew.csv
 * ./data/tn.movie_budgets.csv
 * ./data/imdb.title.ratings.csv
 * ./data/imdb.name.basics.csv
 * ./data/imdb.title.principals.csv
 * ./data/imdb.title.akas.csv
 * ./data/bom.movie_gross.csv
 * ./data/imdb.title.basics.csv
 * ./data/rt.reviews.tsv
 * ./data/rt.movie_info.tsv
 _

How I converted this files for work, I pushed into **Reading information.ipynb**.
 
All website from a list contain serves as an online databases of world cinema. This websites contains a large number of public data on films such as the title of the film, the year of release of the film, the genre of the film, the audience, the rating of critics, the duration of the film, the summary of the film, actors, directors and much more.
  
Faced with the large amount of data available on this dataset, I realize that I can't clearly connected this information from different sources. [Here](https://developers.themoviedb.org/3/genres) I read all information from the files and add decryption to the fields using APIs. For my work I used sqlite3, pandas and glob libraries. After I convert dataset to convenient storage, I can continue to work with.
  
Go to the next step for I have been thinking of several solutions to fix this dataset problem with missing values as follows:
1. Delete the line with the missing values
2. Fill empty fields with specific values
3. Fill empty fields with calculations (if it posible)

All my work how I clean and check my dataset, I push into **Studing and clearing.ipynb**.
</details>

## Part 2. Questions research.
<details><summary><span style="font-size:18pt; font-weight:bold"> Our data set contains plentiful information, in the project I decided to focus on finding properties are associated with successful movies. </span><br></summary>


What defines popular cinema primarily? It is first of all popularity and profit. So, we have a questions:
1. Popularity over years 
2. The distribution of profit in different popularity levels 
3. The distribution of profit in different score rating levels
</details> 

## Part 3. Coding

**Popularity**
First I explored the movie popularity trend over years, from 1930 to 2020. 
How you can see I computed the mean of popularity in each year, and then plotted line chart to show the trend. Since the popularity has no upper bound, in case the mean of popularity was affected by the higher rating, I also computed the median for analyzing this question.
We can see that the trend of popularity mean is upward year to year, but it also mean - information about new films goes faster on the Internet and is easier to evaluate by active users. We need more research.
** **
## Final Thoughts

## For Future.
Few remarks for me for the future:
* Update all information using API or/and WebScraping (all sites have a good API and good custom serviсe).
* Use SQLite database for full service of data set.


