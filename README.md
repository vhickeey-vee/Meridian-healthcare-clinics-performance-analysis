# 📊 Meridian Health Clinics Analysis Across Lagos
#### performance overview


## 🧰 Tools Used
- Excel (data cleaning)
- Pivot table (analysis)
- Pivot chart (visualization)


## 📈 Project Overview

Meridian health clinics is a fictional mid-sized healthcare provider operating multiple outpatient clinics across Lagos. They offer general and specialist consultations (paediatrics, cardiology, dentistry, general medicine, etc.) and have grown quickly over the past two years by opening new branches. The data involve include information about the clinics in terms of appointment, department, location, speciality and records of the clinic daily activities to patients.

In this project, we will be analysing the appointment records to find meaningful insights patients, doctors and patients behaviour as well as revenue data using Microsoft excel.


## Problem Statement

The management is basically flying blindly. The Meridian health clinics are facing challenges of identifying which departments and doctors see the most patients, how much revenue each clinic branch is generating, how often patients miss their appointment schedules, the common conditions across branches and whether they are seasonal or day-of-week patterns in patients visit.


## Objective

The Meridian healthcare clinics aim to answer questions about the different problems that they are facing so that proper decisions can be made and these involves asking questions like who’s busy and who isn’t, where is the money coming from, what are people actually being treated for, etc.


## Data Source
The Meridian healthcare clinic dataset was gotten from a secondary source.


##  Data Transformation/Cleaning

The dataset was opened in Microsoft excel and data cleaning and transformation was done using excel functions and formulas to prepare the data for exploration and analysis. The data cleaning steps performed in excel using FUNCTIONS and FORMULAS includes:
1. Checking Duplicates: Duplicates were checked using the countif function.
2. Remove Duplicates: Remove any information that is duplicated to ensure data quality using the remove duplicates inbuilt function.
3. Removing Extra Spaces: Triming spaces from text to ensure consistency using the trim function.
4. Replace Text: Find and replace text to ensure standardization using the find and replace function.
5. Converting Data Types: Ensure that fields are in their correct data types such as converting date to date format using the text to column and then using the format cell dd/mm/yy to change to one data type.


## Merging Tables Together

From the appointment (fact table), we merge the dimension (patients, doctors, department, clinic, diagnosis) table, using the VLOOKUP and index and match function to bring in the necessary data into the fact table for proper analysis.

![messy dataset](merged cleaned table.jpg)<img width="936" height="303" alt="image" src="https://github.com/user-attachments/assets/537b77ba-1601-4997-8036-237e32fb9223" />
<img width="946" height="286" alt="image" src="https://github.com/user-attachments/assets/abad30ee-68ca-425e-a04f-09dc01390170" />


## Key Performance Indicators (KPIS)

KPIS were added to summarize the overall performance and operations of Meridian health clinics and was analysed using excel pivot table. In our analysis based on key metrics:
1. Total Appointment: Meridian healthcare clinics has 7,150 of appointments booked
2. Total Revenue Collected: Based on money being paid, the clinic generated a revenue of ₦38,572,300.
3. Total Revenue Expected: Meridian clinic is expected to have a revenue of ₦46,351,600 which is gotten from money being paid and those still on pending.
4. No Show Rate: The rate of patients not showing up amounted to 20%.



## Clinic Analysis Report

This report provides a detailed explanation and analysis of Meridian healthcare clinic performance. The analysis involves Revenue by clinic branch, Appointment by department, Top doctors by appointment, Appointment status distribution, Common diagnosis, Monthly appointment trend and weekly appointment trend.

#### 💰 Revenue By Clinic Branch
a. Meridian Surulere generated a revenue of ₦12,457,500.

b. Meridian Lekki generated ₦8,793,500.

c. Meridian Ikeja has a revenue of ₦7,865,800.

d. Meridian Victoria Island accumulated a revenue of ₦7,551,100.

e. Meridian Yaba revenue amounted to ₦1,904,400.

<img width="567" height="382" alt="image" src="https://github.com/user-attachments/assets/a9d27ee2-c365-476d-b87c-87c4d7aa8b00" />


#### ⚕️Patient Volume By Department
a. General medicine has the highest appointment of 1,159.

b. ENT (Ear, Nose & Throat) saw 1,111 numbers of patients.

c. Dermatology attended 1,092 patients.

d. other departments had less than 1,000 numbers of patients.

<img width="573" height="404" alt="image" src="https://github.com/user-attachments/assets/ccb8c77f-cfd0-4aa1-b569-4a87e0645046" />


#### Top 11 Doctors by Appointment
a. Dr. Nasir Fashola saw 249 patients.

b. Dr. Nasir Afolabi and Dr. Ibrahim Okonkwo had 248 patients attended to each.

c. Dr. Halima Bello with 244 patients.

d. Dr. Seyi Afolabi and Dr. Blessing Adekunle saw 242 patients each.

<img width="607" height="413" alt="image" src="https://github.com/user-attachments/assets/dfa65f8d-8332-4da0-81c8-d31edb9c8637" />


#### Appointment Status Breakdown
a. Completed appointments has a rate of 70%.

b. No show appointments with 20% rate.

c. 10% of cancelled appointments.

<img width="534" height="386" alt="image" src="https://github.com/user-attachments/assets/81f4bccf-2492-4d19-8c65-917ef049f1d8" />


#### Common Diagnosis:
a. Conjunctivitis with total of 289.

b. Gastroesophageal reflux disease with 384 in total.

c. Pelvic inflammatory disease with 379 in total.

d. Typhoid fever and Anaemia 368.

e. Hypertension with 361 in total.

f. Osteoarthritis and Bening prostatic hyperplasia with 356 in total.

g. Peptic ulcer disease and obstructive pulmonary with 354 in total.

<img width="566" height="409" alt="image" src="https://github.com/user-attachments/assets/3881e47e-fde3-40a9-b31c-e4f2f6bbfb75" />


#### Patterns In Patient Visit (Monthly)

Base on these they are some seasonal patterns in patient visit. March and November stand out as the two peak months (631 & 627), and April is actually the lowest month (545). There is clinic traffic from May to October which tends to be a rainy season leading to malaria and mosquito-borne illnesses which suggests the rason for the seasonal pattern in patient visiting the clinic because they are in a closely related range.

<img width="594" height="383" alt="image" src="https://github.com/user-attachments/assets/fa5638c3-2c94-4093-ae6f-06c7480d2d96" />


#### Day of week Patterns In Patient Visit

Monday is the busiest day and Sunday the quietest and this is understandable base on the fact that Mondays often carries over demand from the weekend (people who felt unwell Saturday/Sunday and waited till weekday) and Sunday usually sees fewer patients since it typical rest day. Midweek (Wednesday, Thursday) and Monday are closely in the same range while Friday and Sunday has dip below. This suggests that patients visit volume is relatively stable through the week, with a modest lift early in the week (Monday) and a sustainable visit during the weekdays (Wednesday & Thursday).

<img width="656" height="452" alt="image" src="https://github.com/user-attachments/assets/8af6664d-5ad9-4ca9-b72a-2e84ed61196c" />


## Key Insights & Findings

#### Revenue By Clinic Branch
a. Surulere is the clear revenue leader with ₦12,457,500 of the total revenue – well ahead of the rest.

b. Lekki with the second highest branch ₦8,793,500.

c. Ikeja and Victoria Island are almost tied ₦7,865,800 & ₦7,551,100 – no huge difference.

d. Yaba is a major outlier generating the lowest revenue of ₦1,904,400 compared to the other branches.

There is a big and clear performance gap in money coming into the clinic by the different branches and from my findings this is due to the number of patients visits.

#### Patient Volume By Department
a. General medicine (1,159), ENT (1,111), and Dermatology (1,092) are the top 3 departments – they are tightly clustered.

b. General medicine is the department that sees the most patient and this lead reflect the fact that it is the first point of contacts for patients so it understandable.

#### Top Doctors By Appointment
Based on top doctors, no doctors stand out as uniquely overloaded as to the number of patients each of the doctors sees and this suggests that the workload of the doctors is genuinely balanced and evenly distributed.

#### Appointment By Status Distribution
a. 20% of all booked appointments are no shows, 10% are cancellations, only 70% are completed visits.

b. no shows appointment means no advance warning which leads to the slot not being rebooked by someone else and this is a wasted time for the doctor, room usage and administrative efforts (booking, prep). This is a real problem for the clinic.

#### Common Diagnosis
Based on my findings these tells Meridian clinic isn’t a speciality driven clinic dominated by one condition type but a diverse and multi-functional clinic that operates on different conditions and diagnosis.

#### Seasonal & Day-Of-Week Patterns
a. Monday is the highest and Sunday the lowest which shows a normal weekly pattern

b. March & November the highest, February and April the lowest

c. May to October notice almost the same number of patients visit which shows a seasonal pattern (rainy season) as a result of malaria and mosquito air borne illness.


## Recommendations

1. Investigate Yaba branch specifically base on their location cause from my findings the reason for the low level of revenue generated is because of the low number of patients visit. If you filter to just Yaba, you will notice that the volume of patient visit by departments is tailored down to just two departments among so many departments. In other words, the location should be looked into maybe the number of people around the clinic is relatively low. Also, the availability of doctors should be considered because it may also mean that they are no much doctors in that clinic leading to low patients and in turn leading to low revenue.

2. Addressing the 20% no-show rate by suggesting an SMS or call reminders 24 – 48 hrs pre-appointment, a certain amount of deposit to ensure the appointment being booked is secured, a follow up arrangement with patients in regards to their appointments.

3. Track revenue collection separately from revenue being billed or charged cause not all revenue being charged are received by the clinic due to some circumstances like money on pending and money being waived. So, a good tracking or recording system will help in monitoring revenues.

4. Keep staffing levels consistent across departments since the departments are operating in almost the same numbers of patients. There is no need for aggressive staffing in specific departments as well as seasonal and weekly periods.


## Dashboard

<img width="930" height="377" alt="Screenshot 2026-08-26 094219 dashboard" src="https://github.com/user-attachments/assets/92507c6e-60a4-4aa6-a14e-5a3c1d213f9a" />


## Conclusion

This analysis is set to answer a simple but important question: How is Meridian healthcare clinics performing after two years of expansion? Ultimately this project moves Meridian from having no consolidated view of its performance to having a clear view and understanding of how things are operating and functioning.





















