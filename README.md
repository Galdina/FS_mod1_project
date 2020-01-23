# Toss A Coin To Your Witcher

![](images/Witcher.jpg)

  In the first analysis project I will take a look at the dataset provided, try to identify the most interesting values among it and build a plots according to them so we can visualize the information easily and come up with some conclusions.

_Note: Do you know what are similar between data scientist and witcher? - They change eyes color during the work._

During general data analysis process I using basic data analysis technique with NumPy, Pandas, Seaborn, Matplotlib.
What should I do:
1. Questions - find and answering few questions which containt intresting and clearly task.
2. Data Wrangling - make it clear for work, easy to read for the user.
3. Exploratory Data Analysis - research of useful problem  and dependencies between data.
4. Drawing Conclusion

## Navigation
-------------------
My project uses the following files included in this repository:

# Preparatino work:
<details><summary><span style="font-size:18pt; font-weight:bold"><b>Reading information.ipynb</b></span><br></summary>
I'm only at the beginning of the journey into a fascinating world of Data Science. The work with dataset is the first location on the way.

In this project, I was given multiple datasets from:
* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB.org

All website from a list contain serves as an online databases of world cinema. This websites contains a large number of public data on films such as the title of the film, the year of release of the film, the genre of the film, the audience, the rating of critics, the duration of the film, the summary of the film, actors, directors and much more.
  
</details>  
<details><summary><span style="font-size:18pt; font-weight:bold"><b>Studing and clearing.ipynb</b></span><br></summary>
Faced with the large amount of data available on this dataset, I realize that I can't clearly connected this information from different sources. [Here](https://developers.themoviedb.org/3/genres) I read all information from the files and add decryption to the fields using APIs. For my work I used sqlite3, pandas and glob libraries. After I convert dataset to convenient storage, I can continue to work with.
  
Go to the next step for I have been thinking of several solutions to fix this dataset problem with missing values as follows:
1. Delete the line with the missing values
2. Fill empty fields with specific values
3. Fill empty fields with calculations (if it posible)   
</details>  

# Questions research.
Our data set contains plentiful information, in the project I decided to focus on finding properties are associated with successful movies. 

What defines popular cinema primarily? It is first of all popularity and profit. Let's imagen we want to create a super sucgessfull movie. So, we have a questions:
1. Popularity over years: Which genres most popular? 
2. How much we should spend for popularity? 
3. Who can help us with movie creation? 

# Working files:
All my thoughts and progress on the project can be checked on the file <b>Student.ipynb</b>, for closer look:
* <b>Genres.ipynb</b>
   Here I made a research dependence of the popularity of films on their genre and budget.
* <b>Budget.ipynb</b>   
   What’s the budget level movie are associated with movies that have high popularity?
* <b>Studios.ipynb</b>  
   What studios tend to make the most popular movies?
* <b>Show time.ipynb</b>  
   Do we have any correlation between popylarity and runtime of movie?

# Research result.

* presentation.pdf 
   
## Final Thoughts
I did my best at this time. I know my data analysis does not cover a lot of questions and I cannot be proud of absolutely clear data. But now I see where to strive and what to do to improve my knowledges and skills. How important is to write a comment for all parts of your code and read logs.

## For Future.
Few remarks for me for the future:
* Update all information using API or/and WebScraping (all sites have a good API and good custom serviсe).
* Use SQLite database for full service of data set.


