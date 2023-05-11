# Term Deposit
This data set is primarily used for Term Deposit Market Campaign by Bank

Campaign Marketing wants to devise their strategy based on the outcomes.
 
To build an analytics for the same that can be presented to Marketing and Marketing can take their decision based upon that.
 
Input variables:
 
 # bank client data:
 1 - age (numeric)
 2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student","blue-collar","self-employed","retired","technician","services")
 3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
 4 - education (categorical: "unknown","secondary","primary","tertiary")
 5 - default: has credit in default? (binary: "yes","no")
 6 - balance: average yearly balance, in euros (numeric)
 7 - housing: has housing loan? (binary: "yes","no")
 8 - loan: has personal loan? (binary: "yes","no")
 
 # related with the last contact of the current campaign:
 9 - contact: contact communication type (categorical: "unknown","telephone","cellular")
 10 - day: last contact day of the month (numeric)
 11 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
 12 - duration: last contact duration, in seconds (numeric)
 
 # other attributes:
 13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
 14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
 15 - previous: number of contacts performed before this campaign and for this client (numeric)
 16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")
 
 
 Output variable (desired target):
 17 - y - has the client subscribed a term deposit? (binary: "yes","no")



# Insights/Inference
Age: Customers of greater age are more likely to subscribe for the term deposit. The data shows that the older the customer, the higher the probability of subscribing for the term deposit. This could be because older customers are more financially stable, have higher savings, or are more risk-averse and prefer safe investments like term deposits. Ages between 32-58 can be an ideal target group also since the numbers denote a decent account opening rate here.

Account balance: Customers with greater account balance are more likely to subscribe for the term deposit. The data shows that customers with higher account balances are more likely to subscribe for the term deposit. This could be because customers with higher account balances have more disposable income and can afford to invest in term deposits, or because they are more financially savvy and understand the benefits of term deposits. Balance greater than 1509 should be targeted for a higher conversion rate.

Number of contacts: The number of contacts with the customers really matters. Too many contacts with the customer could make them decline the offer. The data shows that customers who were contacted fewer times were more likely to subscribe for the term deposit, while those who were contacted too many times were less likely to subscribe. This suggests that there is a sweet spot for the number of contacts, and that too many contacts may be perceived as pushy or annoying, while too few may not be enough to persuade the customer to subscribe. Less than 4 contacts yields better results.

Education: Customers with higher education levels are more likely to subscribe for the term deposit. The data shows that customers with tertiary education are more likely to subscribe for the term deposit, while those with lower education levels are less likely to subscribe. This could be because customers with higher education levels are more financially literate and understand the benefits of term deposits, or because they have higher-paying jobs and more disposable income.

Job: Customers with certain job types are more likely to subscribe for the term deposit. The data shows that customers who are retired or students are more likely to subscribe for the term deposit, while those who are blue-collar or self-employed are less likely to subscribe. This could be because retired customers have more time and are looking for safe investments, while students may have some savings and are looking for safe places to invest them.

These insights can help the bank improve its marketing strategy and target the right customers with the right offers, leading to higher subscription rates and better returns.
