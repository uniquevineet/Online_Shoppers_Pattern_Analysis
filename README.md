# Online_Shoppers_Pattern_Analysis

People often spend a lot of time browsing through online shopping websites, but the conversion rate into purchases is low. Determine the likelihood of purchase based on the given features in the datsaset. The dataset consists of feature vectors belonging to 12,330 online sessions. The purpose of this project is to identify user behaviour patterns to effectively understand features that influence the sales.

Features	Description	DataType

Administrative        	: Number of pages visited by the user for user account management related activities	Discrete values from 0 to 27 
Administrative_Duration	: Time spent on Admin pages by the user	Continuous value (time in seconds)
Informational	          : Number of pages visited by the user about the website	Discrete values from 0 to 24
Informational_Duration  :	Time spent on Informational pages by the user	Continuous value (time in seconds)
ProductRelated	        : Number of product related pages visited by the user 	Discrete values from 0 to 705
ProductRelated_Duration	: Time spent on Product related pages by the user	Continuous value (time in seconds)
BounceRates	            : Average bounce rate of the pages visited by the user	Continuous value 
ExitRates	              : Average exit rate of the pages visited by the user	Continuous value 
PageValues	            : Average page value of the pages visited by the user	Continuous value 
SpecialDay	            : Closeness of the visiting day to a special event like Mother’s Day or festivals like Christmas	
                           (Discrete values (0, 0.2, 0.4, 0.6, 0.8, 1.0))
Month	                  : Month of the visit from Jan to Dec	Categorical
OperatingSystems	      : OperatingSystems of the visitor	Discrete values from 0 to 7
Browser	                : Browser of the visitor	Discrete values from 0 to 12
Region	                : Geographic region from which the session has been started by the visitor	Discrete values from 0 to 8
TrafficType	            : Traffic source through which user has entered the website	Discrete values from 0 to 19
VisitorType	            : Visitor type as New visitor, Returning user or Others	Categorical
Weekend	                : If the user visited on a weekend or not	Boolean
Revenue(Target Variable): If the user visit resulted with a transaction	Boolean
