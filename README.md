 **1. **Data Overview****
 
  The dataset used in this analysis is named Cost of Living and contains **201 rows** and **5 columns**. It provides information about the average income and living expenses of different countries across various regions and years. The dataset includes variables such as country, region, year, average monthly income, and cost of living, representing essential economic indicators for comparing living standards globally This dataset serves as a foundation to explore how income levels relate to living costs and how these patterns differ across world regions.
  
**2. **Data Cleaning****

   For the column **Average Monthly Income**, two values were missing.
   
   I calculated the median of the income column in Excel and filled the missing entries with this value.
   
   **Reason:** Income data often contains outliers (very high or low values). Using the median prevents distortion of the dataset and maintains a more accurate central representation compared to the mean.
   
   In the column **Region**, two values were missing.
   
   I checked the dataset and saw that all other rows classify Mexico as North America. Therefore, I filled the missing region with North America
   
   **Reason:** Mssing data should be handled to keep accuracy and consistency. Since other records show Mexico as “North America,” filling the missing value this way ensures data integrity.

   After cleaning, the dataset contains **199 rows** and **5 columns**. All missing and duplicate values were successfully handled, resulting in a clean, consistent dataset.
   
 **Handling Duplicates**
 
 During the cleaning process, I detected duplicate records and removed 2 duplicate rows using the Remove Duplicates tool in Excel.
 
 **Reason**: Removing duplicate records prevents distorted statistical results and ensures data accuracy.

 **3. Descriptive Analytics**

**KEY INSIGHT 1: Average Cost of Living by Region**

<img width="392" height="216" alt="image" src="https://github.com/user-attachments/assets/bdded253-fb3d-4acc-93ec-9df4bc4cef2a" />


This chart illustrates the average cost of living across different regions.										
At about 191,000, North America has the highest cost of living, followed by Asia at about 171,000 and Europe at about 160,000.							Africa (71,000) and South America (57,000) have the lowest expenses, indicating more cheap living circumstances, while Oceania is in the middle with about 86,000.	

**KEY INSIGHT 2: Average Monthly Income by Region**

<img width="363" height="241" alt="image" src="https://github.com/user-attachments/assets/5aa0735f-f6d7-4a1c-9e96-bdefd92bc085" />

The average monthly income by region is shown in the chart. 									
While Oceania, Africa, and South America have lower average wages, Europe, Asia, and North America stand out for having greater income levels. 									
The economic disparity between industrialized and developing nations is reflected in this.					

**Summary:** The two figures show that Europe and Asia seem to have a decent balance between income and living expenses, which makes it easier for people to save money. 													
However, while having greater incomes, North America has higher expenses. Africa and South America, on the other hand, exhibit less financial comfort due to their low incomes and low expenditures. 													
In general, established regions offer better living standards and financial stability, while emerging regions still struggle economically.												





  
