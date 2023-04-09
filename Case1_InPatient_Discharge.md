
## Problem Set:
1. What is the effect of the COVID-19 pandemic on the patient population of Memorial Hospital?
2. How has the pandemic affected the comorbidity rates and the observed vs. expected mortality ratio of the hospital?
3. What are the observations regarding the impact of COVID-19 on the hospital's patient population?
4. What recommendations can be made to improve the comorbidity rates and observed/expected mortality ratio during the pandemic?\

## Goal:
The goal of the analysis is to determine the impact of the COVID-19 pandemic on Memorial Hospital's patient population and to make recommendations to improve the comorbidity rates and observed/expected mortality ratio during the pandemic.</p><p>Data Description:
The data provided in the 'Inpatient Discharges' Excel file contains a full year of Memorial Hospital's discharge data from 10/1/2019 to 9/30/2020. The data includes the patient ID, patient type, admit date, discharge date, length of stay (LOS), geometric mean length of stay (GMLOS), discharge status, medical/surgical identifier, DRG (diagnosis-related group) code, DRG weight, expected mortality rate associated with the DRG, DRG description, and up to 25 diagnosis codes assigned to the patient encounter. The data is to be analyzed both including and excluding COVID-19 patients. A patient with a diagnosis of COVID-19 is identified by the diagnosis code of U07.1, which became available on 4/1/2020.</p>
 
 
## Data Dictionary:
1. Patient ID: A unique identifier for each patient.
2. Patient Type: Indicates whether the patient was admitted as an inpatient or outpatient.
3. Admit Date: The date on which the patient was admitted to the hospital.
4. Discharge Date: The date on which the patient was discharged from the hospital.
5. Length of Stay (LOS): The number of days the patient stayed in the hospital.
6. Geometric Mean Length of Stay (GMLOS): The average length of stay for patients with the same DRG.
7. Discharge Status: Indicates whether the patient was discharged alive, dead, or transferred to another facility.
8. Medical/Surgical Identifier: Indicates whether the patient was admitted for a medical or surgical reason.
9. DRG Code: A unique code assigned to each patient based on their diagnosis and procedures performed during their hospital stay.
10. DRG Weight: A number assigned to each DRG that reflects the relative cost of treating patients with that diagnosis.
11. Expected Mortality Rate: The percentage of patients with the same DRG who would be expected to die during their hospital stay based on historical data.
12. DRG Description: A description of the diagnosis and procedures associated with the DRG code.
13. Pridx: The primary diagnosis code assigned to the patient.
14. Secdx1 - Secdx25: Up to 25 secondary diagnosis codes assigned to the patient.

## Terminology:
1. DRG: Diagnosis-Related Group is a system used by Medicare to categorize hospital cases into groups that are expected to have similar costs based on patient characteristics and the services provided.
2. Expected Mortality Rate: The percentage of patients with the same DRG who would be expected to die during their hospital stay based on historical data.
3. Pridx: Primary diagnosis code assigned to the patient.
4. Secdx1 - Secdx25: Secondary diagnosis codes assigned to the patient.
5. LOS: Length of Stay, the number of days the patient stayed in the hospital.
6. GMLOS: Geometric Mean Length of Stay, the average length of stay for patients with the same DRG.


 --------
