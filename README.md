1. **


**TASK-1**


`   `**CREDIT FLOW: SMART ETL FOR CREDIT CARD DATA**

**				

![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.001.png)                ![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.002.jpeg)
**


`                    `**Submitted By: UPPUTHOLLA VENKATA SAINADH**

`                     `**Mail: [sainadhupputholla2002@gmail.com**](mailto:sainadhupputholla2002@gmail.com)**

`                     `**Role: DATA ANALYST** 












**CONTENTS**

1. **INTRODUCTION** 

1. **OBJECTIVE**
   1. extracting data 
   1. exploring data
   1. Data Pre-processing 

1. **VISUALIZATION USING TABLEAU**
   1. over view of tableau
   1. Age interval
   1. region\_wise \_income
   1. loan\_based\_occupation
   1. card\_utilisatioin based on occupation
   1. debit\_ratio
   1. good or bad \_based\_on\_gender\_region
   1. occupation based on gender and income with card utilization
   1. occupation\_ monthly\_income
   1. dependence based on occupation with rent or own house

1. **CREATING THE DASHBOARD**

1. **IDENTIFYING GOOD AND BAD CUSTOMERS**
   1. Potential Good Customers
   1. Strategy Developments
   1. Potential Bad Customers:
   1. Strategy Developments

1. **CONCLUSION**
**


**1.INTRODUCTION**

Credit cards have become an integral part of modern financial life, offering convenience and benefits to many. However, their impact varies significantly depending on individual usage patterns.

For young adults, credit cards can be a double-edged sword. They offer a crucial tool for building credit history, essential for future loans like mortgages and car purchases. Credit cards can also provide flexibility for unexpected expenses or large purchases like college tuition. However, young adults are more susceptible to the pitfalls of overspending and accumulating debt due to limited financial experience and a tendency towards impulsive spending.

Middle-aged adults often utilize credit cards for their convenience and rewards programs. Established credit histories allow them to access credit limits that can facilitate major life events like home renovations or travel. Credit card rewards, such as cashback or travel points, can provide significant value and enhance lifestyle experiences.

Seniors may rely on credit cards for convenience in daily transactions and to maintain a good credit score for potential future needs. However, they may also be more vulnerable to scams and identity theft.

Regardless of age, responsible credit card usage is paramount. This includes understanding the terms and conditions of the card, using it within one's budget, and paying the balance in full and on time each month. Overspending can lead to accumulating high-interest debt, which can have severe long-term financial consequences.

Credit cards offer numerous benefits when used responsibly. They provide convenience, rewards, and can be a valuable tool for financial management. However, it is crucial to be aware of the potential risks and to prioritize responsible spending habits to avoid falling into the trap of debt.

**Potential Risks:**

1. Debt.
1. High Interest Rates
1. Identity Theft
1. Impulse Spending
1. Fee Charges

   ` `Overall, credit cards can be a valuable financial tool when used responsibly. It is important to understand the terms and conditions of your credit card, use it within your budget, and pay your balance in full and on time each month to avoid the negative consequences of debt.



   **2.OBJECTIVE**

   The main objective for this project is data source, for project the data should be clean without any missing values and outliers. For that purpose, before starting the project we want to check the data  

   2\.1 **extracting data** 

   The data which I used in this project or task is collected from the GitHub and extracted that data for my project purpose. 

   Here is the data set link:

   [https://github.com/sainadh2002/Credit_card_analysis/blob/main/creditcard.csv](https://github.com/sainadh2002/Credit_card_analysis/blob/main/creditcard.csv%20) 

   After extracting I observed that there are 150002 rows × 18 columns which is a large data set.

   **2.2 exploring data: understanding what data contains**

   Data exploration is the initial step in the data analysis process where you delve into a dataset to gain a comprehensive understanding of its characteristics, structure, and potential insights. Let's break down what I can understand from the data:

   **Column names and their meanings**:

- **NPA Status**: This likely indicates whether the individual is a Non-Performing Asset (NPA). NPA typically refers to loans or debts where the borrower has defaulted or is significantly behind on payments.
- **Revolving Utilization of Unsecured Lines**: This likely represents the percentage of the available credit limit that is being used on unsecured lines of credit.
- **Age**: The age of the individual.
- **Gender**: The gender of the individual.
- **Region**: The region where the individual resides.
- **Monthly Income**: The individual's monthly income.
- **Rented/Own House**: Whether the individual rents or owns their house.
- **Occupation**: The individual's occupation or profession.
- **Education**: The individual's highest level of education.
- **Days Past Due Not Worse**: This likely represents the number of days that the individual's most recent payment is overdue, but not considered "worse".


- **Monthly Income Loans**: This likely represents the ratio of monthly income to the amount of outstanding loans.
- **Number of Open Credit Lines**: The number of active credit lines the individual has (e.g., credit cards, loans).
- **Number of Times 90 Days Late**: The number of times the individual has been 90 days or more late on a payment.
- **Number of Real Estate Loans**: The number of real estate loans the individual has.
- **Number of Times 60-89 Days Past Due**: The number of times the individual has been 60-89 days late on a payment.
- **Number of Dependents**: The number of dependents the individual has.
- **Good/Bad**: This likely indicates whether the individual is considered a "good" or "bad" credit risk.

**2.3 Data Pre-processing**

Data preprocessing is a crucial step in the data analysis and machine learning pipelines. It involves transforming raw data into a clean, consistent, and usable format suitable for analysis and model training. This process is essential because real-world data is often messy and incomplete, containing inconsistencies, missing values, and outliers that can negatively impact the accuracy and reliability of your results.

First, we want to find out how many missing values are there in every column using machine learning concept and python libraries. Here, is the null values. As shown in below for every column how many null values are presented, we can see below.

`           `![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.003.png)



**Key Steps in Data Preprocessing**:

**Data Cleaning:**

1. Handling Missing Values: 
   1. Imputation: Replacing missing values with estimated values (e.g., mean, median, mode.
   1. Replacing missing values using concepts like fillna.
   1. Removing repeated values or column present in the data using dropna.
   1. Removing duplicate values in the data.  
1. Outlier Detection and Treatment: 
   1. Identifying outliers: Using visualization techniques (box plots, scatter plots) or statistical methods (Z-score, IQR).
   1. Handling outliers: Removing them, transforming them using python libraries and ml concepts.

**Tools and Libraries:**

- Python: Pandas, NumPy, Scikit-learn, marplot. 
- Tool – google Collaboratory

**CODE LINK:**

`    `**Here is the code link please go through this link.**

`     `**[https://github.com/sainadh2002/Credit_card_analysis/blob/main/credit_card.py**](https://github.com/sainadh2002/Credit_card_analysis/blob/main/credit_card.py)**

NOW, after clean the data and removing outliers, the data is ready to make visualizations here is the data set which are cleaned.

[     https://github.com/sainadh2002/Credit_card_analysis/blob/main/credit_card.csv](%20%20%20%20%20https:/github.com/sainadh2002/Credit_card_analysis/blob/main/credit_card.csv)



`                                `3.**VISUALIZATION USING TABLEAU**

**3.1 OVER VIEW OF TABLEAU**

In This project we use the software called Tableau public. Tableau Public is a free data visualization platform that allows anyone to create and share interactive dashboards and visualizations. It's a great tool for exploring data, communicating insights, and collaborating with others.

**Key features of Tableau Public include**:

- **Easy-to-use interface**: Tableau Public has a drag-and-drop interface that makes it simple to create visualizations without needing extensive technical knowledge.
- **Wide range of visualizations**: You can create various visualizations like bar charts, line charts, scatter plots, maps, and more.
- **Interactive dashboards**: Create dashboards with multiple visualizations to explore data from different angles and tell a more comprehensive story.
- **Data connectivity**: Connect to various data sources, including Excel, CSV files, Google Sheets, and more.
- **Sharing and collaboration**: Easily share your visualizations and dashboards online and collaborate with others.
- **Community**: Join a large community of data enthusiasts and learn from others.

Tableau Public is a valuable tool for anyone who wants to explore data, communicate insights, and collaborate with others. It's a great option for individuals, students, and small businesses.


`           `![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.004.png)





**3.2.AGE\_INTERVEL**



import { ocr } from 'llama-ocr';

const markdown = await ocr({
  filePath: "https://napkinsdev.s3.us-east-1.amazonaws.com/next-s3-uploads/26cee61a-203e-41e6-b0c6-993a39d00e04/AGE_INTERVEL.png",
  apiKey: process.env.TOGETHER_API_KEY
});

**Observations:**

- **Age Distribution:** The visualization appears to be a histogram representing the distribution of individuals across different age groups. The x-axis is labelled "Age (bin)", suggesting that the data has been grouped into intervals.
- **Count of Ages:** The y-axis is labelled "Count of Age", indicating the number of individuals falling within each age interval.
- **Age Intervals:** The histogram shows a clear pattern of age distribution. There's a significant peak in the middle age range, likely around 35-49 years old, suggesting a higher concentration of individuals in this age group. The counts gradually decrease towards both younger and older age groups.

**Highest Count:**

- The age group with the highest count appears to be around the **49 years** range. This is indicated by the tallest bar in the histogram which means the people with this age  is more.

**Lowest Count:**

- The age groups with the lowest counts seem to be the **oldest age groups as 104** depicted in the visualization. The bars representing these groups have the smallest heights.

**Starting Age:**

- The visualization starts with the **lowest age group** depicted on the left side of the x-axis started from 0

**Ending Age:**

- The visualization ends with the **highest age group** depicted on the right side of the x-axis ended to 109.

**3.3. REGION\_WISE \_INCOME**

![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.006.png)

**Observations:**

- r**egional Income Disparity:** The visualization clearly shows a significant disparity in monthly income across different regions. The **Central** and **West** regions have markedly **higher monthly incomes** compared to the East, South, and North regions.

- **Gender Disparity:** Within each region, there is a noticeable difference in monthly income between males and females. In most regions, males tend to have higher monthly incomes than females. This disparity is particularly evident in the Central and West regions, where the difference in income between males and females is substantial.


- **Overall Trend:** The visualization suggests a general trend of higher monthly incomes in the Western and Central regions compared to the Eastern, Southern, and Northern regions. This trend holds true for both males and females.



**3.4. LOAN\_BASED\_OCCUPATION**


![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.007.png)


**Observations:**

- **Comparison of Credit Lines and Loans:** The visualization appears to be comparing the sum of open credit lines and loans (represented by green bars) with the sum of real estate loans or lines (represented by orange bars) for different occupations.
- **Grouping by Housing Status:** The data is further grouped by whether the individual rents or owns their house.
- **Occupational Variation:** There seems to be significant variation in the number of credit lines and loans across different occupations. Some occupations have higher numbers of credit lines and loans than others.
- **Housing Status Impact:** The number of credit lines and loans also appears to differ between individuals who rent and those who own their houses.

- **Highest Total Credit Lines and Loans:**
  - **Salf - Emp** appears to have the highest number of total credit lines and loans (green bars) among the rented occupations.
  - **Sales - Emp** also appears to have the highest number of total credit lines and loans (green bars) among the owner-occupied occupations.





- **Lowest Total Credit Lines and Loans:**
  - **Officer 3** appears to have the lowest number of total credit lines and loans (green bars) among the rented occupations.
  - **Officer 3** also appears to have the lowest number of total credit lines and loans (green bars) among the owner-occupied occupations.

- **Highest Real Estate Loans/Lines:**
  - **Sales - Emp** appears to have the highest number of real estate loans or lines (orange bars) among the owner-occupied occupations.
  - **Officer 3** appears to have the highest number of real estate loans or lines (orange bars) among the rented occupations.

- **Lowest Real Estate Loans/Lines:**
  - **Officer 1** appears to have the lowest number of real estate loans or lines (orange bars) among the owner-occupied occupations.
  - **Officer 2** appears to have the lowest number of real estate loans or lines (orange bars) among the rented occupations.



**3.5.CARD\_UTILISATIOIN BASED ON OCCUPATION**


![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.008.png)

**Observations:**

- **Treemap Visualization**: The visualization uses a treemap layout, where the size of each rectangle is proportional to the revolving utilization of credit cards for each occupation.
- **Revolving Utilization**: The color gradient indicates the level of revolving utilization, with darker shades representing higher utilization.
- Based on the visualization, the occupation with the **highest revolving utilization of credit cards appears to be "Self-Emp".** This is indicated by the largest rectangle in the tree map, suggesting that this group has the highest proportion of credit card balances relative to their credit limits.
- The occupation with the **lowest revolving utilization of credit cards is likely "Officer 2".** This group has the smallest rectangle in the tree map, suggesting the lowest proportion of credit card balances relative to their credit limits.



**3.6. DEBIT\_RATIO**


![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.009.png)

**Observations:**

- **Pie Chart:** The visualization uses a pie chart to represent the distribution of debt ratios across different occupations.
- **Debt Ratio:** The size of each slice is proportional to the sum of debt ratios for that occupation. Debt ratio means monthly debt payments, Alimony living costs divided by monthly gross income.
- **Occupations:** The pie chart shows the distribution across five occupations: "Self-Emp," "Non-Officer," "Officer 3," "Officer 2," and "Officer 1."
- **"Self-Emp**" has the largest slice, indicating that this occupation group has the highest sum of debt ratios.
- **Colour Coding:** The slices are color-coded the colour code defines the  occupation.
- ` `Based on the provided visualization, the occupation with the **least debt ratio appears to be "Officer 2".**

It has the smallest slice in the pie chart, indicating that the sum of debt ratios for this occupation is the lowest among the five groups.






**3.7. GOOD OR BAD \_BASED\_ON\_GENDER\_REGION**

`                                  `![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.010.png)

**Observations:**

- **Heatmap:** The visualization uses a heatmap to represent the sum of debt ratios across different regions, genders, and categories (Good and Bad).
- **Colour Gradient:** The colour gradient ranges from red (low) to green (high), visually representing the sum of debt ratios.
- **Regional Variation:** There are clear regional variations in the sum of debt ratios. For instance, the "**West**" region generally has higher values compared to the "**East**" region.
- **Gender Differences:** Within each region, there are also differences in the sum of debt ratios between males and females.
- Based on the visualization, it appears that **Males** generally have a higher "Good" sum of debt ratios compared to Females in most regions.
- You can observe this by looking at the green cells in the heatmap. In most cases, the green cells (representing the "Good" category) for Males have higher values than the corresponding green cells for Females within the same region.
- Based on the visualization, the **West** region appears to have both high "Good" and high "Bad" sum of debt ratios.
- The West region has one of the highest values for the "**Good**" category, as indicated by the darker green cell.
- Similarly, the West region has one of the highest values for the "**Bad**" category, as indicated by the darker red cell.

This suggests that the West region has a relatively high overall debt ratio, with a significant portion attributed to both "Good" and "Bad" categories.



**3.8. OCCUPATION BASED ON GENDER AND INCOME WITH CARD UTILIZATION** 

![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.011.png)

**Observations**:

- **Tree map Visualization**: The visualization uses a treemap layout, where the size of each rectangle is proportional to the sum of monthly income for each occupation and gender combination.
- The occupations are grouped into "Officer" and "Non-Officer" categories, and further divided by gender (Male and Female).
- The colour gradient ranges from blue to red, likely indicating the level of utilization (although the exact mapping is not explicitly stated).
- Dominant Group: The "Male, Self-Emp" group has the largest area, suggesting the highest sum of monthly income.
- Gender Disparity: There appears to be a noticeable difference in the size of rectangles between males and females within the same occupation, suggesting a potential gender-based income disparity.
- Utilisation of card usage also show In the visualisation.



**3.9 OCCUPATION\_ MONTHLY\_INCOME**

`      `![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.012.png)

**Observations**:

- **Heatmap Visualization**: The visualization uses a heatmap to represent the sum of monthly income across different occupations and education levels. 
- The colour gradient ranges from red to green, visually representing the sum of monthly income, with darker shades indicating higher income. 
- The occupations are categorized into "Non-officer," "Officer 1," "Officer 2," "Officer 3," and "Self-Emp," and the education levels are grouped into "Graduate," "Matric," "PhD," "Post-Grad," and "Professional." 
- Income Variation: There is significant variation in the sum of monthly income across different occupations and education levels. Some cells are coloured darker, indicating higher income levels. 
- The "Self-Emp" and "Non-Officer" occupations generally have larger income values compared to the "Officer" occupations across most education levels. 
- The impact of education on income seems to vary across occupations. For example, "Self-Emp" appears to have a strong correlation between education and income, with higher income levels associated with higher education levels. 
- the visualization effectively communicates the relationship between occupation, education, and monthly income, highlighting the variations in income across different combinations of these factors. 

**3.10. DEPENDENCE BASED ON OCCUPATION WITH RENT OR OWN HOUSE**

`     `![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.013.png)

**Observations:**

- **Bar Chart:** The visualization uses a bar chart to represent the sum of the number of dependents for each occupation, broken down by whether the individual owns or rents their house.
- **Occupation Groups:** The occupations are categorized into "Non-officer," "Officer 1," "Officer 2," "Officer 3," and "Self-Emp."
- **Housing Status:** The data is further divided into two categories: "Own House" and "Rented."
- The "Self-Emp" occupation has the highest number of dependents across both housing statuses, with "non-Officer" following closely.
- The number of dependents appears to vary slightly between individuals who own their houses and those who rent. For example, "Self-Emp" individuals who own their houses have a higher number of dependents compared to those who rent.
- Overall, the visualization effectively communicates the relationship between occupation, housing status, and the number of dependents, highlighting the variations in the number of dependents across different combinations of these factors.

`                         `**4.CREATING THE DASHBOARD	![](Aspose.Words.acb7b12d-8087-4839-8bba-0b666d175aca.014.png)**

**Main Key Points from the Dashboard:**

**1. Income Distribution:**

- **Age Distribution:** The age group with the highest concentration appears to be between 35-49 years.
- **Regional Income:** There's a significant income disparity across regions, with the West and Central regions showing higher monthly incomes compared to the East, South, and North.
- **Gender Disparity:** Within each region, males tend to have higher monthly incomes than females.

**2. Loan and Credit Utilization:**

- **Credit Utilization:** "Self-Emp" individuals exhibit the highest revolving credit utilization, indicating they are using a significant portion of their available credit.
- **Loan Usage:** "Self - Emp" appears to have the highest number of both open credit lines and loans, as well as real estate loans.

**3. Debt Ratios:**

- **High Debt:** "Self-Emp" individuals have the highest sum of debt ratios, suggesting a higher level of overall debt.
- **Lowest Debt:** "Officer 2" has the lowest sum of debt ratios.

**4. Income and Education:**

- "Self-Emp" and "Non-Officer" occupations generally have higher monthly incomes across most education levels.
- Higher education levels are associated with higher income levels, particularly for "Self-Emp" individuals.

**5. Dependents:**

- "Self-Emp" individuals have the highest number of dependents across both housing statuses.

`                    `**5. IDENTIFYING GOOD AND BAD CUSTOMERS**

**5.1 Potential Good Customers:**

- **Low Debt Ratio:** Customers with lower debt ratios, such as individuals in the "Officer 2" category, are generally considered less risky.
- **Stable Income:** Individuals with stable and consistent income sources, such as those in certain "Officer" roles or with higher education levels, are likely to be good customers.
- **Low Credit Utilization:** Customers with low revolving credit utilization, indicating responsible credit management, are less likely to default on loans.
- **Positive Payment History:** While not explicitly shown in the dashboard, a history of on-time payments on loans and credit cards is a strong indicator of good creditworthiness.

**5.2 Strategy Development:**

- Higher Credit Limits: Increased spending power and flexibility.
- Lower Interest Rates: Reduced borrowing costs and potential for savings.
- Exclusive Rewards Programs: Access to points, miles, or cash back at higher earning rates.
- Savings on maintenance costs.
- Priority Customer Service: Dedicated support channels and faster resolution of issues.
- Exclusive Deals and Discounts while using credit cards
- Personalized assistance with travel arrangements, event bookings, and other lifestyle needs.
- Access to Exclusive Events: Invitations to concerts, sporting events, and other exclusive experiences.
- Improved Credit Score: Continued responsible credit card use can further enhance creditworthiness.
- Easier Loan Approvals: Better chances of securing loans at favourable terms.






**5.3 Potential Bad Customers:**

- **High Debt Ratio:** Customers with high debt ratios, especially those in the "Self-Emp" category, may be at higher risk of default.
- **High Credit Utilization:** Customers with high revolving credit utilization may be over-reliant on credit and more prone to financial difficulties.
- **Unstable Income:** Individuals with unstable or low income, such as those in certain regions or with lower education levels, may be at higher risk of defaulting on loans.
- **Negative Payment History:** A history of late payments or defaults on loans and credit cards is a strong indicator of bad creditworthiness.
- Due to dependency on self-emp there living cost increases and there are unable to pay money in time and they can’t maintain the credit card.

4. **Strategy Development:**

- Increased Fees and Interest Rates: Charging higher fees for missed payments.
- Penalty APRs: Applying significantly higher interest rates on outstanding balances after missed payments.
- Over-the-Limit Fees: Charging fees for exceeding the credit limit.
- Lowering the available credit limit to reduce the risk of further debt accumulation.
- In extreme cases, closing the credit card account altogether, preventing further use.
- Internal Collections: Employing internal teams to contact the customer via phone, email, or mail to recover the outstanding debt.
- External Collection Agencies: Outsourcing debt collection to third-party agencies.
- Reporting negative payment history to credit bureaus, which can negatively impact the customer's credit score.

  .












**6.CONCLUSION**

In conclusion, credit card users can be broadly categorized as "good" or "bad" based on their creditworthiness and usage behaviour. Good credit card users demonstrate responsible financial habits by making timely payments, staying within credit limits, and maintaining a low debt-to-credit ratio. This behaviour is rewarded by banks through benefits like lower interest rates, higher credit limits, and exclusive rewards. Conversely, bad credit card users struggle with timely payments, carry high balances, and often exceed their credit limits. This behaviour results in penalties, increased interest rates, and potential damage to their credit score. Responsible credit card usage is crucial for building a strong financial foundation and avoiding the pitfalls of debt.
**


- **Project work sheet:**

  We can go through my project work which we can understand more information on project. Here is the project link 

<https://public.tableau.com/app/profile/venkata.sainadh.upputholla/viz/CREDIT_CARD/AGE_INTERVEL?publish=yes>
2

