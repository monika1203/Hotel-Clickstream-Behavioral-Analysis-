# Hotel-Clickstream-Behavioral-Analysis-
This dataset includes clickstream data of online transactions for hotel booking in year 2011

CLICK STREAM ANALYTICS PROJECT_PART I 
 
•	Analyze the data (HotelClickStream.xls) and interpret the results. 
This dataset includes clickstream data of online transactions for hotel booking in year 2011. Appendix doc includes the detailed description for the variables.  
 
1. Create the following 2 additional variables into data  
1)	REF_D (create a dummy variable indicating whether the transaction was referenced from other website, if not, the final booking website was directly accessed. If no information provided for the variable REF_DOMAIN_NAME, REF_D = 0; otherwise REF_D = 1) 
2)	LOG_PRICE (take the log transformation of the variable PROD_TOTPRICE ) 
 
a)	Provide a summary table showing the top 10 domain names 
(DOMAIN_NAME) that generated the most volume of transactions the report should look like the following Table. Please summarize briefly your observations from the results  
 
b)	Provide a summary table showing the top 10 reference domain names (REF_DOMAIN_NAME) that generated the most volume of transactions. The report should look like the following Table. Please summarize briefly your observations from the results. 
  
c)	Provide summary statistics (N, Max, Min, Mean, and Std.) for variables: DIRECTP_D; REF_D; DURATION; PAGES_VIEWED; LOG_PRICE; and TRANS_FREQ. Please report your summary statistics table and provide short descriptions (a few bullet points) of your observations. 
 
d)	Make a Scatter Plot and a Histogram for any of the variables of your own interests in the data. Then report any insights you may be able draw from the charts.   
 
2.	a) Use the linear regression technique to answer the question on “what are the factors that influence how much time people spend on a website?”( Hint: use DURATION as your DV). You should try different set of independent variables in the data set to see which one(s) has significant results (create dummy variables for some of the nonnumerical variables if needed).Report 1) the final set of independent variables you have chosen and why you have chosen them; and 2) the estimated regression equation with simple explanations for each estimated coefficient (β).  Please ONLY report and interpret your final regression results.    
 
b) Use the linear regression technique to answer the question on “what are the factors that influence how many pages people views when visiting a website?”(Hint:use PAGES_VIEWED as your DV). And decide your IVs by conducting the similar exercises in the above analysis. Please ONLY report and interpret your final regression results. 

d) Please summarize your observations by comparing the results from a) and b).       
