#### Risk-Analysis-inBanking-FinancialServices
[Risk Analysis_EDA_Yiqiu Wang_OGTIP_EUR_BA_DA _07_OGTIPDAYW279.pdf](https://github.com/Yiqiu-W/Risk-Analysis-inBanking-FinancialServices/files/14790671/Risk.Analysis_EDA_Yiqiu.Wang_OGTIP_EUR_BA_DA._07_OGTIPDAYW279.pdf)

#### Introduction
##### In an era where data serves as a powerful ally, we have delved into extensive exploratory data analysis (EDA)to identify key driving variables associated with clients' challenges in meeting their installment commitments.Our objective is to empower the bank with insights that enable informed decisions and proactive riskmanagement.

##### In this analysis, we've considered a myriad of factors ranging from demographic details to behavioralpatterns, all with the goal of deciphering the complex landscape that surrounds loan repayment. From thetype of contact made to the number of days a client changes personal identification documents, we've left nostone unturned.

##### Join me as we navigate through the intricacies of age, gender, family dynamics, education, income sources,housing situations, and more. We'll uncover patterns that could significantly impact the likelihood of a clientfacing difficulties in fulfilling their financial obligations.

##### In essence, this analysis serves as a guiding light, allowing us to make nuanced adjustments in our loanapproval process. By understanding these driving variables, we aim to not only minimize risks but also foster amore sustainable and responsible lending environment.
#
#### Data(Variables considered)
###### The original data frame contains 37 columns which covered data about 307511 individuals. But we will only look at several variables that could have significant impact on payment difficulties.

###### TARGET: Target variable (1 - client with payment difficulties: he/she had late payment more than X days on at least one of the first Y installments of the loan in our sample, 0 - all other cases)

###### NAME_CONTRACT_TYPE: Identification if loan is cash or revolving

###### FLAG_OWN_CAR: Flag if the client owns a car
###### FLAG_OWN_REALTY: Flag if client owns a house or flat

###### FLAG_MOBIL: Did client provide mobile phone (1=YES, 0=NO)
###### FLAG_CONT_MOBILE: Was mobile phone reachable (1=YES, 0=NO)

##### DAYS_ID_PUBLISH: How many days before the application did client change the identity document with which he applied for the loan
##### DAYS_LAST_PHONE_CHANGE: How many days before application did client change phone

##### DAYS_BIRTH: Client's age in days at the time of application
##### CODE_GENDER: Gender of the client
##### CNT_CHILDREN: Number of children the client has
##### NAME_EDUCATION_TYPE: Level of highest education the client achieved
##### NAME_INCOME_TYPE: Clients income type (businessman, working, maternity leave,<85>)
##### NAME_FAMILY_STATUS: Family status of the client
##### NAME_HOUSING_TYPE: What is the housing situation of the client (renting, living with parents, ...)

##### REG_REGION_NOT_LIVE_REGION: Flag if client's permanent address does not match contact address (1=different, 0=same, at region level)
##### REG_REGION_NOT_WORK_REGION: Flag if client's permanent address does not match work address (1=different, 0=same, at region level)
##### LIVE_REGION_NOT_WORK_REGION: Flag if client's contact address does not match work address (1=different, 0=same, at region level)
##### REG_CITY_NOT_LIVE_CITY: Flag if client's permanent address does not match contact address (1=different, 0=same, at city level)
##### REG_CITY_NOT_WORK_CITY: Flag if client's permanent address does not match work address (1=different, 0=same, at city level)
##### LIVE_CITY_NOT_WORK_CITY: Flag if client's contact address does not match work address (1=different, 0=same, at city level)
#
#### conclusion
##### Based on our analysis, we regard it as appropriate for banks to be more careful and take more time to tailor suitable loan decision and plans for applicants who belong to the following categories:
##### Male
##### Relatively Low Education Level
##### Income Type: Unemployed or Maternity leave
##### Single
##### Living in rented apartments/houses or with parents
##### Age between 20 to 40
##### Changed ID documents or Phone Number shortly(less than 3 years) before handed in the application  
