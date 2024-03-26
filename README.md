# Bike Sales Analysis using Excel
This repository includes an Excel file containing the analysis of bike sales using a dataset provided by Alex The Analyst. I did some data cleaning and created a dashboard in Excel. 

## Data cleaning and preprocessing
- Removed duplicates by clicking the 'Remove Duplicates' in the Data tab of Excel.
- Re-formated values for the Income column
- Made abbreviations clear for Martial Status and Gender columns. The gender column had values like 'M' and 'F'; I replaced them with 'Male' and 'Female'. Marital Status had values of 'S' and 'M' and were replaced with ' Single' and 'Married'. 
- Added an age brackets column obtained from the Age column using the IF function, where I grouped ages: Adolescent (< 31), Middle Age (31–54), and Old (> 54). By using age brackets it makes it easier to categorize; as a result, this facilitates analyzing and interpreting the data.
  * ```
    =IF(L2 > 54,"Old",IF(L2 >= 31,"Middle Age",IF(L2 < 31,"Adolescent","Invalid")))
    ```
## Pivot Tables and Charts
<p>Average income for someone who purchases a bike based on gender</p>

<img src="https://github.com/plant-haven/PowerBiProjects/assets/94200274/346d7dd4-580a-4ec4-8bb1-496af7f85d0f" width="400" height="100" >
<p><img src="https://github.com/plant-haven/PowerBiProjects/assets/94200274/d646feff-2d7f-4f1f-b310-8eaf8ff08824" width="400" height="250" ></p>

<p>Count of purchased bikes based on commute distance</p>
<img src="https://github.com/plant-haven/PowerBiProjects/assets/94200274/b4371998-4548-4f78-b489-7f36ef7778ee" width="400" height="150">
<p><img src="https://github.com/plant-haven/PowerBiProjects/assets/94200274/8ad3aed3-6212-4a71-b755-c4389261ee11" width="400" height="250"></p>

<p>Count of purchased bikes based on age bracket</p>
<img src="https://github.com/plant-haven/PowerBiProjects/assets/94200274/61502554-94f8-43cc-ace6-2aee599458cc" width="400" height="120">
<p><img src="https://github.com/plant-haven/PowerBiProjects/assets/94200274/d64e8a93-ca19-4503-a3c0-4e3e1c29a54b" width="400" height="250"</p>
  
## Dashboard
![image](https://github.com/plant-haven/PowerBiProjects/assets/94200274/6ab25bd4-dd31-475c-99dd-c78c7f041725)

