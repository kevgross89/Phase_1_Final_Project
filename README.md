![film production](./Images/Film%20Header.jpeg)

# Microsoft Studios Film Recommendations

Author: Kevin Gross

## Project Overview

This project analyzes movie studio data to better understand what types of movies generate a larger domestic gross at the box office. The analysis below shows that domestic box office revenues can be linked to specific genres, movie runtimes, and the time of year the movie is released. This information is intended for the head of Microsoft Studios so they can help decide what type of films to create.

### Business Problem

![film](./Images/Film%20Production.jpg)

Microsoft is seeing all the big companies create original video content and have decided that this is a revenue stream that they want to attempt to tap into. Their first thought is to create a new movie studio, but they do not know anything about creating movies. The information below explores what types of films are doing best at the box office and translates those findings into actionable insights that the head of Microsoft Studios can use to help decide what type of films to create.

### The Data

This analysis looks at a few different data sets:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [TheMovieDB](https://www.themoviedb.org/)

### Methods

This project uses descriptive analysis to help formulate 3 concrete business recommendations for the head of Microsoft's new movie studio. Since all of the data contained information from different time periods, this analysis focuses on when all of the datasets overlap, which is from 2010 to 2018.

### Results

From 2010 to 2018, movies that grossed over $25M at the domestic box office tended to be either Comedy, Drama, Action, or Adventure films.

![Top_Gross_Movies_By_Genre](https://user-images.githubusercontent.com/100182035/173442880-b5f74c7a-9a89-496e-8982-2e02383c6a02.png)

Movies that were 120 to 170 minutes long tended to have a higher domestic movie gross.

![Avg_Dom_Gross_By_Runtime](https://user-images.githubusercontent.com/100182035/173442921-5ece7200-9cbb-458d-8278-18375999acc7.png)

Movies that were released in May, June, July or December had the highest average domestic gross.

![Avg_Dom_Gross_By_Month](https://user-images.githubusercontent.com/100182035/173442932-1370558e-e588-453a-882d-60c11c2fca5a.png)

## Conclusions

This analysis leads to three recommedations for Microsoft to keep in mind while launching their new movie studio:

* Microsoft Studios should produce movies that are in the Comedy, Drama, Action, or Adventure genres.
* Microsoft Studios should aim to produce movies that are 120 to 170 minutes long.
* Microsoft Studios should release movies in May, June, July or December.

### Next Steps

Further analysis could yield additional insights to help guide Microsoft as it starts its new movie studio:

* Look at production budgets for each film and see what type of genre has the best return on investment based on the movie gross.
* Look at the marketing budgets for each film and see what type of advertising each film did. Options could include out of home, linear TV advertising, digital advertising, custom content, etc.
* The movie distribution landscape is rapidly changing as films are no longer going to theaters and then to home entertainment 90 days later. Although there would be limited data available, we could attempt to see what type of distribution model grosses the most amount of dollars (box office performance + home entertainment sales).
* We could also look to analyze the number of movies that were released on the same weekend and see how that affects box office performance as well as long term movie performance.

## For More Information

See the full analysis in the [Jupyter Notebook](https://github.com/kevgross89/Phase_1_Final_Project/blob/master/dsc-phase1-project.ipynb) or review this [presentation](https://github.com/kevgross89/Phase_1_Final_Project/blob/master/presentation.pdf).

For additional information, please contact Kevin Gross at kevgross89@gmail.com

![microsoft](./Images/Microsoft.png)

## Repository Structure
├── Data

├── Images

├── README.md

├── presentation.pdf

└── Phase_1_Final_Project.ipynb
