## Business Problem:
Memorial Hospital has experienced significant delays in patient throughput over the last 12 months, resulting in capacity issues in the inpatient units and negatively impacting the hospital's financial and quality metrics. The hospital aims to address these delays and barriers to discharge by implementing a plan that utilizes performance metrics and industry best practices.

## Data Description:
The provided data is for inpatient throughput at Memorial Hospital for a 12-month period ending September 2020. The data includes patient ID, patient type, admit date, discharge date, length of stay (LOS), expected length of stay (GMLOS), excess days, discharge status, MS class, DRG, DRG weight, expected mortality, DRG description, primary diagnosis (Pridx), and secondary diagnoses (Secdx1-25). The data also includes COVID identifier and discharge disposition description.

## Data Dictionary:

1. Patient ID: Unique identifier assigned to each patient.
2. Patient Type: Type of patient, either inpatient or outpatient.
3. Admit Date: Date the patient was admitted to the hospital.
4. Discharge Date: Date the patient was discharged from the hospital.
5. LOS: Length of stay, measured in days, from admission to discharge.
6. GMLOS: Expected length of stay, based on the patient's diagnosis-related group (DRG).
7. Excess Days: The difference between the observed length of stay and the expected length of stay.
8. Discharge Status: Status of the patient at the time of discharge, either discharged to home/home health, post-acute care facility, or other.
9. MS Class: Medicare Severity Diagnosis Related Group (MS-DRG) class, used for Medicare reimbursement.
10. DRG: Diagnosis-related group, a classification system used to group patients with similar diagnoses and medical procedures.
11. DRG Weight: A weight assigned to each DRG based on the expected cost of treatment.
12. Expected Mortality: Predicted mortality rate for each DRG.
13. DRG Description: Description of the diagnosis-related group.
14. Pridx: Primary diagnosis for the patient.
15. Secdx1-25: Secondary diagnoses for the patient.
16. COVID Identifier: Indicates whether the patient was COVID positive or negative.
17. Discharge Disposition Description: Description of the patient's discharge disposition, either discharged to home/home health, post-acute care facility, or other.

## Tasks:

1. Complete the inpatient throughput dashboard. Calculate the key performance indicator metrics for the 12 months ending September 2020. Break out the inpatient throughput dashboard based on COVID positive cases and non-COVID positive cases.
2. Analyze performance compared to the prior year and national benchmarks. Does Memorial Hospital have an opportunity to reduce length of stay and improve throughput? Use the performance metrics to support your rationale. How does COVID impact performance?
3. Complete the discharge disposition dashboard based on the data you were given. Which disposition has the greatest ALOS and O/E LOS ratio? What are some strategies to reduce ALOS for these patients?
4. Based on your findings, please indicate which areas you would suggest focusing on to improve patient flow. What are some strategies that a hospital might look at implementing to improve hospital throughput and length of stay? Perform independent research to identify best practice.
5. For each patient day reduced, Memorial Hospital achieves a cost savings of $650. Calculate volume for patients discharged between October 2019 and September 2020. If Memorial Hospital were to achieve the GMLOS for the same patient population over the next 12 months, how many days would be reduced? Using the $650 cost per patient day, what would be the overall cost savings for the hospital?
