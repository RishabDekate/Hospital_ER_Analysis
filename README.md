# Hospital Emergency Room (ER) Analysis

## Project Background

In this project the stakeholders are looking to monitor and analyze emergency room (ER) patient statistics to improve efficiency, reduce wait times, and enhance patient care. The data was collected from internal hospital databases (EHR, CRM, SQL systems) Patient feedback surveys (for satisfaction scores). There are 2 differnet dataset first date table and second ER dataset.

### Insights and recommendations are provided in the following key areas:

- How many patients visited the ER during a specific period? 
- What is the average wait time for ER patients?
- What is the patient satisfaction score?
- How many patients were admitted vs. not admitted?
- What percentage of patients were seen within 30 minutes?
- What are the demographics of ER patients (age, gender, race)?
- What are the busiest days and hours for ER visits?
- Which departments refer the most patients to the ER?

The Stakeholders want the analysis in 4 different dashboards with different information on the ER engagement.
- Dashboard 1: Monthly View
- Dashboard 2: Consolidated View
- Dashboard 3: Patient Details
- Dashboard 4: Key takeaways

# Data Structure & Initial Checks

The Emergency room dataset as seen below consist of 12 columns and total rows of 9,217 records.
1. Patient Id: Float64
2. Patient Admission Date: Date & Time
3. Patient First initial: String 
4. Patient Last Name: String
5. Patient Gender: String
6. Patient Age: Int64
7. Patient Race: String
8. Department Referral: String
9. Patient Admission Flag: Boolen
10. Patient Satisfaction Score: Int64
11. Patient Wait Time: Int64
12. Patient Cm: Int64
    
# Executive Summary

### Overview of Findings:

The emergency room is open everyday so the last two years data gave us insight on patients that are coming in ER for treatment. After the anaysis we got insights like number of patient that came to ER monthly is 500, with average wait time for a patient to be attended is 35.9 minutes and with an average of 190 patients came by the referrence of other doctor. In the survey  for the patients feedback gave 4.9 as satisfaction rating to the ER.

### DASHBOARD-1
![Dashboard(1)](https://github.com/user-attachments/assets/408e8ce6-88de-4cff-9b4f-d23e54c14d2b)

Dashboard 1: Insights

- The patients that were admitted are 224 and number of patient that were not admitted are 207 which is less than admitted patients.
- Percentage of patients that were seen/attended with in 30 minutes are 34.34% (148) that means patients that were not seen/attended within 30 minutes would be 65.66% (283), this sasys that patients had to wait for longer time in general.
- The demographics of ER patients as per age can tell that age group of 70-79, as per gender it tells 234 male patients came to ER and 194 female patients came in average per month, and demographics of patients as per race tells that white patients came more to ER as compared to other race.
- As per analysis the busiest days in ER visits are Thursdays and busiest hours for ER vistis mainly on eveinings(5-6 pm).
- Most patients that come in ER are not referred by any department, and if we need name of any department then second department that refers the most patients to the ER is department that do general practice.

### DASHBOARD-2
![Dashboard(2)](https://github.com/user-attachments/assets/d2e5f0a3-b42a-4926-bcb8-146519568218)

Dashboard 2: Insights

- In this dashboard all the insights of the first dashboard will be present for certain range of time i.e. from January 1 2024 to June 30 2024.
- Number of patients that came in this time span were 2923, in that most patient came in May (519) and least number of patient came in February (431). 
- The average wait time of the patient was 35.9 minutes, and similarly every month no improvement in waiting time for any patient.
- Most number of referred patients came in the month of January and number of patients that were referred in this time range were 1173.
- Status of patients that were admitted in the ER were 1464, and patients that were not admitted in the ER 1459 as they came for their routine check ups.
- 1000 patients were examined in less then 30 minutes and 2000 patients were missed to be examined within 30 minutes. That means more patients had taken more than 30 minutes to get examined in the ER. 
- In this ER number of female patients that came for checkup is 1000 were as 2000 male patients came in this time span of 6 months. In which most patients were from 30 - 39 age group.
- The number of patients that came in the ER 1750 which were not referred for any department, and highest number of white patients(796) came to the ER in this time span.
- In daily bases the number of patients that came were on Thursday(437) in which most patient preferred 5-6 as good time to come to ER.

### DASHBOARD-3
![Dashboard(3)](https://github.com/user-attachments/assets/063f741a-8393-4def-8dc7-accc5ec09f33)

Dashboard 3: Insights

- This dashboard shows granular insights into patient-level data to enable detailed analysis and troubleshooting.
- It is in tabluar form so all details are easily available for access to the stakeholders whatever they asked to analyse.


### DASHBOARD-4
![Dashboard(4)](https://github.com/user-attachments/assets/d04fa78d-aa25-43f1-b378-be0eac6aeccc)

Dashboard 4: Insights

- This dashboard gives pointers on descriptive analysis on the patient's dataset. dataset consist of data from April 2023 - October 2024.
- The emergency room dataset, covering a period of 19 months, records a total of 9,216 unique patients.
- The Average wait time was approximately 35.3 minutes, indicating a need for improvement to enhance patient flow. The average satisfaction score was 4.99 out of 10, suggesting moderate satisfaction and highlighting areas for improving patient experiences.
- A significant number of patients(5400) did not required referrals. Among those referred, the most common were General Practice (1840 cases) and Orthopedics (995 Cases), followed by Physiotherapy (276 Cases) and Cardiology (248 Cases).
- The busiest day were Mondays (1377 Patients), Sundays (1322 Patients), and Tuesdays (1318 Patterns). The busiest hours were 11 AM, 7 PM, 01 PM, and 11PM indicating need of ample staffing during these periods.
- Age Groups: Adults (30-39 Years) formed a large group (1200 Patterns), followed by young adults (20-29 Years) with 1188 Patients. Other significant groups included middle aged as well (40-50 Years).
- The largest racial group was White (2571), followed by African American (1951), multi racial (1557), and Asian (1060) patterns. A significant number of patients (1080)  declined to identify their race.
- Nearly half of the patterns (4612) were admitted, while the rest (4604) were treated and released.
- The dataset reveals high patient volumes, moderate satisfaction levels, and common referrals to General Practice and Orthopedics. Mondays and late night to early mornings hours are particularly busy. The patient demographics show a diverse age and racial composition, with nearly equal numbers of admitted and non admitted patients. These insights can help optimize the resource allocation and improve patient care in the emergency room.

# Recommendation

- The dataset reveals high patient volumes, moderate satisfaction levels, and common referrals to General Practice and Orthopedics.
- Mondays and late night to early mornings hours are particularly busy.
- The patient demographics show a diverse age and racial composition, with nearly equal numbers of admitted and non admitted patients.
- These insights can help optimize the resource allocation and improve patient care in the emergency room.
- If the ER cuts the waiting time of patients little less then it may get more patients for treatment.
