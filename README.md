# SecuereTech
# PSID : INTL-DA-07
##########################################

# IDEA DESCRIPTION :

## We have developed our solution into two phases :

## Phase 1 :
## Exploratory Data Analysis ( EDA ) :
### We have performed the Exploratory Data Analysis on the given dataset. 
## Outcomes of EDA :
### > By using the folium, we get to know that Atmost all the points were lying in the North East region of Lucknow.
### > Dataset has outliers which we have removed using quantiles method.
### > Dataset was divided into two parts i.e. C1( includes two police stations PS1 and PS2 ) and C2( includes two police stations PS3 and PS4 ) with 38.2% and 61.8% region respectively.
## Model Training To Predict The Location Of Crime Prone Areas :
### We have trained our model by performing the Time_Series Analysis on the given dataset.
### This is how we will get the location of crime prone areas.
 
## Phase 2 :
## Model Training :
### For model training, we have taken the dataset from the kaggle.
### We have trained our model by doing the SENTIMENT ANALYSIS by using the Long Short Term Memory ( LSTM ) technique.
## Structure Of Our NLP Model :




## Task 1 : To get the data from the Social Media( By default we have used the Twiiter as social media ) :
### For this, we have used Third Party API ( snscrape ) to get the information from the twitter. This API gives us the data with the time delay of 7 Hours from the current time.
## Reason to use Third party API : 
### There was no other options to get the data from the twitter, because only goverment based authority can get the previliges by having an agreement with that particular organinzation.

## After getting the data we can do the Sentiment Analysis on the dataset which is provided by the Third Party API and then after that we can get the information related to the person who are posting the hatred posts. 

# MAIN IDEA :
## We are using the output of phase 1 ( i.e. the locations with high probability of crime ) as an input for phase 2.

## We will extract the data of only those users who are active in that particular region. We can get all the posts which they are posting on social media in that particular time. And then we can fetch this data to the Phase 2 model to do the Sentiment Analysis of that post. And if that posts is hateful, we can provide all the metadata related to it. For example, number of people who have liked, commented, along with the user ID, tweet URL etc.  

### Video PPT link : https://drive.google.com/file/d/17VWwLwBMAv_0bxpEn7dU1OARYG-JwS-2/view

### WEBAPP LINK : https://securetech.herokuapp.com/

### Youtube Link : https://youtu.be/zH5FS-kErLU
# OUR DEVELOPMENT IS STILL GOING ON.......
