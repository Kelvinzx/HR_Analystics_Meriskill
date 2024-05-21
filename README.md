# HR ANALYTICS

 ## Project Highlights:
This project was a deep dive into HR analytics and data visualization. It included:
- Extensive data cleaning to ensure data accuracy.
- Leveraging DAX functions for attrition rate calculations and insightful analytics.
- Designing a user-friendly, interactive dashboard for HR insights.
- Extracting actionable insights to drive effective talent retention strategies.

## Tasks to perform

- **Data Cleaning:**
  
 Deleting redundant columns
 
 Renaming the columns.
 
 Dropping duplicates.
 
 Cleaning individual columns.
 
 Remove the NaN values from the dataset
 
 Check for some more Transformations

 ### Data Visualization:
 Plot a correlation map for all numeric variable Overtime
 
 Marital Status 
 
 Job Role 
 
 Gender
 
 Education Field
 
 Department 
 
 Business Travel
 
 Relation between Overtime and Age
 
 Total Working Year
 
 Education Level
 
 Number of Companies Worked
 
 Distance from Home
 
*I downloaded the dataset and uploaded the data using the "Get Data" option in 
Power BI. Then, I utilized the "Transform" option to check for any null values 
in the dataset*
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### HR Attrition Dashboard 1

**DEMOGRAPHICS**

*A demographic report summarizes employee statistic, including age groups, gender, distance from home, and marital status, providing insights  into workforce diversity and commuting patterns for informed decision-making.*

<img width="620" alt="Demograph" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/19491d11-dc7d-4d68-a91f-6c73503635dd">

## Analysis of the Demographics Dashboard
### STEP 1:

**Total Employees is 1470 using card visulas** <img width="294" alt="card" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/149cbb40-52f9-4495-8f1d-a08391c23b1b">
*Using the "Format Visual" option, you can customize the design of the card as 
needed.*

### STEP 2:  **Total attrition by education field by clustered bar chart**

<img width="423" alt="222" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/9d5fcad3-9da8-4e31-8836-6841ba70c956">

### STEP 3:
<img width="539" alt="333" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/09bd690c-fcb4-44b8-8fd1-1969018b6bed"> 

- To obtain the counts of 237 and 1233, follow these steps:
 
1. Navigate to the table view, click "New Column," and apply the provided 
formula.
<img width="262" alt="3333" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/e560f291-aa84-4a96-82ab-4bb3398b9db2">

<img width="597" alt="Screenshot 2024-05-11 143716" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/4c2fc0da-c267-411f-8f48-bf9972df5c8a">

- This will yield the desired results: if "Attrition" is "Yes," the count is 1; 
if it's "No," the count is 0.


<img width="280" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/e559ad21-4eea-4281-b19a-e38e666799b3">  <img width="263" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/3563012f-8daa-4aec-894c-ab770cc6eb8a">

- Summing all the 1s gives the total attrition count that is 237 
- And subtracting this from the employee count yields the count of active 
employees that is 1233
<img width="556" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/b2a59424-bfe6-42ef-9c8b-0b5307bed15a">
<img width="178" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/26761739-e9aa-47c6-a075-40f6136001e9">

- By dragging and dropping it in the field u will get the active employees

  ### STEP 4: **8Using data groups for making better visuals. Using groups, you can aggregate certain values together to form meaningful subsets**

  <img width="458" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/2f9b1f97-2e1d-4dac-ab45-e0f3884bfc58">

  I create these three visuals using the concept of grouping to organize 
and display the data effectively.

Choose the column u want to group
<img width="170" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/f061f219-454a-4a8f-aa56-778863402595">


- Change the group type from BIN to LIST

<img width="495" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/6fab3cae-9f5c-4f78-8be3-d728d02cd800">

- Change From bin to list

  <img width="504" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/0a46d526-744f-491f-9595-5120a287ed60">

- Group 1 as "Bad", 2 as "Average", 3 as "Good", and 4 as "Excellent."
- A new group is created 
- Then drag and drop in the fields.

  <img width="628" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/d3eb3df1-9288-4f64-b8ff-0cf36db3beb8">
  <img width="149" alt="Screenshot 2024-05-11 150850" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/a9467179-c168-45fe-ba5a-d2863165722c">


        - Follow the same grouping steps for “AGE” and distance from home.
        - For distance from home, 1-10 is considered near, 10-20 is considered far and 20 – 30 is considered very far
<img width="785" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/1206e1d1-fb01-475d-a823-778fd086f70c">   <img width="786" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/8de876d0-5eb6-4b06-9b1d-45a20e2c1d26">



### STEP 5: **Total attrition by marital status using stacked column chart.**

<img width="631" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/1d78075f-0edd-4317-818a-a8f01300ff43">   <img width="142" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/69b4920e-3745-4de6-a40b-78bc5fc7ef7e">

### STEP 6: **Gender count using donut chart.**

<img width="152" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/9a10c702-2765-45da-b1b8-fad04f317cb3">   <img width="314" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/a15997ac-c9c3-4d01-8e68-36693b6561f5">

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### HR Attrition Dashboard 2

 **TURNOVER ANALYSIS 1**

<img width="619" alt="turn1" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/e77d6207-28a7-4544-886c-1c67009f7cfd">



**STEP 1:** 
**Total attrition by job role.**

<img width="764" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/ba93e672-16ea-4098-971d-fb61f6ddb48d"> <img width="136" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/228dbbf0-15a9-4f08-9960-72fb1bc49956">


**STEP 2:**

- **Total attrition by business travel by stacked column chart.**

  <img width="796" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/d9dc0f79-726c-4fe6-a2a0-6fdfc089e127">

- **Total attrition by department using the donut chart**.

  <img width="793" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/9a70095d-c5e0-44d1-968a-89db4eb09810">

- **Total attrition by years in current role using stacked column chart**

  <img width="797" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/c86827bd-460f-4c74-9d2b-2731f623dfd3">

-  **Total attrition by job role**

  <img width="284" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/dcb2c94f-1388-4988-8328-686550a9b7a1"> <img width="131" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/f6685134-13b8-410a-ad45-8c3b5c4053b0">
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### HR Attrition Dashboard 3

**TURNOVER ANALYSIS 2**

<img width="658" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/2b6be736-b175-43df-b964-36303dba5f58">
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### HR Attrition Dashboard 4

**EMPLOYEE WELLNESS**

<img width="618" alt="image" src="https://github.com/Kelvinzx/HR_Analystics_Meriskill/assets/147884934/5e5443e8-2550-417d-9af4-30ceb097f8e2">






















