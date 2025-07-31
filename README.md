## Healthcare-Data-Analysis

This project uses SQL to perform data analysis on a healthcare dataset from Kaggle. The analysis provides insights into various aspects of patient data, including demographics, medical conditions, financial information, and hospital performance.

Key Features and Analyses:
Data Overview & Basic Statistics: The project explores the dataset to understand patient information, including the total number of records, and the maximum and average ages of patients.

Medical Conditions & Medications: The analysis identifies prevalent medical conditions and the frequency of prescribed medications for those conditions.

Insurance Providers & Hospitals: The project examines patient preferences for insurance providers and hospitals to assist with resource allocation and understanding service prominence.

Financial Analysis & Duration of Hospitalization: The analysis scrutinizes financial data by looking at average billing amounts for different medical conditions and the total billing amounts and durations of hospital stays.

Blood Type Analysis & Donation Matching: The project explores the distribution of blood types and includes a stored procedure named 'Blood_Matcher' to identify potential donors and recipients.

Yearly Admissions & Insurance Analysis: The analysis identifies hospitals with patient admissions in specific years (2024 and 2025) and examines billing patterns across different insurance providers.

Patient Risk Categorization: A new column was created to categorize patients into high, medium, or low-risk categories based on their medical conditions and test results.

Dataset Column Descriptions:
Name: The name of the patient.

Age: The patient's age in years at the time of admission.

Gender: The patient's gender ("Male" or "Female").

Blood Type: The patient's blood type (e.g., "A+", "O-").

Medical Condition: The primary medical diagnosis (e.g., "Diabetes," "Hypertension," "Asthma").

Date of Admission: The date the patient was admitted.

Doctor: The name of the doctor responsible for the patient's care.

Hospital: The name of the hospital where the patient was admitted.

Insurance Provider: The patient's insurance provider (e.g., "Aetna," "Blue Cross," "Cigna").

Billing Amount: The cost of healthcare services.

Room Number: The patient's room number.

Admission Type: The type of admission ("Emergency," "Elective," or "Urgent").

Discharge Date: The date the patient was discharged.

Medication: A medication prescribed to the patient (e.g., "Aspirin," "Ibuprofen").

Test Results: The outcome of a medical test ("Normal," "Abnormal," or "Inconclusive").
