# ♪ TikTok_Engagement_Analyzer

I'm Saghar Yeganehparast, currently a sophomore Computer Science and Engineering student with a minor in Business Analytics at Sabancı University.

This is my term project for DSA 210 (Introduction to Data Science).

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Objectives](#objectives)  
3. [Motivation](#motivation)  
4. [Data Collection & Sources](#data-collection--sources)  
   - [The Primary Data Source](#the-primary-data-source)  
   - [External Influencing Factors](#external-influencing-factors)  
   - [Personal Influencing Factors](#personal-influencing-factors)  
5. [Research Questions](#research-questions)  
6. [Possible Tools & Libraries To Be Used](#possible-tools--libraries-to-be-used)  
7. [Example Data Table](#example-data-table)


---

## Project Overview
Understanding digital consumption patterns has become increasingly important in recent years, where social media plays a significant role in most people's daily lives. This project aims to analyze my personal TikTok usage over the past six months, identifying correlations between usage patterns and various external and personal factors. The ultimate goal is to develop a predictive model that estimates future TikTok consumption based on these influencing variables.

---

## Motivation
Since TikTok is the social media app I use the most, analyzing my consumption patterns can provide valuable insights into behavioral trends. It will also allow me to make more informed decisions/predictions about my screen time and digital well-being.

---

## Objectives  
- **Analyze** TikTok usage patterns over a few months.  
- **Identify factors** influencing engagement (like global events, weather, and academic schedules).  
- **Build a predictive model** for future TikTok consumption.  
- **Apply data science skills** in a real world context.  

---

## Research Questions
1. What factors influence the TikTok usage on a daily basis?
2. Does **sleep** duration have a direct effect on daily TikTok usage? 
3. How does the **temperature and weather** conditions affect TikTok consumption?
4. How does **academic workload** (exams, class schedules) influence TikTok consumption?
5. What is the relationship between overall **screen time** (across all apps) and TikTok usage?  
6. What role do **global events** (e.g., award shows, elections, cultural events) play in influencing TikTok consumption?  
7. Can I make a predictive model to estimate my future TikTok consumption based on these factors?  
9. Perhaps, can I use these findings to optimize my social media(Tiktok) consumption?  

---

## Data Collection & Sources
The analysis will be conducted using both personal data collected directly from TikTok and additional data from external sources that may influence my media consumption:

### The Primary Data Source:
  - Frequency of app usage per day. *(Collected through TikTok app)*
  - Total hours spent on TikTok daily. *(Collected through TikTok app)*

### External Influencing Factors:
   - **Major Global Events**
     - Medical
     - Religious
     - Political
     - Social/Cultural
     - Music-related
     - Sports-related
     - Fashion-related
     - Competitions/Award shows
     - Etc. *(All collected through manual research or calendars)*

   - **Weather Conditions**
     - Temperature *(Collected through Weather app)*
     - Precipitation *(Collected through Weather app)*

### Personal Influencing Factors:
   - **Total Daily Screen Time**
     - *Collected through the Samsung Health application*

   - **Sleep Duration from the Previous Night**
     - *Collected through the Samsung Health application*

   - **Academic Responsibilities**
     - Exam schedules *(Collected through Sabancı University Website)*
     - Course schedules *(Collected through Sabancı University Website)*

---

## Possible Tools & Libraries To Be Used

**1. Programming Language:**
- **Python**: For data analysis and model building.

**2. Data Analysis & Machine Learning:**
- **Pandas**: For data manipulation/analysis.

**4. Data Visualization:**
- **Matplotlib**: For creating data visualizations.

**5. Data Collection:**
- **TikTok**: To collect personal usage data.
- **Weather App**: To get weather data for analysis.
- **Samsung Health App**: To get screen time and sleep data for analysis.
- **Sabancı University Website**: To get course/exam schedules for analysis.

---

## Example Data Table
(**Note:** This is just an **example** data table, the project will include many more columns)

TikTok Usage and Influencing Factors (In countdowns, if the event passed the numbers will turn negative. If 0, then we are on the D-day)

| Date       | TikTok Usage (Hours) | Total Screen Time (Hours) | Sleep Duration (Hours) | Temperature (°C) | Precipitation (mm) | Have Exam? | Hours of Class | Grammy Awards? | Oscar Awards? | Paris Fashion Week (Day) | Ramazan 2025 Countdown | Nowruz 1404 Countdown | New Year 2025 (Passed) Countdown | US Elections Period? | Turkey Elections Period? | Iran Elections Period? | UEFA Champions League Final? |
|------------|----------------------|---------------------------|------------------------|------------------|--------------------|------------|----------------|----------------|----------------|-------------------------|------------------------|-----------------------|---------------------------------|-----------------------|---------------------------|------------------------|-------------------------------|
| 2025-03-01 | 3.5                  | 6.0                       | 7.0                    | 15               | 5                  | 1          | 4              | 1              | 0              | 3                       | 0                      | 19                    | -59                             | 0                     | 1                         | 0                      | 0                             |
| 2025-03-22 | 2.0                  | 4.5                       | 8.0                    | 18               | 0                  | 0          | 6              | 0              | 1              | 5                       | -21                    | -2                    | -80                             | 0                     | 0                         | 1                      | 0                             |
| 2025-03-25 | 4.0                  | 7.0                       | 6.0                    | 17               | 3                  | 0          | 3              | 0              | 0              | 0                       | -24                    | -5                    | -83                             | 1                     | 0                         | 0                      | 1                             |
| 2025-05-25 | 4.0                  | 7.0                       | 6.0                    | 25               | 0                  | 0          | 3              | 0              | 0              | 0                       | -85                    | -66                   | -144                            | 0                     | 0                         | 0                      | 1                             |
