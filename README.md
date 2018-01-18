# CS502_project2_medical_data
This is a data pipeline to analyze medical data

								New Drug Notification System : Find the drug that suit you 

## Introduction for business plan and pitch
	We are planning to create a new drug notification system for patients/physicians to use. The idea is
	simple, we are using the key words from patients/physicians to help us to look for the FDA (food and
	drug administration) data set for the drugs that is related to this type of disease. For example,
	patient with diabetes, we can look into the FDA’s data set to find drug that treat diabetes. We will
	build a data pipeline to store and parse the data from FDA website via Kafka and Cassandra. We will
	also apply machine learning model on the drugs that we receive from the data set and suggest the most
	suitable drug back to the patients. Depends on which attribute that the patient cares the most. Some
	patient may want a lower price drug, and some may not care about the price, but only on the
	effectiveness of the drug.


## Link and data that will be used in this project:
To get general inforamtion of top illness: Cancer, Cardiovascular Disease,Diabetes, Hepatitis B & C
https://www.fda.gov/ForPatients/Illness/default.htm
Let say we start with the nofication for Diabetes:
1. Enter the category 
2. Get the information: Diabetes Prevention in this link: 
https://www.fda.gov/ForPatients/Illness/Diabetes/ucm408100.htm
3. Get information regarding the treatment if patient is already have the illness:
https://www.fda.gov/ForPatients/Illness/Diabetes/ucm408101.htm
4. For approved medicine: 
https://www.fda.gov/ForPatients/Illness/Diabetes/ucm408682.htm
5. Then look for information at link below to look for listed drugs and compile their attributes
https://www.accessdata.fda.gov/scripts/cder/daf/ 
(We also get the predownloaded zip file)
We can display something like the image below to compare different drugs and do machine learning analysis
![Example.png]

6. Machine learning and data analysis etc