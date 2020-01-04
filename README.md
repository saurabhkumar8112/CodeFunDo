# CodeFunDo+
Task : To create a webapp which can predict in real time the probabilities of flood in a particular area given the average rainfall in that area over the last 24 hours.

Learning Features in Hand : The rainfall data of past 50 years taken from "http://hydro.imd.gov.in/hydrometweb/(S(ht2dew45izstmbyyphslh455))/landing.aspx#" in JSON format. The data contains the name of a state and district in one column and the average rainfall in the last 24 hours. We also had the same data for the last 50 years and labels being at what average rainfall the flood occured in that area. We used this as a metric for flood prediction.

The webapp : The webapp used the geocoder API to get the realtime location of a person and corresponding to that find the avergae rainfall from the "http://hydro.imd.gov.in/hydrometweb/(S(ht2dew45izstmbyyphslh455))/landing.aspx#" website, then feed the average rainfall to the classifier, get the probabilties as to how much is the chance of  a rainfall. Then return it back to the served where the corresponding message will be shown to the user. 

The app was made in flask and hosted in Microsoft's Azure.


# We came 4th in this competition. 
