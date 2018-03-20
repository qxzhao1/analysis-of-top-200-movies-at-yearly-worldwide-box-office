## PART 1 Analysis of Top 200 Movies at Worldwide Box Office from 2000 to 2017

* step 0 web scraping and data cleaning

  1.acquire the data from the box office Mojo 
  
  2.after data cleaning, save it into boxoffice.csv file
  
  3.you can see this process in WEB SCRAPING OF Box Office.ipynb
 
 
* step 1 statistical analysis of top 200 movies at worldwide box office from 2000 to 2017

  1.turn the box office into real dollars instead of nominal dollars.
  
  2.analysis of whether worldwide box office changed over time? Domestic? Overseas?
  
  3.explore the distribution of worldwide box office over time. Is it similar to that of the domestic and the overseas?
  
  4.which movies are included in the top 10 of the worldwide, the domestic and the overseas box office? Is there a large difference?
  
  5.could the title of the movie affect the box office? is there a pattern of naming for the movies with highest box office? or the movies with most succesful box office share same words?
 
 
* step 2 specific analysis of 2017 top 200 movies at worldwide box office

  1.what are the most frequent words in 2017 yearly top 200 movies' names? 
  
  2.is there a pattern of the protion of domestic box office in the top 100 movies? 
  
  3.has the Big Six still ruled the movie market?
  
  4.find domestic movies have higher box office in China instead of in the USA.


* step 3 detailed analysis of movies that have different domestic and Chinese box office 

  1.it is based on 7 movies among 2017 top 200 movies we get from step2.
  
  2.you can this process in Analysis of 7 movies with different domestic and Chinese box office.ipynb.


## PART 2 Analysis about the potential influence features that may account for the difference in Box Office

After finding out those 7 movies that are produced domestically while having higher Chinese Box Office, we focus on finding the reason behind it. Based on common potential possibilities that may influence the Box Office of a specific movies, we decide to focus on director effect, leading cast effect, popularity effect and social media effect. 

### Question:

1. Since social media such as FaceBook and Twitter are becoming more influential to our life, will that affect the Box Office? i.e. If someone gave the negative feedback of a movie, would that make others who see the feedback reluctant to see that movie? Or could these negative ratings account for the decline of the box office?

2. Are those 7 movies have different evaluations from  movie judging websites IMDB and Douban? Could the positive or negative ratings on those two websites indicate the higher or lower Box Office of China?

3. Chinese audiences are huge fans of some stars! It is a common phenomenon that most Chinese audience will watch movies where their idols play a role, though sometimes just a guest appearance. Is that a universal phenomenon in America? Should leading actors with less enormous fan base be responsible for the compartively lower domestic Box Office? Is this also true for directors?

4. Besides, we have special designed plots for director detailed data and it is actually user friendly,i.e. you can actually build  your own "conclusion" by putting different criteria for different directors and then check its relationship with Box Office. 

Curious, huh? Go ahead and check our notebooks!

### Fetching data:
First step is getting needed data from the corresponding websites. Folder named "DATA fetching for different feature studies for those 7 movies" contains notebooks about the methods of fetching each feature data set. There are total three notebooks where the methods of getting actor and director data are in the same notebook basically because the structure of the web pages of the actor data and director data are similar. 

### csv file: 
The output csv files for this part are under the file “CSV file for feature analysis data”. Each feature is a separate file and the file “actordata” and “directordata” are the detailed data of those features.

### Analysis:
The data visualization steps and comments are under file ANALYSIS, we use the regular plots as well as interactive plots because for director analysis and actor analysis, individual differences are huge and can not be modified and therefore, the use of interactive plots is necessary of readers to get a right handle of the data and even making their own inference!

### Conclusion:
After this study, we actually find out that the popularity and social media rating features are not so related to the Box Office while the director and actor effects can not be ignored.  

