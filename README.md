# sapa_model

Sapa.com is one of the leading eCommerce platforms in Nigeria with millions of daily complete transactions. The goods and services on sapa.com cater for both the elite and the masses which makes it the first choice for almost everybody in Nigeria. Due to the COVID-19 pandemic that struck the entire world in all areas of living, the companies' daily complete transactions have dropped drastically to thousands.

The CEO, Mr Echoke in his recent actions to put the platform back to the top of the eCommerce platforms chain in the country has approved the use of Artificial intelligence in User Personality Analysis. The company has contracted to build an AI System with a special focus on recommender system development to build a robust intelligent model capable of recommending products and services to Users based on their activities on sapa.com.

I build a model capable of predicting users’ responses to marketing campaigns based on the features in the provided dataset by the sapa.com data engineer. The next phase of the project was highly dependent on the accuracy of my model as this was the foundation of what will constitute the features of the proposed recommender system development. Good luck!

It was a great task

DATASETS (It is a private data so i wont be uploading the datset for privacy)

train.csv: contains the target. This is the dataset that you will use to train your model. test.csv- resembles train.csv but without the target-related columns. This is the dataset on which you will apply your model to. sample_submission.csv: shows the submission format for the project, with the ‘ID’ column mirroring that of test.csv and the ‘target’ column containing my predictions. The order of the rows does not matter, but the names of the ID must be correct.

VARIABLE DEFINITIONS

ID: Unique identifier for each User

Year_of_Birth: Year of birth

Education_Level: The highest level of education attained by the User

Marital_Status: Marital status

Disposable_Income: Yearly User’s household disposable income

No_of_Kids_in_home: total count of children in the user’s home

No_of_Teen_in_home: Number of teenagers in the User's household

Date_User: Date of User's enrollment with the company

Recency: Number of days since User's last purchase

Discounted_Purchases: Counts of purchases made by the user using coupons

WebPurchases: Counts of purchases made by the user through the company’s website

CatalogPurchases: Counts of purchases made by the user using a catalogue

StorePurchases: Counts of purchases made by the user directly in stores

Amount_on_Wines: Total amount user spent on wine and drinks within the last 3 years

Amount_on_Fruits: Total amount user spent on fruity food within the last 3 years

Amount_on_MeatProducts: Total amount user spent on meat products and livestock within the last 3 years

Amount_on_FishProducts: Total amount user spent on fish alone within the last 3 years

Amount_on_SweetProducts: Total amount user spent on sweets and chocolates within the last 3 years

Amount_on_GoldProds: Total amount user spent on golden products within the last 3 years

WebVisitsMonth: The number of times the user of visits to company’s website within the last 4 weeks

Cmp3Accepted: 1: Offer was accepted after the third campaign, 0 otherwise

Cmp4Accepted: 1: Offer was accepted after the fourth campaign, 0 otherwise

Cmp5Accepted: 1: Offer was accepted after the fifth campaign, 0 otherwise

Cmp1Accepted: 1: Offer was accepted after the first campaign, 0 otherwise

Cmp2Accepted: 1: Offer was accepted after the second campaign, 0 otherwise

Any_Complain: 1 if the user has a compliant history with the platform in the last 3 years, 0 otherwise

User_Response: 1: indicates the acceptance of offer and 0 otherwise
