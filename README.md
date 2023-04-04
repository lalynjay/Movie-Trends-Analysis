

# Analysis of Current Trends in the Movie Industry

### Lynn Anderson


## Overview


Microsoft wants to expand their offerings and begin producing films. However, the company doesn't know where to start- they need to know what types of films are most successful, in order to know where to focus their efforts and investments. The purpose of this project was to use exploratory data analysis to determine some characteristics of films that were most successful. I chose return on investment as the metric for success because other metrics (for example net profit, ratings, or popularity) do not accurately portray to what degree that film was financially beneficial to the company. As a start to help Microsoft with their decision regarding what types of films to produce, I used exploratory data analysis to determine what size production budgets, which genres, and what directors are associated with films that have a high return on investment.  Based on the results of the analysis, my reccomendations are to produce more films with a modest budget, to emphasize producing content belonging to the most successful genres, and to recruit directors who have a reputation for producing successful films. 

## Business Problem:

Microsoft wants to enter the film industry and start producing original video content, and have decided to create a new movie studio. However, the company doesn't know much about creating movies. As a start, they need to know what types of films are are most profitable and popular, so they spend their time and budget wisely. To ensure their success in the industry, they will need to produce films that consistently provide a substantial return on their investment. By analyzing trends in what types of movies have been most successful, we can gain insights into type of films to create and how much financial investment is appropriate. 


## Data Understanding

Exploratory data analysis was used to identify the genres, directors, and production budgets that were associated with successful films. The databases used were sourced from The Numbers (which contains 5,782 records for top permorming movies based on the domestic and worldwide box office), and from the IMDB database (which contains information for over 80,000 movies). After combining 4 different databases, I had 3,181 records from 2,123 different movies, representing 22 genres and 2,404 different directors. 


## Results

The Horror and Mystery genres are clear winners, with Thriller a not so close third. These 7 genres represent the most successful third of all genres from the dataset.

![top_genres](https://github.com/lalynjay/Movie-Trends-Analysis/blob/main/images/genres.png)

Chris Lofing Travis Cluff, Sébastien Lifshitz, Adnan A. Shaikh, Chad Zuver, and Chris Stokes have experience with producing very successful films. There is a significant drop between the directors with the 7th and 8th highest ROI, as Chris Stokes has a 30% higher ROI than the director with the 8th highest, hence the cutoff in this visualization.

![top_directors](https://github.com/lalynjay/Movie-Trends-Analysis/blob/main/images/directors.png)

Production budget had a negative correlation with ROI. Films with the highest ROI had a relatively low budget.

![budget_roi](https://github.com/lalynjay/Movie-Trends-Analysis/blob/main/images/roi_1.png)


## Conclusions

Based on the results of the analysis, my recommendations are to:

1. Produce more films with a relatively low budget, rather than pouring a substantial amount of financial resources into a single film. 


2. Emphasize producing content belonging to the most successful genres- specifically Horror, Mystery and Thriller. Also include Sport, Biography, Fantasy and Romance. 


3. Recruit directors who have a reputation for producing highly successful films. 


## Next steps and further research

Further research should be done to identify which studios and cast members are associated with the films having the highest ROI. It should also be determined if there is a relationship between ratings and ROI. Are highly rated films also very successful? Or is the audience drawn in by initial impressions such as the genre, director, and film crew, and are ratings not necessarily associated with success?
 

## For More Information

See the full analysis in the [Jupyter Notebook](https://github.com/lalynjay/Movie-Trends-Analysis/blob/main/Movie_Trends_Analysis.ipynb) or review [this presentation](https://github.com/lalynjay/Movie-Trends-Analysis/blob/main/Presentation.pdf)

For additional info, contact Lynn Anderson at lalynjay@gmail.com
 
## Repository Structure

├── data

├── images

├── README.md

├── Presentation.pdf

└── Movie_Trends_Analysis.ipynb
