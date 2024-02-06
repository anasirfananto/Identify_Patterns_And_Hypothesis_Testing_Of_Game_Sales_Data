# Identify_Patterns_That_Determine_Whether_A_Game_Can_Be_Said_To_Be_Successful_Or_Not
You work at the online store "Ice" which sells video games from all over the world. Data related to user and expert game reviews , genre, platform (e.g. Xbox or PlayStation), and historical game sales data are available from open sources. You need to identify patterns that determine whether a game can be said to be successful or not. That way, you can find the games with the most potential and plan their advertising campaigns.
In front of you is data from 2016. Let's imagine that it is December 2016 and you are planning a campaign for 2017.
(Right now, the most important thing is for you to get experience working with data. It doesn't matter whether you forecast 2017 sales based on data from 2016 or forecast 2027 sales based on data from 2026.).
This dataset contains abbreviations. ESRB is an abbreviation for Entertainment Software Rating Board, which is an independent regulatory organization that evaluates game content and assigns age ratings such as Teen or Mature.
Instructions for Completing the Project
Stage 1. Open the data file and study its general information
File path:
/datasets/games.csv . Download dataset
Stage 2. Prepare the data
Rename the column (make all lowercase).
Convert the data to the required data type.
Describe the columns whose data types you changed and explain why.
If necessary, determine how you will handle missing values:
Explain the reason why you filled in the missing values ​​the way you did or the reason why you left them blank.
Why do you think these values ​​are being lost? Give possible reasons.
Pay attention to the abbreviation TBD ( to be determined or in Indonesian, "will be determined"). Determine how you will handle such cases.
Calculate total sales (sum of sales across all regions) for each game and enter these values ​​into separate columns.
Stage 3. Analyze the data
Review how many games were released in different years. Is the data in each period significant?
See how sales vary from one platform to another. Choose the platform with the largest total sales and make the distribution based on annual data. Find a platform that was once popular but now doesn't have any sales. How long does it generally take for new platforms to emerge and for old platforms to fade in popularity?
Determine the time period for data collection. To do this, look at your answer to the previous question. The data you take should allow you to build a benchmark for 2017.
Work only with data that you decide is relevant. Ignore data for previous years.
Which platforms have the most sales? Which platforms are growing or shrinking? Choose several platforms that have the potential to generate profits.
Create a boxplot for global sales of all games grouped by platform. Is the difference in sales significant? What about average sales on various platforms? Describe your discovery.
See how user and professional reviews impact sales on one of the popular platforms (of your choosing). Create a scatter plot and calculate the correlation between reviews and sales. Draw conclusions.
Keeping your previous conclusions in mind, compare the sales of the same game on other platforms.
Observe the general distribution of games by genre. What can we conclude regarding the most profitable genres? Can you generalize about high and low selling genres?
Stage 4. Perform user profiling for each region
For each region (NA, EU, JP), specify:
Top 5 platforms. Explain variations in market share from one region to another.
Top 5 genres. Explain the difference.
Does the ESRB rating affect sales in each region?
Stage 5. Test the following hypotheses:
— Average user ratings for Xbox One and PC platforms are the same.
— The average user rating for the Action and Sports genres is different.
Set your own alpha threshold value .
Explain:
— How do you formulate the null hypothesis and alternative hypothesis
— What level of significance you chose to test your hypothesis, and explain why you chose that number
Stage 6. Write down the general conclusion
Format: Complete this assignment in Jupyter Notebook. Enter the programming code in the code cell and the explanatory text in the markdown cell . Apply formatting and add a title.
Data Description
— Name (name)
— Platform 
— Year_of_Release (year of release)
— Genre 
— NA_sales (North American sales in million USD)
— EU_sales (sales in Europe in million USD)
— JP_sales (sales in Japan in million USD)
— Other_sales (sales in other countries in million USD)
— Critic_Score (critic review score, maximum 100)
— User_Score (review score from users, maximum 10)
— Rating (ESRB)
Data for 2016 may be incomplete.
How Will My Project Be Evaluated?
Read the following project assessment criteria carefully before you start work.
Here are the things project reviewers look for when evaluating your project:
How would you describe the problem identified in the data?
How do you prepare a dataset for analysis?
How do you graph a distribution and how do you describe it?
How do you calculate standard variation and variance?
Did you formulate a null hypothesis and an alternative hypothesis?
What method did you apply when testing the hypothesis?
Do you explain the results of your hypothesis test?
Do you follow the project structure and keep your code neat and easy to understand?
What conclusion did you come to?
Do you provide clear and relevant comments at each stage?
The data you take should allow you to establish a benchmark for 2017. What level of significance you chose to test your hypothesis, and explain why you chose that number
