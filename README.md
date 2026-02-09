# COVID-19 Global Insights Dashboard (2020–2024)

## 📌 Project Overview
This project presents an **interactive Power BI dashboard** analyzing **global COVID-19 trends from 2020 to 2024**.  
The goal of the project is to explore how the pandemic evolved over time and how it affected countries and regions differently in terms of **cases, deaths, vaccinations, demographics, and economic indicators**.

The dashboard transforms a large real-world dataset into **clear, data-driven insights** that support public health analysis and policy evaluation.

---

## 🌍 Data Source
- **Dataset:** Our World in Data – COVID-19 Deaths  
- **Link:** https://ourworldindata.org/covid-deaths  
- **Note:** Due to the large size of the dataset, it was accessed directly via the source link.

---

## 🎯 Research Questions
The dashboard was designed to answer the following key questions:

1. What was the **total world population** during the period?
2. How many **total COVID-19 cases** were recorded globally?
3. How many **total deaths** occurred?
4. How many **total vaccinations** were administered?
5. What is the **average life expectancy** across countries?
6. What is the **median age** globally and per country?
7. What is the **GDP per capita** for each country?
8. How many **deaths were recorded by location**?
9. What were the **total cases per year**?
10. What were the **total vaccinations per year**?
11. How does the **Human Development Index (HDI)** vary by continent?
12. Which **income levels** were most affected by COVID-19 deaths?
13. How did **monthly deaths change**, and how do they vary by year?

---

## 🧹 Data Cleaning & Preparation
Data preparation was carried out in **Power Query**, including:

- Filtering records between **2020 and 2024**
- Handling missing and null values
- Standardizing country and continent names
- Converting date fields into proper date formats
- Aggregating global metrics (cases, deaths, vaccinations)
- Creating calculated fields for:
  - Total cases
  - Total deaths
  - Total vaccinations
- Grouping countries by:
  - Income level
  - Continent
- Preparing time-based fields:
  - Year
  - Month

---

## 📊 Dashboard Overview (Page 1)

![Screenshot 2024-10-16 131011](https://github.com/user-attachments/assets/88a5a173-3bb6-4a3a-9539-4037eb7e2057)

## 🔑 KPIs

- **World Population:** 8bn  
- **Total Cases:** 775M  
- **Total Deaths:** 7.05M  
- **Total Vaccinations:** 13.56bn  
- **Average Life Expectancy:** 73.71 years  
- **Median Age:** 30.50 years  

**Insight:**  
These KPIs provide a global snapshot of the pandemic’s scale and its demographic context.

---

## 🌐 Total Deaths by Location (Map)

- Visualizes deaths using a geographic bubble map  
- Larger bubbles represent higher death counts  

**Insight:**  
COVID-19 impact was unevenly distributed, with higher death concentrations in densely populated and highly connected regions.

---

## 📈 Total Cases by Year

- Shows yearly progression of total COVID-19 cases  
- Peak observed around **2022**

**Insight:**  
The pandemic intensified over time before declining as vaccination efforts increased.

---

## 📊 GDP per Capita by Location

- Displays economic variation across countries  

**Insight:**  
Economic capacity plays a role in healthcare response and mortality outcomes.

---

## 📊 Detailed Insights & Trends (Page 2)

![Screenshot 2024-10-16 131053](https://github.com/user-attachments/assets/674b80ea-56b1-4b6b-be59-b0abb3445347)

## 💉 Total Vaccinations by Year

- Majority of vaccinations occurred between **2021 and 2022**

**Insight:**  
Global vaccination campaigns accelerated rapidly after vaccine development.

---

## 📅 Monthly-Wise Deaths

- Monthly death trends with year-based filtering

**Insight:**  
Multiple waves are visible, reflecting variants, policy changes, and seasonal effects.

---

## 🌍 Human Development Index by Continent

- Europe has the highest average HDI  
- Africa records the lowest HDI  

**Insight:**  
Lower HDI regions tend to face higher vulnerability during global health crises.

---

## 💰 Deaths by Income Level

- High-income and upper-middle-income countries recorded the highest deaths

**Insight:**  
Higher deaths in wealthy regions reflect population size, testing capacity, and reporting accuracy rather than healthcare weakness alone.

---

## 🧠 Key Insights

- COVID-19 impact varied significantly by geography, income level, and development index  
- Vaccination efforts dramatically increased after 2021  
- Higher-income countries recorded more deaths numerically but often had better recovery capacity  
- Monthly trends reveal multiple pandemic waves  
- Demographic factors such as age and life expectancy influence mortality patterns  

---

## 🛠️ Tools & Technologies Used

- Microsoft Power BI  
- Power Query  
- DAX  
- Data Visualization  
- Public Health Data Analysis  

---

## 🚀 Conclusion

This project demonstrates a comprehensive Power BI analytics workflow, from handling large-scale public datasets to delivering interactive, insight-driven dashboards.  
It highlights how data visualization can be used to understand global crises and support informed decision-making during public health emergencies.


