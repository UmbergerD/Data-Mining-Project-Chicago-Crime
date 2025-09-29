# Data Mining Prediction for Chicago Crime
# Executive Summary
My objective was to locate and predict the top four most likely crimes in the city of Chicago to help make arrests more effective by associating data rules utilizing R. 
1. Assault, battery, criminal damage, and theft are the top four crimes.
2. Results showed some association between the data, so there are some conclusions to be drawn from them.  
3. By breaking up the city’s districts into north, central, and south, I was able to look more closely at the data relating to those crimes. 
4. With an average model success rate of around 67%, I found that the models I used do need some work to be more effective.

# Business Problem
The purpose of this project is to shed light on the effects of crime and the likelihood of where crimes are committed in the city of Chicago, Illinois. My goal was to better police presence in the Chicago districts by allocating the right amount of resources to the needed areas. There is certainly the moral reason for lowering what is wrong being the right thing to do. The economic effects of lowering crime in this city are better because this provides a more attractive environment for business so more companies will want to move there. When crime is down, neighborhoods and communities can better themselves and project a more livable image.

<img width="1199" height="831" alt="image" src="https://github.com/user-attachments/assets/b6043e04-e1f7-4e4b-aaa4-5bd27faf5927" />

# Methodology
For the descriptive modeling, I used the R Apriori algorithm since this dataset fits better since the dependent variables that I was attempting to use were better served under a categorical friendly model. Since this algorithm is unsupervised, I wanted to find out if there were relationships between the three district areas, crime types, and arrests in the city.
For the predictive modeling, I chose the R Decision tree algorithm. I aimed to look at the number of arrests for the incidents logged to gauge how effective the police coverage in the city and district area is. I was able to make inferences in both of these models using the attribute “Arrested” since it is a yes/no question and used several predictors to produce the results.
Also for the predictive modeling, I chose to use the R Naïve Bayes algorithm since this method depends more on probability, so this data worked well in our results.
