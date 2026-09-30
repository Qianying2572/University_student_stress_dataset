# University_student_stress_dataset
## CONTRIBUTORS: 
Paul, Subrata Kumer; Paul, Rakhi Rani; Musa Miah, Abu Saleh; Hamid, Md. Ekramul ; Rashidul Hasan, Mirza A.F.M. 
## INSTITUSION:
University of Rajshahi
## DESCRIPTION: 
This dataset contains responses from 3000 undergraduate students studying at public, private, and national universities in Bangladesh. The primary goal of the dataset is to support machine learning research on classifying student stress levels using academic, lifestyle, social, and psychological factors. Data were collected through a structured Google Form survey, which was distributed via email to 3710 students, and a total of 3000 complete and anonymous responses were used in the final dataset.

The dataset includes 18 attributes, selected based on their relevance to academic stress in higher education. Demographic features include Age (19–24) and Gender, while University_Type captures differences between institutional environments. Academic indicators—Study_Hours, Class_Attendance, Exam_Frequency, Assignment_Load, and Tuition (Yes/No)—reflect students’ academic workload and overall study pressure.

Lifestyle-related features include Sleep_Hours, Social_Media_Use, Screen_Time, and Physical_Exercise, as daily habits often influence stress and time management. Socio-economic and psychological attributes—Family_Income_Level, Peer_Pressure, Family_Support, and Anxiety_Level—provide additional context on student wellbeing and external influences.

A derived variable, Stress_Score, was computed by combining workload indicators, psychological ratings, and lifestyle habits. Based on this score, each student was assigned a target label, Stress_Level, categorized as Low, Medium, or High. This label enables supervised learning tasks and stress prediction modeling.

The dataset is clean, structured, and suitable for multi-class classification, correlation analysis, and educational data science research. It offers a valuable resource for understanding how academic demands and personal habits interact to influence stress among university students in Bangladesh.
## GEOGRAFIC LOCATION: 
The data were collected from undergraduate university students in Bangladesh.
## METHODOLOGY: 
The dataset was collected through a structured Google Form survey distributed via email to 3,710 undergraduate university students in Bangladesh. Participants were enrolled in public, private, and national universities. A total of 3,000 complete and anonymous responses were retained for the final dataset. Data analysis is conducted using IBM SPSS Statistics, including descriptive statistics, correlation analysis, and regression analysis.
## LICENCE:
CC BY 4.0 (Creative Commons Attribution 4.0 International licence)
## INFORMATIONS ABOUT DATAFILES:
**IDENTIFIER:** DOI: 10.17632/rc5htd5dfr.1 \
**LOCATION:** Mendeley Data repository, https://data.mendeley.com/datasets/rc5htd5dfr/1 \
**DATES:** Published on 25 December 2025 \
**LATEST VERSION:** Version 1 \
**SUBJECTS:** Student Stress, University Students, Academic Stress, Anxiety, Academic Workload, Mental Health, Bangladesh \
**FILE FORMATS:** Comma-Separated Values (CSV), a tabular format compatible with Microsoft Excel, IBM SPSS, R, and Python.
## DATA-SPECIFIC INFORMATION
**Number of variables:** 18 \
**Number of rows:** 3,000 \
**Missing values:** No missing values \
**Variable list and definitions:** 
| Variable / Column     | Full name & definition                                                   | Type        |
| --------------------- | ------------------------------------------------------------------------ | ----------- |
| `Age`                 | Age of the student, measured in years                                    | Numeric     |
| `Gender`              | Gender of the student                                                    | Categorical |
| `Study_Hours`         | Number of hours spent studying per day                                   | Numeric     |
| `Class_Attendance`    | Percentage of classes attended                                           | Numeric     |
| `Tuition`             | Whether the student receives/pays for tuition                            | Categorical |
| `Exam_Frequency`      | Frequency of examinations                                                | Numeric     |
| `Assignment_Load`     | Level/amount of assignment workload                                      | Numeric     |
| `Sleep_Hours`         | Number of hours of sleep per day                                         | Numeric     |
| `Physical_Exercise`   | Whether the student participates in physical exercise                    | Categorical |
| `Social_Media_Use`    | Hours spent using social media per day                                   | Numeric     |
| `Screen_Time`         | Daily screen time in hours                                               | Numeric     |
| `Family_Income_Level` | Student's family income category                                         | Categorical |
| `Peer_Pressure`       | Level of pressure experienced from peers                                 | Numeric     |
| `Family_Support`      | Level of support received from family                                    | Numeric     |
| `Anxiety_Level`       | Level of anxiety experienced by the student                              | Numeric     |
| `University_Type`     | Type of university attended                                              | Categorical |
| `Stress_Score`        | Composite score representing the student's overall stress                | Numeric     |
| `Stress_Level`        | Categorized stress level based on the stress score: Low, Medium, or High | Categorical | 

**Units of measurement:** 
| Variable              | Unit / Scale                 |
| --------------------- | ---------------------------- |
| `Age`                 | Years                        |
| `Study_Hours`         | Hours per day                |
| `Class_Attendance`    | Percentage (%)               |
| `Exam_Frequency`      | Frequency/count              |
| `Assignment_Load`     | Rating/score                 |
| `Sleep_Hours`         | Hours per day                |
| `Social_Media_Use`    | Hours per day                |
| `Screen_Time`         | Hours per day                |
| `Peer_Pressure`       | Rating/score                 |
| `Family_Support`      | Rating/score                 |
| `Anxiety_Level`       | Rating/score                 |
| `Stress_Score`        | Composite score              |
| Categorical variables | Categories; no physical unit |

**Missing data codes:** 
No missing values were identified in the dataset. No special numerical codes are used to represent missing observations.

