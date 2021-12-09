# Phase 1 

**Author**: Jeremias Campos

![Popcorn](https://media.giphy.com/media/6pJNYBYSMFod2/giphy.gif)

## Overview

A one-paragraph overview of the project, including the business problem, data, methods, results and recommendations.

### Business Problem

Microsoft is looking to venture into the multi-billion dollar movie making industry. To aid in the company's goal, I have conducted research by looking into what variables may lead to be a successful movie release.  With the development of their new movie studio, I researched, collected information, and analyzed the recommendations for action steps. 
During my analysis I looked closely at variables such as budget, gross profit (domestic, international, and worldwide), ratings, and more. 

The Factors Include:
* Movie Type/Genre & Gross: What types of movies generated the highest gross?
* Movie Budget & Gross: How does movie budget relate to gross?
* Ratings & Month: How is a movie rating and release month related?


### The Data

**In my analysis, I utilized 3 sources to develop 3 recommendations for the Microsoft team.**

The Movie Database (TMDb): TMDb is a database created for movies and TV shows insights.
* Contains 3387 movies which have details on studio, gross(domestic & foreign) and year.
* For the purpose of the project, I focused mainly on the top 10 movies and genres.

The Numbers is "premier provider of movie industry data and research services.”
* Contains 5782 movies with details including: movie, production budget, gross (domestic & worldwide)
* For the purpose of the project, I conducted research on budget vs. worldwide budget.

Box Office Mojo is an database that collects information on domestic & international movies & tv shows. 
* Contains 26, 517 movies with an average rating of 5.99 out of 10. 
* This dataset included data on original language, title, popularity, release date, title, vote average, and vote count. 
* For the purpose of the project, I focused mainly on the relationship between release month and vote average. 


## Methods

* Data was imported from reputable sources.
* Unneeded data was removed including: columns, null values, commas, $ signs,  
* Throughout the data analysis, visualizations were created to show the correlation and relationship between variables to indicate results of the research.
* Utilizing the methods above resulted in a collection of results to view correlations between variables in the popular movies that had high ratings, gross, budget, and other variables to provide recommendations.


## Results

**The Movie Database (TMDb):**
* Based on the top 10 movies analyzed from 3887,  I’d suggest to focus on fiction movies such as: a sequel to a successful movie series, a modern remade sci-fy movie, a super hero movies especially from Marvel, and a cartoon animation especially from Disney.

**The Numbers:”**
* From the 5782 movies analyzed, there is a ~.74 positive correlation with production budget and worldwide gross, which means this shows that production budget does impact the worldwide gross.

**Box Office Mojo:** 
* There are 7843 movies out of 26k+ that have over a 7.0+ rating with a range of movies from as early as 1930 to 2020.
**Numbers of Movies Released w/ 7+ Rating**
* The top 3 most popular months that movies were released include: January, October, and April.
* The 3 least popular months that movies were released include: June, July, and February.

**Average Rating Per Month**
* The top 3 months with the highest rating was May, June, and January.
* The 3 months with the lowest rating were in: November, April, March.



### Visual 1
![graph1](./images/viz1.png)

## Conclusions

In conclusion, I would recommend that Microsoft consider these recommendations to produce successful movie campaigns

**Production Budget:
* 40,000,000 dollars + which is what the movies in the top 25% use 

**Releasing movie on the months of January, May, and June

**Genre:
* fiction movies: 
    * sequel to a successful movie series, a modern remade sci-fy movie
    * a super hero movies especially from Marvel
    * a cartoon animation especially from Disney.

**Display movie in:
* Theaters
* Partner with online movie apps 
* Netflix
* Hulu
* HBO Max
* Disney Plus

These factors above would be allow Microsoft to have a great start to their venture into the movie production world. As the world continues to change, I would highly suggest partnering with modern applications to increase profit  and the number of individuals watching the movies. In the future, we can continue to collect data on movie applications and continue to experiment with other variables that may affect the production of a successful movie.



## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── student.ipynb                       <- Narrative documentation of analysis in Jupyter notebook
├── DFlatiron_ Movie Industry Analysis & Recommendations.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```