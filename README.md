# Predictive-Churn-Management-for-Online-Gaming-Platform
# Background
A leading online gaming platform is investigating what leads to churn amongst their users. The company decided to study 90,000 of its users to determine the key drivers that led to them unsubscribing from their yearly plan. 

# Appraoch
I trained a Logistic Regression Model to predict churn while accounting for all possible drivers and confounds. Based on the best model, I calculated the feature importance and the individual odds of those drivers to quantify the effect. Simulated the effect of providing 6 months of extended subscription and increase in play time on churn.

# Data
The data consists of 90,000 datapoints on customers and their interaction with the gaming platform. The data is partitioned into 3 parts- train, test, and representative set. The train and test have been oversampled for churned customers to ensure the model sees both kings of customers. The representative set is a natural sample signifying the actual churn rates in the population. The data consists of the following columns:
<br>africa: User lives in Africa
<br>asia: User lives in Asia 
<br>churn: Customer churned
<br>consldays: Number of days since the most recent console purchase
<br>crackle: User has installed the Crackle app
<br>creditaa: High credit - AA or better 
<br>ctrlrs: Number of game controllers linked to the console
<br>custcare: Number of messages to the customer care center
<br>customer: Customer identifier
<br>disneyp: User has installed the Disney Plus app
<br>europe: User lives in Europe 
<br>gchange: Change in minutes spent playing games (over 3 month period)
<br>hulu: User has installed the Hulu app
<br>mchange: Change in minutes spent playing online multiplayer games (over 3 month period)
<br>mcycle: User owns a motorcycle
<br>mdrops: Number of times that an online multiplayer game has gotten dropped due to a poor connection
<br>mmins: Average number of minutes playing online multiplayer games (per month)
<br>months: Number of months the user has had the console
<br>namerica: User lives in North America 
<br>netflix: User has installed the Netflix app
<br>numgames: Number of different games the user plays (per week)
<br>oceania: User lives in Oceania
<br>over18: User is above the age of 18
<br>refurb: Console is refurbished (as opposed to new)
<br>representative: Observation is assigned to representative sample
<br>retired: User is retired
<br>rural: User lives in a rural area 
<br>rv: User owns a recreational vehicle (RV)
<br>samerica: User lives in South America
<br>spotify: User has installed the Spotify app
<br>telemundo: User has installed the Telemundo app
<br>training: Observation is assigned to training sample
<br>truck: User owns a truck
<br>youtube: User has installed the YouTube app
