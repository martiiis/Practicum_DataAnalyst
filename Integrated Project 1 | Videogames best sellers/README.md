# Project description
You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.

In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017.


# Contents
1. Data overview

2. Data preprocessing
 
    * Columns: `name` & `genre`
    * Columns: `year_of_release`
    * Columns: `user_score`, `critic_score`, `rating`
    * Check data Types
    * Calculate total sales 
    
3. Exploratory Analysis
4.Create user profile for each region
5. Hipothesis
6. Conclusions


# Project info & documentation 

**Step 1. Data Overview**

**Step 2. Prepare the data**
- Replace the column names (make them lowercase).
- Convert the data to the required types.
- Describe the columns where the data types have been changed and why.
- If necessary, decide how to deal with missing values:
    - Explain why you filled in the missing values as you did or why you decided to leave them blank.
    - Why do you think the values are missing? Give possible reasons.
    - Pay attention to the abbreviation TBD (to be determined). Specify how you intend to handle such cases.
- Calculate the total sales (the sum of sales in all regions) for each game and put these values in a separate column.

**Step 3. Analyze the data**
* 3.1. Look at how many games were released in different years. Is the data for every period significant?
* 3.2. Look at how sales varied from platform to platform. Choose the platforms with the greatest total sales and build a distribution based on data for each year. 
    * *Find platforms that used to be popular but now have zero sales. How long does it generally take for new platforms to appear and old ones to fade?*
    * *Which platforms are leading in sales? Which ones are growing or shrinking? Select several potentially profitable platforms.*
* 3.3. Working only with relevant data. Filter df from 2014 and on.
    * *Build a box plot for the global sales of all games, broken down by platform. Are the differences in sales significant? What about average sales on various platforms? Describe your findings.*
* 3.4. Take a look at how user and professional reviews affect sales for one popular platform (you choose). Build a scatter plot and calculate the correlation between reviews and sales. Draw conclusions.

**Step 4. Create a user profile for each region**
- For each region (NA, EU, JP), determine:
    - The top five platforms. Describe variations in their market shares from region to region.
    - The top five genres. Explain the difference.
- Do ESRB ratings affect sales in individual regions?

**Step 5. Test the following hypotheses:**
- Average user ratings of the Xbox One and PC platforms are the same.
- Average user ratings for the Action and Sports genres are different.
Set the alpha threshold value yourself.

Explain:
- How you formulated the null and alternative hypotheses
- What significance level you chose to test the hypotheses, and why

**Step 6. Write a general conclusion**
