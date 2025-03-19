# **Predicting-Hospital-readmissions-using-Machine-learning**

## INTRODUCTION
A hospital readmission is when a patient discharged from the hospital is readmitted within a specified
time frame. Time frame generally varies from 30 day to 90 days also 1 year sometimes. The first
admission in an hospital is called as “index admission” and the subsequent admission is called as
“readmission”. In general, readmission indicates the ineffectiveness of treatment and lack of healing
during past hospital care.
Given the prevalence of diabetes in the general population and hospitalized patients, diabetes is a major
contributor to acute care re-utilization and associated costs.In 2016, over 10 million hospital discharges
involved patients with diabetes. The annual cost of readmissions within 30 days of discharge (30-day
readmission) is $20–25 billion based on the most inclusive readmission rates of 16.0 to 20.4% among
patients with diabetes in the USA Hospital .Studies show that diabetes increases the risk of 30 -day
readmission by at least 17% and up to 2.5 times compared to patients without diabetes.readmission is an
unavoidable problem for both patients and hospital.Machine Learning (ML) has appeared as a powerful
Readmission prediction tool and offered data based on active intervention data. Recent research
(2019-2024) on the prediction of the ML-based readmission, focusing on key methodologies, challenges
and future directions, is exploring this literature. Machine Learning (ML) has appeared as a powerful
Readmission prediction tool and offered data based on active intervention data. Recent research
(2019-2024) on the prediction of the ML-based readmission, focusing on key methodologies, challenges
and future directions, is exploring this literature.

A successful predictive model will help the Healthcare Organization:

Pinpoint patients with high readmission risk to reduce the occurrences of preventable hospital readmissions and avoidable admissions.
Out-predict common approaches to readmission risk stratification by rendering more precise and complete views into patient predispositions by using patient characteristics and other comorbidity index computations in enabling the patient level predictions
Improve resource utilization and increase operational efficiency
Improve hospital rating based on lower readmission rate and increased patient satisfaction
A positive financial return is expected from the readmission and avoidable admission reduction rate. Revenue generation by decreasing the hospital’s excess readmission ratio that reduces payments for hospitals whose 30-day readmission rates are high relative to other facilities

## PROJECT DETAILS
Understanding the typical work flow on how the data science process works is important in business understanding and problem solving.
Using the OSEMN Framework the student will go through the different steps of the framework in an iterative and non-linear process.

O. Obtain the data - Requirements and information gathering on the problem.\
S. Scrubbing - Pre-processing our data (removing nulls, outliers, normalization, feature selection)\
E. Explore-Understand the cohort characteristics and impactful predictors\
M. Modeling the data - Build and tune the model\
N. iNterpret the Data and communicate results to stakeholders

## Hospital Readmissions Diabetes Data Set
[https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008](url)

The dataset represents 10 years of clinical care at 130 US hospitals and integrated delivery
networks. It includes over 50 features representing patient and hospital outcomes. Information was
extracted from the database for encounters that satisfied the following criteria.
1. It is an inpatient encounter (a hospital admission)
2. It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system
as a diagnosis.
3. The length of stay was at least 1 day and at most 14 days.
4. Laboratory tests were performed during the encounter.
5. Medications were administered during the encounter.

Features:
1. Encounter ID – Unique identifier of an encounter.
2. Patient number – Unique identifier of a patient.
3. Race – Categories: Caucasian, Asian, African American, Hispanic, and Other.
4. Gender – Categories: Male, Female, and Unknown/Invalid.
5. Age – Grouped in 10-year intervals: (0-10), (10-20), …, (90-100).
6. Weight – Patient’s weight in pounds.
7. Admission type – Integer identifier corresponding to 9 values (e.g., Emergency, Urgent,
Elective, Newborn, Not Available).
8. Discharge disposition – Integer identifier corresponding to 29 values (e.g., Discharged
to home, Expired, Not Available).
9. Admission source – Integer identifier corresponding to 21 values (e.g., Physician
referral, Emergency room, Transfer from a hospital).
10. Time in hospital – Number of days between admission and discharge.
11. Payer code – Integer identifier for 23 payer types (e.g., Blue Cross/Blue Shield,
Medicare, Self-pay).
12. Medical specialty – Integer identifier for 84 physician specialties (e.g., Cardiology,
Internal Medicine, General Practice).
13. 14. Number of lab procedures – Total number of lab tests performed during the encounter.
Number of procedures – Total number of non-lab procedures performed.
15. Number of medications – Number of distinct medications administered during the
encounter.
16. Number of outpatient visits – Number of outpatient visits in the year before the
encounter.
17. Number of emergency visits – Number of emergency visits in the year before the
encounter.
18. Number of inpatient visits – Number of inpatient visits in the year before the encounter.
19. Diagnosis 1 – Primary diagnosis (first three digits of ICD9 code).
20. Diagnosis 2 – Secondary diagnosis (first three digits of ICD9 code).
21. Diagnosis 3 – Additional secondary diagnosis (first three digits of ICD9 code).
22. Number of diagnoses – Total number of diagnoses recorded.
23. Glucose serum test result – Values: ">200", ">300", "normal", or "none" (if not
measured).
24. A1c test result – Values: ">8" (>8%), ">7" (between 7% and 8%), "normal" (<7%), or
"none" (not measured).
25. Change of medications – Indicates if there was a change in diabetes medication. Values:
"change" or "no change".
26. Diabetes medications – Indicates if any diabetes medication was prescribed. Values:
"yes" or "no".
27. Medication details (24 features) – For specific diabetes medications (e.g., metformin,
insulin, etc.), the values indicate:
- "up" (dosage increased)
- "down" (dosage decreased)
- "steady" (dosage unchanged)
- "no" (not prescribed).

## DATA-SPECIFIC INFORMATION FOR: [diabetic_data.csv]

Number of variables: 50
Number of instances/rows: 101766
Target Variable : Readmitted 
Days to inpatient readmission. Values: “<30” if the patient was readmitted in less than 30 days, “>30” if the patient was readmitted in more than 30 days, and “No” for no record of readmissionFeatures.






