# What makes a good cup of coffee? (MLR)
**Description**: 
Slideshow for presentation on Multiple Linear Regression - what makes a good cup of coffee?

In this presentation, we explore our goals and questions: 
* What makes a good cup of coffee?
* Estimate the association between the response and explanatory variables.
* From the explanatory variables, what is most and least important?

*Please view slideshows or report for full details, including summary statistic and modeling results.

**Methodology**:
Data is collected from the Coffee Quality Institute's review pages in January 2018 of reviews of 1338 Arabica and Robusta coffee beans. We can assume the data was collected using a voluntary sampling method as any of the Coffee Quality Institute's trained reviewers are able to give a review and score to the coffee beans that they receive samples of.

Variables:
* Response = Coffee Ratings (Total Cup Points); rated from 0-100
* Explanatory = Aroma, Flavor, Aftertaste, Acidity, Body, Balance Uniformity, Cup Cleanliness, Sweetness, Cupper Points; rated from 0-10

We utilize a multiple linear regression model and create a hypothesis of:
Total Cupping Points = β0 + β1 aroma + β2 flavor + β3 aftertaste + β4 acidity + β5 body + β6 balance + β7 uniformity + β8 cup cleanliness + β9 sweetness + β10 cupper points + ε

Where, β0 : the average total cupping points for coffee beans with variables units = 0
β1... β10 : the average difference in total cupping points for coffee beans whose predictor
variable differs by one unit. ε : the model error residuals

**Assumptions**:
1. Linearity
2. Constant variance
3. Normality
4. Multicollinearity

**Results and Conclusion**:

* Flavor was the least reliable predictor
* Sweetness and cup cleanliness was the most reliable predictor

**References**
LeDoux, James, Coffee ratings (2020), GitHub repository,
https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-07-07#coffee_ratingscsv
