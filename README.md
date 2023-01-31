# Title : Hotel-Booking-Predicting-System

About the Dataset:
<ul>
<li>Hotel booking demand datasets</li>
<li>A data set has information about bookings for two hotels, a city hotel and a resort hotel. The information includes when the booking was made, how long the stay was, how many people were staying, and if parking was available.</li>
<li>Source: Dataset taken from kaggle website</li>
</ul>

## Description

The data set has one file that compares information about bookings for a city hotel and a resort hotel.

Attributes:
Data columns (total 32 columns):<br>
 No.  Column                                                 
 0.    hotel                           
 1.    is_canceled                     
 2.    lead_time                       
 3.    arrival_date_year               
 4.    arrival_date_month              
 5.    arrival_date_week_number         
 6.    arrival_date_day_of_month      
 7.    stays_in_weekend_nights         
 8.    stays_in_week_nights           
 9.    adults                        
 10.   children             
 11.   babies
 12.   meal            
 13.   country                
 14.   market_segment               
 15.   distribution_channel    
 16.   is_repeated_guest         
 17.   previous_cancellations  
 18.  previous_bookings_not_canceled
 19.  reserved_room_type             
 20.  assigned_room_type              
 21.  booking_changes                
 22.  deposit_type                
 23.  agent                     
 24.  company                   
 25.  days_in_waiting_list     
 26.  customer_type        
 27.  adr                     
 28.  required_car_parking_spaces 
 29.  total_of_special_requests     
 30.  reservation_status            
 31.  reservation_status_date
 
## Getting Started


### Business Questions:

List of Questions to help project goals

<ol>

<li>How Market Segment Of Booking Affecting Cancellation ?</li>
<li>How long do people stay at the hotels?</li>
<li>Which are the most busy months?</li>
<li>What Are The Other Factors that affecting cancellation of booking ?</li>
<li>Which countries do customers come from?</li>
<li>What types of customers are most common in each hotel?</li>


</ol>

What machine learning algorithm that has the highest accuracy when it comes predicting hotel booking cancellations ?

### Workflow:

1. Data Cleaning :

Imputing missing value with mean
Dropping rows with abnormal values: 0 Total guests / adults in the booking

2. Exploratory Data Analysis :

Feature Engineering
Aggregating Columns -  the agg function refers to the aggregation operation that is being performed on the data. 
Visualization
Insight & Conclusion

3. Feature Selection for machine learning process

Label encoding for certain columns that needs to be encoded

4. Model Building

<ul>

<li>Train Test Split</li>
<li>Using pipeline for model building</li>
  * scaling for numerical features <br>
  * Normalizing for numerical features
  
<li>
<ul>

<li>Creating base model with few algorithm <br>
         * Logistic Regression, <br>
         * K Neighbors Classifier, <br>
         * Decision Tree Classifier, <br>
         * Random Forest classifier
</li>
</ul>
</li>
<li>Checking evaluation matrix</li>
<li>Comparing the model with the best accuracy score</li>
<ul>

## Authors

@Kaaviasudhan

## Version History

* 0.1
    * Initial Release
