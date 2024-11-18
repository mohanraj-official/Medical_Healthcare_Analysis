<center><h1> EXCEL CAPSTONE PROJECT - MEDICAL HEALTHCARE ANALYSIS</h1></center>

|Problem Statement|
|-------------------|
|The healthcare industry generates vast amounts of data daily, providing valuable insights for healthcare providers and policymakers to improve patient care, allocate resources effectively, and manage healthcare costs. This project aims to analyze a comprehensive healthcare dataset comprising medical examinations, hospitalization details, and customer profiles to extract insights into patient health profiles, medical histories, and healthcare costs. By exploring relationships between various health metrics, identifying trends, and visualizing key patterns, we aim to deliver actionable insights to healthcare stakeholders for informed decision-making through rigorous data cleaning, transformation, exploration, and analysis.|

<br>

|Dataset Download|
|---------------|
|https://drive.google.com/uc?export=download&id=1zelh7bZrE7F290QtTABHgHYn4B7JDbZO|

<br>

| Data Cleaning|
|------------|
|1. Check for the number of missing values marked with '?' in each column of the “Medical Examinations” Table and "Hospitalization Details" Table.|
|2. Fill in the missing values of ‘month’ with Sep and ‘year’ with its average rounded to the nearest integer.|
|3. Determine the most frequently occurring values in the ‘smoker’, 'Hospital tier', and 'City tier' columns, and fill in the missing values accordingly.|
|4. If any 'State ID' values are missing, consider filling them with 'Unknown' or using another appropriate strategy.|

<br>





| Data Transformation|
|---------|
|1. Split the ‘names’ column in the “Customer Names” Table into 3 meaningful columns: ‘Title’,
‘First Name’, and ‘Last Name’.|
|2. Convert the "NumberOfMajorSurgeries" column in the “Medical Examinations” Table to numerical data by replacing non-numeric characters with meaningful numerical values.|
|3. Check for inconsistencies in the 'Heart Issues' and 'Smoker' columns and propose corrective actions if necessary.|

4. Create a new column named “Weight Status” that categorizes BMI into different categories as below:

|BMI| Weight Status|
|------------|-----------|
|Below 18.5| Underweight|
|18.5 – 24.9 |Healthy Weight|
|25.0 – 29.9 |Overweight|
|30.0 and Above| Obesity|

<br>

5. Create a new column named “Diabetes Status” and fill it as per the information given below:

| HbA1C | Diabetes Status|
|----------|------------|
|Below 5.7 | Normal      |
|5.7 – 6.4 | Prediabetes |
|6.5 and Above | Diabetes|

<br>

|     |
|----|
|6. Merge the ‘year’, ‘month’, and ‘date’ columns in the “Hospitalization Details” Table into one column named ‘Date of Birth’ and format it in ‘DD-MMM-YYYY’ custom format.|
|7. Calculate the ‘Age’ of each customer based on their ‘Date of Birth’ and the date of collection of the dataset, which is 8th June 2023.|
|8. Format the ‘charges’ column as currency ($).|

<br>

### Data Exploration:

|Customer Names Table|
|----|
|1. Are there any duplicate Customer IDs in the dataset? If yes, how many?|
|2. How many customers are included in the dataset?|

<br>

|Medical Examination Table|
|-----|
|1. How many customers have a history of cancer?|
|2. Identify the customer(s) with the highest BMI.|
|3. How many customers have Diabetes?|
|4. How many obese customers have heart issues?|
|5. What is the total number of major surgeries performed on customers?|
|6. Calculate the percentage of customers who have undergone any transplants.|
|7. Find the average HBA1C value of customers who are smokers.|
|8. How many customers with heart issues have done transplants?|
|9. What is the average BMI of the customers who have done more than 2 major surgeries?|

<br>

|Hospitalization details Table|
|-----|
|1. Calculate all the Summary statistics for the ‘charges’ column.|
|2. Which is the median age and the most common age in the dataset?|
|3. Find the average hospitalization charges for customers who are more than 50 years old.|
|4. Compare the total charges across different hospital tiers.|
|5. Which city tier has the highest average hospitalization charges?|
|6. Calculate the average charges for people who have more than 2 children.|
|7. Find the integer average number of children of customers who are less than 40 years old.|

|1 - Customer Names|
|----|
|![Screenshot (59)](https://github.com/user-attachments/assets/76b00f2d-90c1-45b3-b626-55fa97f154a0)|

<br>

|2 - Medical Examinations|
|-------|
|![Screenshot (60)](https://github.com/user-attachments/assets/08d36f43-dd19-44d7-b85b-e6a7c6522821)|

|3 - Hospitalization Details|
|-----|
|![Screenshot (61)](https://github.com/user-attachments/assets/7bd7b6ea-97d8-419d-ab7e-ec8b60a9773c)|

|4 - Data Exploration|
|-----|
|![Screenshot (62)](https://github.com/user-attachments/assets/018d79cb-420a-4312-b87f-84bb0e1ae94f)|

|5 - Healthcare|
|-----|
|![Screenshot (64)](https://github.com/user-attachments/assets/e8a89707-774b-48d7-bf27-77155415bd7d)|

<br>

|1) What is the distribution of cancer history among smokers and non-smokers?|
|--------|
|![Screenshot (65)](https://github.com/user-attachments/assets/7efedfad-545f-4860-aa6d-8565a89f1c96)|

<br>

|2) How does the total number of major surgeries and average HbA1C differ between patients with and without a history of transplants?|
|-----|
|![Screenshot (66)](https://github.com/user-attachments/assets/a7f2d559-34cd-44bb-ad78-5f638cc46cf9)|

<br>

|3) How do healthcare charges vary based on different weight statuses and diabetes statuses?|
|--------------|
|![Screenshot (67)](https://github.com/user-attachments/assets/fe9b1b2c-57da-45b0-9d56-eeae049595d9)|

<br>

|4) Can you compare the average charges for each hospital tier within different states?|
|-------|
|![Screenshot (68)](https://github.com/user-attachments/assets/3f6b50e1-2ffb-43b7-b76a-a2b424473a86)|

<br>

|5) Is there any correlation between age and both BMI and HbA1C in the dataset?|
|-------------|
|![Screenshot (69)](https://github.com/user-attachments/assets/6c5adb0d-a792-4eb5-9b7d-188b84d251ad)|

<br>

|6) Explore the relationship between age and healthcare charges.|
|-----------------|
|![Screenshot (70)](https://github.com/user-attachments/assets/c391aa77-76bf-4882-bc61-df95c4cd7f46)|

In this Excel Series, we can cross all these categories like

* DATASET CREATION
* DATASET EXPLORATION
* DATASET CLEANING
* DATASET TRANSFORMATION
* DATASET OPERATION
* DATA ANALYSIS

