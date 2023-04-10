# Data-Analysis-Portfolio
This is a personal repository to track my skills and knowledge in analytics
# Project Portfolio

# Tableau Viz
Tableau visualizations: [Tableau visualizations .pdf](https://github.com/EleniV15/Data-Analysis-Portfolio/files/11189989/Tableau.visualizations.pdf)


# 1.Econometrics
# 1st Difference in Difference Analysis in Python (and in R)
   
Code: file:///C:/Users/CH354ZB/OneDrive%20-%20EY/Desktop/pers/Econometrics%20for%20Business%20in%20R%20and%20Python/1.%20Difference-in-Differences/minWAGEanalysis.py
   
Description: Minimum Wages and Employment: A Case Study of the Fast Food Industry in New Jersey and Pennsylvania (1992) in order to estimate if an increase in minimum    wage can cause a decrease in employment 
   
Skills: data cleaning, data analysis, descriptive statistics, Difference-In-Difference.
   
Technology: Python, Pandas, Numpy, statsmodels.api.
   
Results: 1st regression: p value is positive but not statistically significant, 2nd regression: p value is still positive and more statistically significant, 3rd        regression: p value is still positive and more statistically significant. In conlusion there is no clear evidence that the rise in NJ's minimum wage affected the employment of this market. The effect is significant at 10% with the treatment having a positive effect.
   
# 2nd Difference in Difference Analysis in Python (and in R)
   
Code: file:///C:/Users/CH354ZB/OneDrive%20-%20EY/Desktop/pers/Econometrics%20for%20Business%20in%20R%20and%20Python/1.%20Difference-in-Differences/taxsinglemothersDID.py
   
Description: Tax credit on single mothers. Unavailable before 1994. +Placebo test to check if the deviation has started before 1994 (treatment time). If this is true then we are failing our "parallel trends assumptions", which is necessary for a DiD analysis and then the single women in not a good control group
   
Skills: data cleaning, data analysis, descriptive statistics, Difference-In-Difference.
   
Technology: Python, Pandas, Numpy, statsmodels.api.
   
Results: Tax credit had a positive impact on single mothers employment


# Google's Causal Impact in Python (and in R)
Code: file:///C:/Users/CH354ZB/OneDrive%20-%20EY/Desktop/pers/Econometrics%20for%20Business%20in%20R%20and%20Python/2.%20Google_s%20Causal%20Impact/causalimpact.py
   
Description: Impact of Cambridge Analytica scandal in Facebook (META) stock price. Story was broken by major newspapers on March 2018 and on July 2018 there was a major fine. This has major impact on the stock price because if anything, the market cap decreases by five billion.
The focus is really more on the scandal rather than the fine.

Post period or our treatment period: between March and June 2018. During this period, I analyzed what actually happened to Facebook stock price.
   
Skills: data cleaning, data analysis, descriptive statistics, correlation matrix, Causal Impact.
   
Technology: Python, yfinance.
   
Results: The effect of Cambridge Analytica scandal in Facebook (META) stock price starts off by being negative but then really becomes positive.
So there's almost just this initial shock and then it three bounces back.
It is as if we can go to the old saying that all publicity is good publicity.
In conclusion this scandal, had no impact overall. It could have been a shock in the beginning, but that the overall impact was actually positive.


# Granger Causality in Python (and in R)
Code: file:///C:/Users/CH354ZB/OneDrive%20-%20EY/Desktop/pers/Econometrics%20for%20Business%20in%20R%20and%20Python/3.%20Granger%20Causality/Granger%20Causality.py
   
Description: Correlation does not imply causality. Two factors can be interconnected (correlation) but which started first? (causality). To prove there is Causal inference between X and Y, we have to prove that X is a statisticaly significant predictor of Y and that Y is a statisticaly significant predictor of X.
Thurman and Fisher Chicken, Egg and Causality
   
Skills: data cleaning, data analysis, descriptive statistics, correlation matrix, time series, stationarity.
   
Technology: Python, pandas, matplotlib, grangercausalitytests, statsmodel.
   
Results: Up until six periods (years) eggs leads to chicken, but the chicken does not lead to eggs. This tells us that when it comes to the causality bit, it is eggs that does lead to chickens and not the other way around.

# Propensity Score Matching in Python (and in R)
Code: file:///C:/Users/CH354ZB/OneDrive%20-%20EY/Desktop/pers/Econometrics%20for%20Business%20in%20R%20and%20Python/4.%20Propensity%20Score%20Matching/propensity.py
   
Description: In the 1970s there was a training program for disadvantaged workers. When it comes to that selection, they selected the individuals that would be part of the training program.
So there is a selection bias problem.
   
Skills: data cleaning, data analysis, descriptive statistics, propensity score matching.
   
Technology: Python, pandas, numpy, seaborn, scipy, matplotlib, CausalModel, statsmodels.api.
   
Results: Individuals who are being treated, (blue) are far more to the right. This makes sense because it is also more likely that they were selected.
And as a result, the model works in predicting that they would be selected.
On the other hand, in red, the untreated, they are more skewed to the left. 
Focus on ATE (avg treatment effect) it is negative and highly statistically insignificant (pvalue 0.781).
Also huge confidence interval. 



# CHAID in R
   
Description: This was a dataset that has been provided by IBM and has 30 drivers. Understand why people quit.
   
Skills: data cleaning, data analysis, descriptive statistics, CHAID, chi-square test.
   
Technology: R, ggplot, dyplr, modeldata, installr, partykit, caret, tidyr.
   
Results: 1st CHAID model: Overtime can be a very good predictor for why people quit. 
2nd CHAID model: Overtime is the most important than job level, stock option level than job satisfaction.
Marital status got really downgraded the introduction of the second model with the new variables.
3rd CHAID model: Overtime is the most important, then job level, years at company.

# 2.Data Analytics
# Law of Large Numbers
Code: file:///C:/Users/CH354ZB/OneDrive%20-%20EY/Desktop/pers/intro%20to%20data%20science/python%20programming%20course/LawOfLargeNumbers.py
Description: Using the normal distribution to check if the law of large numbers actually holds true.
   
Skills: Law of Large Numbers analysis
   
Technology: Python, Numpy
   
Results: By increasing the sample size we're getting closer and closer and closer to the expected value of 68.2%.

# Financial Statement Analysis
Code: file:///C:/Users/CH354ZB/OneDrive%20-%20EY/Desktop/pers/intro%20to%20data%20science/python%20programming%20course/financial_statement_analysis.py
Description: Analyze financial statement. Calculate the financial metrics: profit for each month, profit after tax for each month, Profit margin for each month, good months, bad months, the best month, the worst month
   
Skills: Financial Statement Analysis
   
Technology: Python, Numpy
   
Results: [.....], the best month = December , the worst month = March


# Basketball players analysis
Code: file:///C:/Users/CH354ZB/OneDrive%20-%20EY/Desktop/pers/intro%20to%20data%20science/python%20programming%20course/basket.py
Description: Investigate the trends of basketball game statistics.
   
Skills: data cleaning, data analysis
   
Technology: Python, Numpy, pandas, matplotlib 

Results: Points by player: ![PointsByPlayer](https://user-images.githubusercontent.com/130169752/230868359-5f36679e-9663-4725-b0b4-96e09b72fbb4.png)
         Points minus freethrows by fieldgoals:![points_minus_freethrows_by_fieldgoals](https://user-images.githubusercontent.com/130169752/230868491-108aefa2-1dce-4cb2-9ded-163fb6487482.png)
         Salaries by players:![salaries_by_player](https://user-images.githubusercontent.com/130169752/230868631-60ef8cba-7c0c-4e72-8875-a690e527c2d9.png)
         FreeThrowAttempts By Games:![FreeThrowAttempts_By_Games](https://user-images.githubusercontent.com/130169752/230868763-bc8fe471-7fec-42ac-9a96-4cdc91e5af41.png)
         FreeThrowAttempts By FreeThrows:![FreeThrowAttempts_by_FreeTrows](https://user-images.githubusercontent.com/130169752/230868859-031dce34-4258-437c-8d0b-84c2c86fd22c.png)

# Movie Ratings Analysis
Code: file:///C:/Users/CH354ZB/OneDrive%20-%20EY/Desktop/pers/intro%20to%20data%20science/python%20programming%20course/MovieRatings.py
Description: Explore data set and investigate the trends of movie ratings statistics.
   
Skills: data cleaning, data analysis
   
Technology: Python, Numpy, pandas, matplotlib, seaborn
   
Results: 4 plots viz comparing audience ratings, ctrics ratings and budget of movies: ![4plots](https://user-images.githubusercontent.com/130169752/230870480-1ded6f3e-f19f-451c-9d3a-73ee32b1ac0a.png)
         viz audience to critic ratings for every genre, year ![crtitVsaudALL](https://user-images.githubusercontent.com/130169752/230870874-6630d604-67bd-44bb-ba43-6b09ad8d2493.png)
         Domestic gross % US by genre per studio: ![Gross_us_by_genre_per_studio](https://user-images.githubusercontent.com/130169752/230871421-5f8bb500-1840-4ebf-bdb8-7aaa10c2457c.png)


