# Bank_term_deposit_marketing

Market Campaigns by XYZ-
XYZ is Indian bank which provides various types of services to clients. One of the most 
famous and profitable services of them is Term Deposit. So, they have launched a market 
campaign to contact customers on phone and advertised their products.
Now they want to analyze the data that they have collected during the campaigns and 
automated the process of classification that predict the if the client will subscribe the 
service or not.
Using the attached datasets which contains historical data about the market campaigns, the 
problem has two primary goals:
1. To analyze the data and get the insights about the customers.
2. To build a model which automate the process of classification.
The attached CSV datasets has following columns:
Input variables: -
1 - age (numeric)
2 - job : type of job (categorical: 'admin.','bluecollar','entrepreneur','housemaid','management','retired','selfemployed','services','student','technician','unemployed','unknown')
3 - marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means 
divorced or widowed)
4 - education (categorical: 
'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown'
)
5 - default: has credit in default? (categorical: 'no','yes','unknown')
6 - housing: has housing loan? (categorical: 'no','yes','unknown')
7 - loan: has personal loan? (categorical: 'no','yes','unknown')
# related with the last contact of the current campaign:
8 - contact: contact communication type (categorical: 'cellular','telephone')
9 - month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')
10 - day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')
11 - duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects 
the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is 
performed. Also, after the end of the call y is obviously known. Thus, this input should only be
included for benchmark purposes and should be discarded if the intention is to have a realistic 
predictive model.
# other attributes:
12 - campaign: number of contacts performed during this campaign and for this client (numeric, 
includes last contact)
13 - pdays: number of days that passed by after the client was last contacted from a previous 
campaign (numeric; 999 means client was not previously contacted)
14 - previous: number of contacts performed before this campaign and for this client (numeric)
15 - poutcome: outcome of the previous marketing campaign (categorical: 
'failure','nonexistent','success')
Output variable (desired target):
16- y - has the client subscribed a term deposit? (binary: 'yes','no')
