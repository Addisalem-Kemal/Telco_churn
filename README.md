Telco Churn


Project Goal:

The purpose of this project is to identify various drivers of churn within Telco and predict customer's probablity of churn using machine learning methodologies.


Questions we are interested in:


When are customers most likely to churn?

Which features affect churn the most?

Is there a price threshold that increases churn per feature?

What does the churn rate look like after the 12th month?


Data Dictionary:


Attribute	            Definition	                                                            Data Type

customer_id	            Alpha-numeric ID that identifies each customer	                        object

online_security	        Indicates if a customer has online security add-on	                    int64

online_backup	        Indicates if a customer has online backups add-on	                    int64

device_protection	    Indicates if a customer has a protection plan for Telco™ devices	    int64

tech_support	        Indicates whether a customer has technical support add-on	            int64

streaming_tv	        Indicates if a customer uses internet to stream tv	                    int64

streaming_movies	    Indicates if a customer uses internet to stream movies	                int64

internet_service_type	Indicates the type of internet service a customer has	                object

dsl_internet	        Indicates if the customer has dsl internet or not	                    uint8

fiber_optic_internet	Indicates if the customer has fiber optic internet or not	            uint8


How to reproduce:

    Pull all .py files
    acquire.py
    prepare.py
    Add your env.py file
    Run through telco_churn.ipynb
    
Random states are set as 42 in the notebook
