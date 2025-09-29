# Data Mining Prediction for Chicago Crime
# Executive Summary:
My objective was to locate and predict the top four most likely crimes in the city of Chicago to help make arrests more effective by associating data rules utilizing R. 
1. Assault, battery, criminal damage, and theft are the top four crimes.
2. Results showed some association between the data, so there are some conclusions to be drawn from them.  
3. By breaking up the city’s districts into north, central, and south, I was able to look more closely at the data relating to those crimes. 
4. With an average model success rate of around 67%, I found that the models I used do need some work to be more effective.

# Business Problem:
The purpose of this project is to shed light on the effects of crime and the likelihood of where crimes are committed in the city of Chicago, Illinois. My goal was to better police presence in the Chicago districts by allocating the right amount of resources to the needed areas. There is certainly the moral reason for lowering what is wrong being the right thing to do. The economic effects of lowering crime in this city are better because this provides a more attractive environment for business so more companies will want to move there. When crime is down, neighborhoods and communities can better themselves and project a more livable image.

<img width="1199" height="831" alt="image" src="https://github.com/user-attachments/assets/b6043e04-e1f7-4e4b-aaa4-5bd27faf5927" />

# Methodology:
1. For the descriptive modeling, I used the R Apriori algorithm since this dataset fits better since the dependent variables that I was attempting to use were better served under a categorical friendly model. Since this algorithm is unsupervised, I wanted to find out if there were relationships between the three district areas, crime types, and arrests in the city.
2. For the predictive modeling, I chose the R Decision tree algorithm. I aimed to look at the number of arrests for the incidents logged to gauge how effective the police coverage in the city and district area is. I was able to make inferences in both of these models using the attribute “Arrested” since it is a yes/no question and used several predictors to produce the results.
3. Also for the predictive modeling, I chose to use the R Naïve Bayes algorithm since this method depends more on probability, so this data worked well in our results.

# Skills:
R: Apriori Algorithm: inspect rules test, network plot, parallel plot

R: Decision tree algorithm: confusion matrix and prediction nodes

R: Naive Bayes algorithm: confusion matrix

# Results and Recommendations:
The three algorithms utilized showed different results:

Apriori algorithm showed poor results with support being low around 37% through testing the three district areas to see if there were association rules but did show higher-end confidence, showing a leaning towards only specific data.

<img width="840" height="148" alt="image" src="https://github.com/user-attachments/assets/e6673fab-b7ce-4787-aaf9-b31dd7580642" />

Naïve-Bayes tests pulled the following performance results in predicting arrests. They were not as high as I would have hoped but considering the size and variety of the data, this is possible.

<img width="537" height="240" alt="Naive Bayes" src="https://github.com/user-attachments/assets/9e7e3029-675f-4d6d-a906-beb3f764add1" />

Decision tree model pulled better performance than the Naïve-Bayes. I look at the error rate being only 11% compared to the 33 and 34%. The false-positive rate is much lower showing the decision tree almost unwilling to make a positive arrest identifier.

<img width="313" height="240" alt="Decision tree" src="https://github.com/user-attachments/assets/7d3274e5-8570-4579-90cd-06a2dcb33644" />

# Next Steps:
1. A better model would be to possibly try more combinations and find out why the data is not pulling better rules or showing better results

2. Some of the challenges could be the data itself in that it may have some structural challenges since this dataset does have much variety

3. With enough code manipulation and data wrangling, we can have a more accurate prediction of crime in Chicago




