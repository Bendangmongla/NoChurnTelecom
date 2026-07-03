No-Churn Telecom is an established Telecom operator in India with more than a decade in Business. Due to new competitors in the market, telecom industry has become very competitive, making customer retention a major challenge. 

Despite initiatives such as tariff reductions and promotional offers, the company’s churn rate (percentage of customers switching to competitors) remains above 10%. 

To maintain a competitive edge, No-Churn Telecom aims to leverage Machine Learning to identify churn patterns and improve customer retention strategies. 

PROJECT GOAL 

Help No-Churn with their use cases with ML 

1.	Identify the key variables influencing customer churn. 

2.	Predict customers likely to churn. 

3.	Generate a new variable CHURN_FLAG: 


	YES (1) → High churn risk 

  NO (0) → Low churn risk 

  
	
  4. Help marketing team target high-risk customers with retention offers. 
	
  5. Assist customer support teams in prioritizing high-risk customers for proactive engagement and faster issue resolution.
	
	
	Meta Info of Data 
	
	Column Name 
	
	Description 
	
	customer_id 
	
	Unique ID assigned to each customer 
	
	telecom_partner 
	
	Telecom service provider 
	
	gender 
	
	Customer gender (Male/Female) 
	
	age 
	
	Age of the customer 
	
	state 
	
	State where customer resides 
	
	city 
	
	City of the customer 
	
	pincode 
	
	Residential postal code 
	
	date_of_registration 
	
	Date when customer joined telecom service 
	
	num_dependents 
	
	Number of dependents in the household 
	
	estimated_salary 
	
	Estimated annual salary of the customer 
	
	calls_made 
	
	Total number of calls made 
	
	sms_sent 
	
	Total SMS sent 
	
	data_used 
	
	Total data usage (GB) 
	
	churn 
	
	Target variable (YES = 1, NO = 0)


NO-CHURN TELECOM — PROJECT SUMMARY


Dataset          : 243,553 customers across 4 telecom partners  

Overall Churn    : ~20.0%                                       
 
Best Model       : {best_name:<40}

Model AUC-ROC    : {best_auc:.4f}                                       


CHURN_FLAG=YES (High Risk) : {n_high:>8,} customers              

Critical Risk tier         : {n_crit:>8,} customers              
 
Urgent Support tier        : {n_urgent:>8,} customers              


KEY FINDINGS                                                    

1. Low call activity is the strongest churn signal              

2. Short-tenure customers churn at higher rates                 

3. Age 36–50 segment shows the highest absolute churn count     

4. Churn rates vary significantly across telecom partners       


RECOMMENDATIONS                                                 

Marketing  → Target Critical Risk tier with personalised offers 

Support    → Urgent tier gets same-day proactive outreach       

Product    → Investigate high-churn partners for service gaps   

Retention  → Loyalty programs for tenure < 12 months  

