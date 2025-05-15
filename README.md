# 🎥 Movie_genres_analysis 🎥
## An analysis of movies produced between 1960 and 2015 by their genres

### Project Overview

This project aims to provide insights about the performance of different genre of movies produced over a time span of 55 years (1960 to 2015).  By exploring and analyzing various aspects of the movies data, we seek to understand the trends in the financial performance of different genre of movie and to gain an understanding of the movie industry.

### Data sources
Movie data: The primary dataset used in this project is 'imdb_movies.csv'. This dataset is a 10,866 x 21 dataframe providing details about the movies such as their finances, genres, rating, released year etc.

### Tools
- Jupyter Notebooks
- Python libraries
  - Pandas - For data cleaning adn preparation
  - Matplotlib and Seaborn - For data visualization

### Data Cleaning and Preparation
In the initial step of this project, the data was cleaned and prepared as described below:
1. Data import and inspection
2. Handling missing/null values
3. Data cleaning by identifying and removing duplicates
4. Data formating and preparation

### Exploratory data analysis (EDA)
The following questions were taken into consideration for data exploration:
1. Which genre is the most common?
2. Which genre takes the highest budget?
3. Which genre generates the highest revenue?
4. The most profitable genre?
5. What are the high-rating genres? This was determined by  using a vote_average >= 8 and vote_count > 50
6. Any correlation between the genres attributes?
7. What is the profit trend for the genres over the last 55 years?
   
#### Research hypothesis
1. The best movies according to vote_avg and vote_count will generate a high profit and revenue
2. We expect a positive correlation between the budget invested and the revenue or profit they generate.

### Results/Findings
The analysis result are sumaarized as follows bearing in mind the answers to the questions raised above:
1. The most common genre appears to be drama with 4672 movies.  After this, the next top four genres are comedy, thriller, action, and romance with 3750, 2841, 2339, 1683 movies respectively.
2. The top five genres with the highest budgets are Adventure, Fantasy, Action, Science Fiction, and Family.
3. The top five genres that generated the highest revenue are Adventure, Fantasy, Animation, Action, and Family.
4. In terms of profit generated, adventure generated the most profit with profit above 70 million dollars. This is followed by Fantasy, Animation, Family, and Science Fiction
5. The highest rating genre are documentary and drama, followed by crime.
6. Their was a positive correlation between the profit generated and vote_average. Also, the revenue generated also has a positive correlation with the popularity of genre.
7. Over the last 55 years, Adventure, Fantasy, Family, Action, and Animation has been the consistent moneybag of the movie industry. Genres such as Documentary, Foreign, TV Movie hardly generate any profit.

### Recommendations
The determining factor for high revenue and profit return are budget, popularity, and vote average as these has a positive correlations. Genres with higher vote average generates a higher profit. Similar observation is seen with revenue. Also, some genres interest people more than the other and this affects the profit and revenue returned.
Therefore, the following recommendations are made:
1. Most profitable genre are Adventure, Fantasy, Animation, Action, Science Fiction, and Family.
2. The higher the budget invested, the higher the revenue and the profit generated. Possibly, this will influence the quality of the scripts, planning and design, marketing etc.
3. Investing into genres such as documentary, foreign, and TV movie will require great effort to reap revenue that can nearly match its counterparts.



