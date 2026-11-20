# 🏨 Hotel Booking Analysis

## 📌 Project Overview

This project focuses on analyzing hotel booking data to identify booking patterns, understand customer behavior, and investigate the factors influencing reservation cancellations.

Using Python, I performed data cleaning, exploratory data analysis (EDA), and data visualization to extract meaningful insights and provide business recommendations that could help hotels reduce cancellation rates and improve revenue.

## 🎯 Project Objectives

The main objectives of this analysis are:

- Understand hotel booking and cancellation patterns.
- Compare booking behavior between City Hotels and Resort Hotels.
- Identify the months with the highest and lowest cancellation rates.
- Investigate the relationship between accommodation prices (ADR) and cancellations.
- Identify the countries with the highest number of cancelled reservations.
- Analyze the distribution of bookings across different market segments.
- Provide recommendations to improve hotel performance and customer retention.

## 🛠️ Tools & Technologies

- **Python** – Data analysis and manipulation.
- **Pandas** – Data cleaning and analysis.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Jupyter Notebook** – Development environment.

## 📂 Dataset

The dataset contains hotel booking information, including:

- Hotel type (City Hotel / Resort Hotel)
- Reservation status
- Lead time
- Arrival date
- Number of guests
- Country of origin
- Market segment
- Distribution channel
- Average Daily Rate (ADR)
- Customer type
- Previous cancellations
- Special requests

The original dataset contains 119,390 records and 36 columns.

## 🔍 Project Workflow

### 1. Data Cleaning & Preparation

- Imported the dataset using Pandas.
- Removed personal information columns, including names, emails, phone numbers, and credit card details.
- Converted reservation status dates into datetime format.
- Identified and handled missing values.
- Removed columns with a significant number of missing values, such as agent and company.
- Identified and filtered an ADR outlier.

### 2. Exploratory Data Analysis (EDA)

Performed analysis to explore:

- Overall reservation and cancellation rates.
- Differences between City Hotels and Resort Hotels.
- Average Daily Rate (ADR) and its relationship with cancellations.
- Monthly reservation and cancellation patterns.
- Countries with the highest number of cancelled bookings.
- Booking distribution across market segments.

### 3. Data Visualization

Created visualizations using Matplotlib and Seaborn, including:

- Reservation status comparison.
- Cancellation distribution by hotel type.
- Average Daily Rate trends.
- Monthly booking and cancellation patterns.
- Cancellation distribution by country.
- Booking distribution by market segment.

## 📊 Key Findings

**1. Overall Cancellation Rate**

Approximately 37% of reservations were cancelled, highlighting the importance of understanding the factors behind booking cancellations.

**2. City Hotels vs. Resort Hotels**

City Hotels recorded more bookings and cancellations than Resort Hotels.

The cancellation rate was approximately:
- City Hotels: 41.7%
- Resort Hotels: 28.0%

**3. Monthly Booking Patterns**

- January recorded the highest number of cancellations.
- August had the lowest number of cancellations and the highest number of reservations.
- December recorded fewer reservations compared with other months.

**4. Pricing and Cancellations**

The analysis suggests a positive relationship between accommodation prices (ADR) and cancellations. Higher accommodation prices may contribute to customers cancelling their reservations.

**5. Countries with the Highest Cancellations**

Portugal recorded the highest number of cancelled reservations, followed by the United Kingdom, Spain, and France.

**6. Market Segment Analysis**

Online Travel Agents (Online TA) represented approximately 47% of all reservations, followed by Offline Travel Agents and Tour Operators (Offline TA/TO) at approximately 20%.

Online Travel Agents also accounted for approximately 47% of cancelled reservations.

## 💡 Business Recommendations

Based on the findings, the following recommendations could help hotels improve their booking performance:

- **Improve pricing strategies:** Offer competitive and flexible pricing, particularly during periods associated with higher cancellation rates.
- **Seasonal promotions:** Introduce discounts and targeted marketing campaigns during January to attract more visitors.
- **Resort pricing:** Consider more attractive room prices during weekends and holidays.
- **Improve hotel facilities:** Focus on improving facilities and services, particularly in Portugal, where the highest number of cancellations was observed.
- **Optimize online marketing:** Review online booking platforms, hotel descriptions, and photographs to ensure that customer expectations match the actual experience.
- **Personalized marketing:** Develop targeted campaigns based on customer location, booking behavior, and seasonal demand.

## 📌 Conclusion

This project provided valuable insights into hotel booking behavior and reservation cancellations.

The analysis highlighted that hotel type, pricing, seasonality, country of origin, and market segment are important factors to consider when evaluating booking performance.

By using data-driven insights, hotels can develop better pricing strategies, improve their marketing activities, enhance customer satisfaction, and ultimately reduce cancellations.

---

*This project was completed as part of my Data Analytics portfolio to demonstrate my skills in Python, data cleaning, exploratory data analysis, and data visualization.*
