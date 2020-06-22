# Project-3-Analyze-A-B-Test-Results
 
This project was a part of the Udacity Data Analyst Nanodegree program.
Project Definition: To understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Your goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

### Part I – Probability:

To check the probability of conversion ratio, statistical calculations were made to find out the probabilities of converting to new page. These were used to analyze if the old or new page led to more conversions.

### Part II - A/B Test

Initially, Null and Alternative Hypothesis were defined and then Boot strapping and Sampling Distributions was done. 
After calculating p-value and z-score, the conclusions were drawn on conversions for both the pages. The conclusions were: 

•	The p-value calculated in j is approx. 0.90 which is very high than 0.05. And hence, we fail to reject the null hypothesis.

•	From the above calculations, it is observed that z-score is 1.31 and the value at 95% confidence interval is 1.96. z-score value does not exceed the confidence interval of 95% (1.96) and p-value obtained is 0.9050 which is almost similar to our results computed in section j. From both the observations it is evident that "we fail to reject the null hypothesis" and there is a higher probability of null hypothesis to be true.

### Part III – Regression
In this final part, you will see that the result you achieved in the A/B test in Part II can also be achieved by performing regression. The goal is to use statsmodels to fit the regression model to see if there is a significant difference in conversion based on which page a customer receives.

Null and alternative hypotheses associated with this regression model were defined and verified using statsmodel. Additionally, steps were carried out to check if country had an impact on conversion.

### Conclusions

Conclusions are not only statistical reasoning, but also practical reasoning for the situation which is “After considering all the statistical data, it is evident that in none of the cases we are able to consider alternative hypothesis, meaning we FAIL TO REJECT THE NULL HYPOTHESIS. Based on the results, I would recommend continuing using the old page, as the new page has no major improvements over old page, in terms of conversion rate.”


