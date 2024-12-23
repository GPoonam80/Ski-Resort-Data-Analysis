# Ski-Resort-Data-Analysis

To analyze a dataset of ski resorts to gain insights into various aspects of the ski industry, such as resort popularity, pricing, and amenities.

![Title Slide 2](https://github.com/user-attachments/assets/002f78f5-c30f-4e25-a535-2325ec99d4b6)




## Data Analysis Project 📊
Welcome to my Data Analysis project! This project showcases the steps I took to analyze a dataset, clean it, and extract meaningful insights using various technical tools and techniques. Below is an overview of the key sections of this project.

---


### Introduction 👋
This project demonstrates the complete process of data analysis, from data cleaning to final recommendations. The goal was to explore a real-world dataset, perform necessary data cleaning, analyze trends, and derive actionable insights using various tools such as Excel, Pivot Tables and Visualisation charts. 
- **Objective:** To analyse a dataset of ski resorts to gain insights into popularity, pricing, amenities, and customer satisfaction.
- **Tools Used:** Google Sheets
- **Key Deliverables:** Visualizations, Pivot Tables and Actionable Insights.




### Data Analysis Process 🔍
In this section, I walk through the step-by-step process of how data was cleaned, pre-processed, and analyzed to ensure the most accurate insights. Each phase is vital to ensure the integrity of the final results.

#### Steps Taken:
- **Data Formatting:** Corrected inconsistencies in data types.
- **Pivot Tables:** Summarized data from different perspectives.
- **Visualizations:** Used charts and maps for KPI representation.
- **Key Features:** Application of formulas like VLOOKUP, COUNTIF, ARRAYFORMULA.

### Key Performance Indicators (KPIs) 📊
KPIs are essential in evaluating the success of a project. In this section, I identify the KPIs that were used to measure performance and guide the analysis, aligning them with the objectives of the business or dataset.

The project focused on analysing the following critical aspects of ski resorts:
1. **Resort Popularity 🏔️**
    - Measure: Number of Skiers per Resort.
2. **Pricing Analysis 💸**
    - Measure: Average Day Pass per Resort.
3. **Amenity Analysis 🎢**
    - Measure: Diversity of Lift Types.
4. **Resort Location Analysis 🌍**
    - Measure: Number of Resorts per Region.
5. **Customer Satisfaction 😊**
    - Measure: Family-Friendly and Expert-Friendly Ratings.
6. **Accommodation Analysis 🏨**
    - Measure: Total Accommodations and Distance to Nearest Accommodation.

Each KPI provided insights into different facets of the ski industry, enhancing our understanding of resort performance and customer preferences.

### Challenges in the Dataset ⚠️
No data analysis project is without its hurdles. Here, I highlight the challenges I faced while working with the dataset, such as missing values, outliers, or inconsistencies, and how I approached solving these issues.
- **Data Formatting Issues 🛠️**
   - Numeric values were stored as text strings (e.g., "5 Gondolas"), leading to calculation errors.
- **Missing Data 🔍**
   - Key columns (e.g., pricing, amenities) had blank entries, impacting analysis accuracy.
- **Correlation Challenges 📈**
   - Difficulty in analysing relationships between variables, such as ratings vs. visitor numbers.


### Data Cleaning Process 🧹
Data cleaning is one of the most crucial steps in any analysis. In this section, I explain the methods and tools used to clean the dataset, including removing duplicates, handling missing values, and correcting data inconsistencies to ensure high-quality analysis.
- **Corrected Data Formatting 🧹**
   - Applied ARRAYFORMULA & REGEXEXTRACT to extract numeric values from text strings.
- **Addressed Missing Data 🧩**
   - Highlighted blanks using conditional formatting.
   - Filled gaps with averages or trends, where possible.
- **Created Calculated Fields 📊**
   - Added columns (e.g., Average Day Pass) to establish relationships between variables.



### Exploratory Data Analysis 🔎
In this section, I perform exploratory data analysis (EDA) to uncover patterns, trends, and relationships within the data. 
Various visualizations and statistical methods are used to gain insights from the raw dataset.


<!--#### Resort Popularity 🏔️
 - **KPI: Number of Skiers per Resort.**
 - **Steps Taken:**
          - Applied Conditional Formatting to highlight resorts with more than 1,250,000 visitors🎯.
          - Filtered data (in a separate view) for easier visibility and insights.
 - **Visualization:** Bar Chart 📊 showing the most visited resorts.  -->

   
![image](https://github.com/user-attachments/assets/3d94d353-9b48-484f-a3a5-6bb2f53fab4f)

![image](https://github.com/user-attachments/assets/5a18452b-0b35-49eb-bacd-e988f0188e48)


<!--#### Pricing Analysis 💸 
- **KPI: Average Day Pass per Resort**:  Identified the most expensive and least expensive resorts..
- **Steps Taken:**
        - Created a new calculation column: Average Day Pass using AVERAGE(W2:Y2)✍️.
       - Compared pricing across resorts to uncover trends.
- **Visualization:** Histogram showcasing price distribution.  -->
![image](https://github.com/user-attachments/assets/71ffe24a-18dc-4d8d-8066-36a0926c8255)


<!-- ![image](https://github.com/user-attachments/assets/54963929-c503-4404-8689-d5b67d577c2f)  -->

![image](https://github.com/user-attachments/assets/c462d4c0-824f-4f44-980d-12ec5b13ad06)


<!-- #### Amenity Analysis (Lift Types) 🎢
 - **KPI: Count of different lift types per resort.**
 - **Steps Taken:**
      - Formatted data (e.g., text to numbers) using ARRAYFORMULA & REGEXEXTRACT 🛠️.
      - Identified resorts with the most diverse lift options. 
- **Visualization:** Bar Chart 📊 showcasing lift distribution -->
![image](https://github.com/user-attachments/assets/2470fe11-ec44-4b13-9758-aa8fce22be32)
![image](https://github.com/user-attachments/assets/58bf28b5-c7a2-43bc-87da-1cc2e806c99d)



<!-- #### Resort Location Analysis🌍
 - **KPI: Number of Resorts per Region.**
 - **Steps Taken:** 
       - Created Pivot Table to summarize resort distribution by region.
       - Represented the data on a Geographical Map 🗺️ for clarity. 
- **Visualization:** Geographical Map showing regional spread. -->
![image](https://github.com/user-attachments/assets/4d5ab003-095c-4623-a14b-b2c4dfbc783b)
![image](https://github.com/user-attachments/assets/e3314f5f-73ef-444b-ad47-2fc04790099d)


<!-- #### Customer Satisfaction Analysis😊
 - **KPI:** Family-Friendly and Expert-Friendly Ratings.
 - **Steps Taken:** 
     - Compared ratings across resorts using Pivot Tables.
     - Identified resorts catering to specific skier types (e.g., families or experts. 
- **Visualization:** Radar Chart or Bar Chart 📌 for detailed comparisons. -->
![image](https://github.com/user-attachments/assets/4ffa0505-4fe5-46a2-85ee-33550ae602c2)
![image](https://github.com/user-attachments/assets/d06da61c-287e-4ca7-bd13-1149a156081e)



 #### Technical Skills Showcase 💻
This project showcases my proficiency in a range of technical tools and languages:.

    - Excel & Google Sheets (XLOOKUP, Pivot Tables, Charts).
    - Formulas Used: VLOOKUP, COUNTIF, ARRAYFORMULA, etc.
    - Visualization Techniques: Bar Charts, Pie Charts, Scatter Plots, Radar Charts.
    - Other Features: Conditional Formatting and Pivot Tables.
<!-- ![image](https://github.com/user-attachments/assets/b81904eb-a105-4812-970b-9d2d79df0c92) -->
 



### Insights and Observations 💡
This section covers the key insights drawn from the data analysis, such as trends, correlations, and outliers, along with any surprising findings that were uncovered during the analysis process.

  <!-- 1. Most popular resort **(Saas-Fee)** has 1,800,000 visitors.. 
  2. Average Day Pass cost ranges from **$20 (Troodos) to $115 (Saas-Fee)**.
  3. Lift diversity is highest at Resort **Saalbach-Hinterglemm.** 
  4. Maximum resorts (9) are in region **Savoie & Tyrol.**
  5. **Borovets, Zakopane, Mürren, Avoriaz, and Saas-Fee** offer accommodations within the resort premises, providing enhanced convenience for visitors.
  6. **Bláfjöll** has an exceptionally high accommodation capacity of 25,000, but all accommodations are located 25 km away, making it a unique outlier. 
  7. **Saas-Fee** successfully balances premium pricing with convenience and quality, positioning itself as a top-tier destination for affluent and quality-focused visitors.  -->
![image](https://github.com/user-attachments/assets/5ad6e1d2-d86e-4f43-8485-7d246e55a55f)


### Recommendations 📈
Based on the insights derived from the dataset, I provided actionable recommendations for improving business performance, addressing issues, or optimizing processes. These recommendations are tailored to align with the business goals and KPIs.
   <!--  1. Resorts with on-site accommodations, such as Saas-Fee, show higher convenience for visitors..
    2. Consider increasing on-site accommodation capacity at resorts like Borovets and Avoriaz to attract more guests.
    3. Offer tiered pricing or discounts to balance affordability with premium services.
    4. Leverage high Family-Friendly Ratings to market specific resorts to families.
    5. For resorts with off-site accommodations, such as Bláfjöll, enhance transportation links to improve convenience.
    6. Consider shuttle services or partnerships with local accommodations to reduce visitor inconvenience. -->
  ![image](https://github.com/user-attachments/assets/cd975641-3ff9-454d-aceb-d4dcc59d02b5)



### Conclusion ✅
In conclusion, this project highlights my ability to handle real-world datasets, clean and process data, and derive valuable insights. The skills demonstrated in this project are a testament to my proficiency as a data analyst, ready to tackle new challenges in the data field.

    - Tools & Technologies Used 💻
    - Excel & Google Sheets

**Feel free to explore the code and visualizations in this repository to see how I applied these tools in this project.**

**Thank you for checking out my project! If you have any questions or feedback, feel free to reach out. 🙌**

