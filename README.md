# MovieRecommendorSystem

Dataset Overview 
Original Dataset: The dataset is divided into three sets.
1.	Training set 
2.	Qualifying set 
3.	Probe set

The difference between the qualifying set and the probe set is that the ratings for the qualifying set are withheld by Netflix and they are not released to public. The probe set, however, is created to help the participants test the accuracy of their methods before submitting the results for the qualifying set to Netflix.  

Below is the breakdown of the data in numbers.

•	Total movies across the entire dataset: 17770
    Movie IDs range from 1 – 17770 with no gaps
    
•	Total Customers/Users included in the entire dataset: 480189
    Customer IDs range from 1 – 2649429, with gaps
    
•	The rantings are on a scale from 1 – 5 

•	The date of rating is also provided in the dataset. It is in the format YYYY-MM-DD


Results
Method 1 		Method 4  (with part of the dataset)
RMSE:	2.213309	
MAS:	1.846437

Method 2 (with part of the dataset)	
RMSE: 1.08041	 
MAS: 0.80641	

Method 2 (with the entire dataset)
RMSE: 1.060477
MAS: 0.77795	 

