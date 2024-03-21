# Film-Fortune-Telling

![movie studio](images/Studio%20image.jpeg)


Phase one project: Predicting movie studio success. (project description: https://github.com/Nyabaga/dsc-phase-1-project-v2-4.git)

## Business problem

 > Business Problem : Microsoft wants to start a film company
 
 Microsoft decides to venture into the world of movie production, but they're new to the game. I have been given a task  to figure out what kinds of movies are popular right now. Your job is to dig into the data and give them advice on what types of movies they should focus on making. With my insights, Microsoft can make smart decisions about their film projects and increase their chances of success in the industry.I formulated these three questions to help analyse the data and come up with the required findings.

Which movie genres are the most popular?
What is the runtime distribution?
How production budget affects the returns of the movie?

 
 ## Business Understanding
 As a data scientist delving into the movie industry, it's evident that this field is complex, involving various players and factors shaping a film's success. Crucial aspects include script caliber, celebrity allure, promotional tactics, release timing, and audience genre preferences. Action and adventure flicks usually fare well, whereas specialized genres like documentaries may attract a smaller audience. Our analysis integrates diverse data sources like box office data, social media metrics, and critical reviews, utilizing methodologies such as regression and sentiment analysis to uncover trends. For Microsoft's new movie studio, our aim is to utilize these insights to inform their film production strategies effectively. By grasping the nuances of the industry and employing data-driven approaches, Microsoft can optimize their movie lineup, ensuring greater success and profitability in this competitive arena.
 
 ## Data Understanding
 Our data is stored in a folder named zippedData. The data is sourced from a variety of movie aggregation sites:

1. Box Office Mojo
2. IMDB
3. Rotten Tomatoes
4. TheMovieDB
5. The Numbers

## Results
##### First analysis
From my analys on the movie.info csv file the most common gener is Drama. The geners that were given include:Drama, Comedy, Comedy Drama, Drama Mistery and Suspence, Art House and International|Drama. From this analysis I would advise Microsoft to put more emphasis on Drama and Comedy movies.

![most popular gener](images/Most%20popular%20genre%20.png)

##### Second analysis
The mode runtime is 90 minutes and the frequency of movies within a sample of the data that have a runtime of 90 minutes in 72 movies.
- This analysis shows that most people love watching movies that have a runtime of 90 minutes.
- The graph is also skewed to the right. This shows that as the runtime increases the frequency of the movies decreases. This shows that, people generaly prefer movies with lesser runtime.

![Runtime distribution](images/Runtime%20distribution.png)

##### Third analysis
The correlation coefficient between ROI and Production Budget being approximately -0.048 suggests a very weak negative correlation between the two variables. In other words, changes in production budget do not significantly predict changes in ROI.Overall, while the correlation coefficient indicates a weak negative correlation between ROI and production budget, it's crucial for movie studios to conduct comprehensive analyses considering various factors to make informed decisions regarding budget allocation and maximizing returns.

![ROI vs production budget](images/ROI%20vs%20Production%20budget.png)

Find the correlation of ROI and World wide gross.
![production Budget vs worldwide gross](images/production%20budget%20vs%20worldwide%20gross.png)

Understanding the correlation helps studios allocate their budgets more effectively. If there's a strong positive correlation between production budget and worldwide gross revenue, investing more in production may lead to higher returns. There seems to be a very strong corelation between Production budget and Worldwide Gross Revenue. I would advice Microsoft to invest more on their production budget.

## Conclusion
##### My recommendations are :
1. **Focus on producing Drama and Comedy movie genres:** Since the Drama genre has the highest ratings, it would be wise to start production of movies in that genre. Microsoft can also include the Comedy genre as it is second in popularity.
2. **Runtime:** Microsoft should focus on producing movies with a runtime of 90 minutes.From the graph it is evident that as runtime increases the frequency of movies.
3. **Production budget:** Microsoft should heavily invest in their production budget in order to increase their returns. 
>In conclusion Microsoft should cosider these recommendations when starting their film studio.

## Next Steps
Here are other ideas to explore for future analysis:
>1. **Segmentation**: Microsoft should consider segmenting their movies according to age and gender in order to meet the needs of their audience .
>2. **Include difference in the runtime of movies vs. ratings** :Does the duration of a movie always indicate its quality? This information would help Microsoft grasp how to create their own future "classics" and determine the optimal length for maximizing ratings.
>3. **Strategic Planning:** Armed with the correlation coefficient, studios can develop strategic plans for their future movie productions. They can set budget targets based on revenue expectations and adjust their marketing and distribution strategies accordingly.
## Presentation link
 > **Link:**[presentation link](Film-Fortune-Telling/Film_Fortune_Telling_presentation.pdf)
