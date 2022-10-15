# Bank_Marketing_Effectiveness_Prediction-ML_Classification-

##   This project will be explored over the previous data in order to predict if the client will subscribe to a term deposit offered by the banking institution. The results will be in the form of yes or no as it a classification model.

#### Tags: Classification, Python, Machine Learning, Data Science 

#### Team Members are: Rajesh kumar, Kunika Gupta, Prayagraj Dubey

#### Links:  
Project Presentation: [Slideshow](https://drive.google.com/file/d/1HFd9jKPJBAGv-kOcDQg7HAqhuAMd0T4k/view?usp=sharing)
Dataset: [Bike Sharing Demand Prediction](https://drive.google.com/file/d/1A81TMIl0oe2G3SQ8zpT0AFJJtsZ26KAj/view?usp=sharing)

<h2><b>Problem Statement:</h2></b>

The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed. The classification goal is to predict if the client will subscribe to a term deposit (variable y).


<h2><b>ATTRIBUTE INFORMATION :</h2></b>
<h3><b>Input variables:</h3></b>
  
<h3>Bank Client data:</h3>
  
<h4>age</h4>(numeric)
<h4>job :</h4>   type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')
<h4>marital :</h4>  marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)
<h4>education </h4> (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')</h3>
<h4>default:</h4   has credit in default? (categorical: 'no','yes','unknown')
<h4>housing:</h4>   has a housing loan? (categorical: 'no','yes','unknown')
<h4>loan:</h4>   has a personal loan? (categorical: 'no','yes','unknown')

<h3>Related with the last contact of the current campaign:</h3>
<h4>contact:</h4>   contact communication type (categorical: 'cellular','telephone')
<h4>month: </h4>   last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
<h4>day_of_week:</h4>   last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
<h4>duration:</h4>   last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.
  
<h3>Other attributes:</h3>
<h4>campaign: </h4>  number of contacts performed during this campaign and for this client (numeric, includes last contact)
<h4>pdays:</h4>   number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
<h4>previous:</h4>   number of contacts performed before this campaign and for this client (numeric)
<h4>poutcome: </h4>  outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')
  
<h3><b>Output variable (desired target):</h3></b>
<h4>y - </h4>    has the client subscribed to a term deposit? (binary: 'yes','no')


<h2><b>Steps involved doing this project</h2></b>

Import data from dataset and perform initial high-level analysis: look at the number of rows, look at the missing values, look at dataset columns and their values respective to the campaign outcome.

Clean the data: remove irrelevant columns, deal with missing and incorrect values, turn categorical columns into dummy variables.

Use machine learning techniques to predict the marketing campaign outcome and to find out factors, which affect the success of the campaign.
 

## <h2><b>Conclusion</h2></b>
  
The 2nd quarter of the year has the highest number of subscriptions & Month of May has the maximum subscriptions.

Blue-collar, management and technician showed maximum interest in subscription.

Compared to married and single, Divorced people have less interest in term deposits.

People with secondary education followed by tertiary education were subscribed to term deposit.

Generally people who don't have credit in default are interested in a deposit. Majority of the people have a home loan but only few of them opted for a term deposit.

Cellular communication is seen as more effective in comparison to other communication types.

The calls with large duration have more tendency for conversion. Majority of people were not contacted previously before this campaign.

We can choose Support Vector Machine or KNN or Decision Tree to predict Effectiveness as all 3 of them are showing the same accuracy & F1- <b>Score - (0.8824).</b>


