# Video Game Sales Analysis
A capstone project in which a video game's success was analyzed by looking at it's Metacritic scores as well as many other features.
## Summary
In this project the many features of a video game such as Metacritic score, genre, publisher, and year of release were analyzed
to see their affects on global sales. Machine learning was also used in order to create a classifier that could predict
a video game as selling more than 1 million units. The technical aspects of this project was done through jupyter notebooks using Python.

## Steps 
The steps taken to complete this project are as follows:  

1.) [Data Cleaning and Wrangling](https://github.com/tpham222/VideoGameSalesAnalysis/blob/master/1.%20Data%20Cleaning%20and%20Wrangling/Data%20Cleaning%20and%20Wrangling.ipynb) 
- A dataset that came from a kaggle competition was loaded, cleaned, and filtered in order
    to transform it into a state that could be analyzed.  
    
2.) [Data Visualizations and Storytelling](https://github.com/tpham222/VideoGameSalesAnalysis/blob/master/2.%20Data%20Visualizations%20and%20Storytelling/Data%20Story%20-%20Visualizations%20and%20EDA.ipynb)
- After cleaning the dataset, exploratory data analysis was performed in order to find potential
    avenues to explore. The EDA provided the foundation to create a story and visualizations from the data.  
    
3.) [Statistical Inference](https://github.com/tpham222/VideoGameSalesAnalysis/blob/master/3.%20Statistical%20Inferences/Statistical%20Inference.ipynb) 
- Using the results of the EDA, inferences and analysis were performed. Many hypothesis tests were ran and
    correlations were made.  
    
4.) [Machine Learning](https://github.com/tpham222/VideoGameSalesAnalysis/blob/master/4.%20Machine%20Learning/Machine%20Learning%20-%20In%20Depth%20Predictive%20Analysis.ipynb) 
- Linear regression on multiples video games features was performed. Three different classification models was
    also tested on the dataset.  
## Results
The results of this project are presented in both a pdf [Video Game Sales Report](https://github.com/tpham222/VideoGameSalesAnalysis/blob/master/Video%20Game%20Sales%20Report.pdf) and a [slide deck presentation](https://github.com/tpham222/VideoGameSalesAnalysis/blob/master/Video%20Game%20Sales%20Presentation.pptx). Both of these contain many
visualizations as well in-depth analysis of the results. On top of the complete report, there is also a report for each step of this project
which can be found in the "Previous Reports" directory. The jupyter notebook for each step goes into great detail explaining the code as 
well as the technical steps taken to complete this project.
### Summary of results  
It was seen that there was a statistically significant difference between average critic scores and average user scores.
This project focused on only the critic score. There was a linear correlation between a video game's critic score and the log of global
sales. Of the 12 video game genres, shooters had the highest average global sales value. Action games seem to be the most popular video game
genre and accounted for about 20% of the video games in this dataset. It was also seen that there was a strong linear correlation between
the amount of games a publisher produces and the total global sales of that publisher. The best machine learning classifier model
for this dataset was the random forest. The random forest was able to predict a video game as having more than 1 million units sold globally
with an accuracy of 79% and a precision of 73%. 
