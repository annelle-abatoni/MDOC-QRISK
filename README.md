# WNSK@4-2022 Risk Calculator

## Project Description 
Integrating the QRISK®3-2018 risk calculator into mDoc's digital health platform to predict a person's risk of developing a heart attack or stroke over the next ten years. In the age of information where data availability is rather not the problem, our team’s task has been to modify the QRISK®3-2018 risk calculator into a more user-friendly tool that can evoke emotion in the user and prompt them to take immediate action to prevent a cardiovascular event. This has been coupled with designing an algorithm and considering data that caters for the African population, a vital element the QRISK®3-2018 risk calculator leaves out since it was designed based on data from the British population.   

## Background 
The burden of Non Communicable diseases, NCDs including cardiovascular diseases, CVDs is rising in Sub-Saharan Africa. This is reflected in the low levels of hypertension diagnosis at 40%, treatment at 35% and control as low as 10-20%. Cardiovascular disease deaths have increased by a shooting 50% in Sub-Saharan Africa. In the Case of Kenya, CVDs cause about 25% of hospital admissions and 13% deaths. The death rate for heart disease and stroke is at 72 per 10,000 people and 92 per 10,000 people ranking 144 for heart disease and 81 for stroke on the global scale. These numbers are increasing. 




##Objectives
To identify high-risk patients and risk factors with the use of health risk assessments
To recommend preventive care strategies to reduce the likelihood of chronic disease development
To determine disease severity and when to initiate lifestyle modifications and preventive medical treatment 
 
## Goal
Our goal is to develop ​​an algorithm for predicting cardiovascular risk and make it possible to recommend preventive care strategies to reduce the likelihood of chronic disease development. 
 
##Strategy
Our algorithm has the ability to identify high-risk patients and risk factors using health risk assessments (HRAs) conducted on a diverse group of participants with keen interest to participants of African descent. HRA’s were used to collect patient data and identify potential risk factors that could lead to chronic disease and data obtained from HRAs to determine disease severity and when to initiate lifestyle modifications and preventive medical treatment.
 
## Data
We studied a cohort of approximately 15,000 people aged 25 and older without history of a cardiovascular event. We received extensive data conducted by mDOC on the HRAs of this cohort. These data contained information on the participants’ history of hypertension, arthritis, diabetes, diabetes type, obesity, migraine, chronic kidney disease, stroke, and heart disease/attack. There was also information on whether the participants were taking blood pressure medication, smoked tobacco, drank alcohol or had systolic blood pressure. More general metadata was also available like the age, gender, weight, height, body mass index (BMI), triglycerides, and cholesterol levels of the participants. Patients under 25 years of age were excluded because this is the lower age limit for the risk calculator.
We compared this data to the data in a study by National Library of Medicine: Cardiovascular Diseases in Sub-Saharan Africa Compared to High-Income Countries using an Epidemiological Perspective. There were two shocking distinct factors:
The tendency of CVDs to occur at younger ages in Sub-Saharan African populations, approximately two decades earlier compared to Developed Countries. 
While the underlying cause of heart failure among adults in high income countries is ischemic heart disease, IHD, in Sub-Saharan Africa, the leading causes are hypertensive heart disease, cardiomyopathy, rheumatic heart disease and congenital heart diseases. 
 
 
## Features of the QRISK®3-2018 risk calculator modified. 
Users have the option to go to the calculator once logged into their mDoc accounts in the top-bar of the web application. 
For data collection, the site stores the pieces of users’ entries. Each prompt has different links where the user can read more on why that prompt is relevant to the accuracy of the risk calculator. 
The database saves users’ entered data allowing them to save their progress on their account. They also have the option to get extensive details on how the risk was calculated by choosing to expand the results.
The information provided has to be secure against user input that could be potentially malicious i.e. SQL injection. 
Our front-end design will utilize HTML, CSS and JavaScript, which will serve a great purpose in our GUI to guide the user through the site when inputting data or learning more about the risk calculator.
