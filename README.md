# EXCEL CAPSTONE PROJECT - MEDICAL HEALTHCARE ANALYSIS

---

## Problem Statement
The healthcare industry generates vast amounts of data daily, providing valuable insights for healthcare providers and policymakers to improve patient care, allocate resources effectively, and manage healthcare costs.  
This project analyzes a comprehensive healthcare dataset comprising medical examinations, hospitalization details, and customer profiles to extract insights into patient health profiles, medical histories, and healthcare costs.  
By exploring relationships between various health metrics, identifying trends, and visualizing key patterns, we aim to deliver actionable insights to healthcare stakeholders for informed decision-making through rigorous data cleaning, transformation, exploration, and analysis.

---

## Dataset Download
[Download the dataset](https://drive.google.com/uc?export=download&id=1zelh7bZrE7F290QtTABHgHYn4B7JDbZO)

---

## Data Cleaning
1. Check for missing values (`?`) in each column of the **“Medical Examinations”** and **"Hospitalization Details"** tables.  
2. Fill missing values in:
   - `month`: Use "Sep".
   - `year`: Use the average rounded to the nearest integer.  
3. Fill missing values in:
   - `smoker`, `Hospital tier`, `City tier`: Use the most frequently occurring value.  
4. For missing `State ID` values, fill with "Unknown" or another suitable strategy.

---

## Data Transformation
1. Split the `names` column in the **“Customer Names”** table into:
   - `Title`, `First Name`, and `Last Name`.  
2. Convert `NumberOfMajorSurgeries` in the **“Medical Examinations”** table to numerical data by replacing non-numeric characters.  
3. Check for inconsistencies in the `Heart Issues` and `Smoker` columns and propose corrections.  
4. Create a new column **“Weight Status”** based on BMI:

   | BMI            | Weight Status     |
   |----------------|-------------------|
   | Below 18.5     | Underweight       |
   | 18.5 – 24.9    | Healthy Weight    |
   | 25.0 – 29.9    | Overweight        |
   | 30.0 and Above | Obesity           |

5. Create a new column **“Diabetes Status”** based on HbA1C:

   | HbA1C          | Diabetes Status |
   |----------------|-----------------|
   | Below 5.7      | Normal          |
   | 5.7 – 6.4      | Prediabetes     |
   | 6.5 and Above  | Diabetes        |

6. Merge the `year`, `month`, and `date` columns in **“Hospitalization Details”** into `Date of Birth` (format: `DD-MMM-YYYY`).  
7. Calculate each customer's age based on `Date of Birth` (dataset collected on **8th June 2023**).  
8. Format the `charges` column as currency (`$`).  

---

## Data Exploration

### Customer Names Table
1. Are there any duplicate Customer IDs? If yes, how many?  
2. What is the total number of customers in the dataset?

---

### Medical Examination Table
1. Number of customers with a history of cancer?  
2. Customer(s) with the highest BMI?  
3. Number of customers with Diabetes?  
4. Number of obese customers with heart issues?  
5. Total number of major surgeries performed?  
6. Percentage of customers who have undergone transplants?  
7. Average HbA1C value of smokers?  
8. Number of customers with heart issues who have done transplants?  
9. Average BMI of customers with more than 2 major surgeries?

---

### Hospitalization Details Table
1. Summary statistics for the `charges` column.  
2. Median and most common age in the dataset.  
3. Average hospitalization charges for customers aged above 50.  
4. Total charges across different hospital tiers.  
5. City tier with the highest average hospitalization charges.  
6. Average charges for customers with more than 2 children.  
7. Average number of children (integer) for customers under 40.

---

## Data Visualizations

1. **Distribution of cancer history among smokers and non-smokers:**  
   ![Cancer Distribution](https://github.com/user-attachments/assets/7efedfad-545f-4860-aa6d-8565a89f1c96)  

2. **Comparison of major surgeries and HbA1C for patients with/without transplants:**  
   ![Transplants Comparison](https://github.com/user-attachments/assets/a7f2d559-34cd-44bb-ad78-5f638cc46cf9)  

3. **Healthcare charges based on weight and diabetes statuses:**  
   ![Charges by Status](https://github.com/user-attachments/assets/fe9b1b2c-57da-45b0-9d56-eeae049595d9)  

4. **Average charges by hospital tier within states:**  
   ![Charges by Tier](https://github.com/user-attachments/assets/3f6b50e1-2ffb-43b7-b76a-a2b424473a86)  

5. **Correlation between age, BMI, and HbA1C:**  
   ![Correlation Analysis](https://github.com/user-attachments/assets/6c5adb0d-a792-4eb5-9b7d-188b84d251ad)  

6. **Relationship between age and healthcare charges:**  
   ![Age vs Charges](https://github.com/user-attachments/assets/c391aa77-76bf-4882-bc61-df95c4cd7f46)  

---

## Key Steps in This Series:
- **Dataset Creation**  
- **Dataset Exploration**  
- **Dataset Cleaning**  
- **Dataset Transformation**  
- **Dataset Operation**  
- **Data Analysis**
