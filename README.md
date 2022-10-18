# Investigate_a_Dataset - [No-show appointments]
## by Abdulafiz Musa


## Dataset

>This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

>‘ScheduledDay’ tells us on what day the patient set up their appointment. 

>‘AppointmentDay’ tells us on what day the patient are expected to visit the hospital 

>‘Neighborhood’ indicates the location of the hospital. 

>‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família. 

>‘Hipertension’, ‘Diabetes’, ‘Alcoholism’, ‘Handcap’ indicates the patients' current health issues

>‘No-show’ column: ‘No’ indicates the patient showed up to their appointment, and ‘Yes’ indicates they did not show up.


## Summary of Findings

### Deductions from statistics and graphs in the EDA section:
>Observing all the green (showed up) and yellow (didn't show up) bars across each possible factor that can affect if a patient showed up or not:

>There is a general trend showing that from the entire data of 110526 patients, 80% of them showed up for their appointment. This average is also true for the total number of patients that showed up for their appointment 'in any given category or sub-category'. Some were even as high as 90%.
Directly proportional increase between total number of appointments and number of patients that showed up.
There is an average percent of turn out regardless of the number of appointment.

>79% and 80% of the total number of female and male showed up respectively.

>The total number of appointment scheduled and confirmed each day were almost same. Tuesday and Wednesday shared the highest, but there is a drastic decline in the number of appointments on Saturday. However, the turn out percentage was still up to average - 76%.

>Patients at the age of 0 and 1 had the highest number of appointments. However, considering age brackets, there seem to be a greater number of patients between the age of 40 and 64 with a turn out of 80%.

>The location Jardim Camburi had the highest number of appointments, hence the highest number of turn out (according to point number 1) - 81% ; Bonfim had the lowest number of appointmnets, hence the lowest turn out - 80%.

>There is still an average turn out rate; the difference is only in the number of appointments.

>There is no significant preference between those that received SMS or not.

>76% of those with scholarship showed up, 80% of patients without scholarship showed up

>On a scale of 4, there is a greater number of patients with lesser number of health issues.

>Patients with 0 health issues are more than and had a greater turn out than those with at least 1 health issues, and so on.

>There is no significant preference between those that received SMS or not.

>72% of those that received SMS showed up; 83% of those that didn't receive SMS showed up.
In general, none of the categories or sub-categories in this dataset can determine the number of patients that will show up for an appointment(%), however, these categories and sub-categories can determine the total number of appointment that will be made or scheduled.

### Limitations:
>Complex analysis such as using a scatterplot or regression analysis isn't applicable as most of the data are categorical, thereby limiting: our ability to infer or establish possible correlation between the dependent variable (no_show) and the independent ones; combine two independent variables and check them against tthe no_show record to see if more than one condition could predict the turn out of patients.

>There were multiple corrections made on the dataset that could have affect any of the results displayed in the EDA sectiion.

>We deleted on of the patient record during the analysis. The patient had an age of -1
One of the health issues (handicap) had a different scale of measurement
