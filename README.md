# TikTok_Engagement_Analyzer

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
5. [Example Data Table](#example-data-table)

---

## Project Overview
Understanding digital consumption patterns has become increasingly important in recent years, where social media plays a significant role in most people's daily lives. This project aims to analyze my personal TikTok usage over the past six months, identifying correlations between usage patterns and various external and personal factors. The ultimate goal is to develop a predictive model that estimates future TikTok consumption based on these influencing variables.

---

## Objectives  
- **Analyze** TikTok usage patterns over a few months.  
- **Identify factors** influencing engagement (like global events, weather, and academic schedules).  
- **Build a predictive model** for future TikTok consumption.  
- **Apply data science skills** in a real world context.  

---

## Motivation
Since TikTok is the social media app I use the most, analyzing my consumption patterns can provide valuable insights into behavioral trends. It will also allow me to make more informed decisions/predictions about my screen time and digital well-being.

---

## Data Collection & Sources
The analysis will be conducted using both personal data collected directly from TikTok and additional data from external sources that may influence my media consumption:

### The Primary Data Source:
  - Frequency of app usage per day.
  - Total hours spent on TikTok daily.

### External Influencing Factors:
  **1. Major Global Events**
   - Medical
   - Religious
   - Political
   - Social/Cultural
   - Music-related
   - Sports-related
   - Fashion-related
   - Competitions/Award shows
   - Etc.

  **2. Weather Conditions**
   - Temperature
   - Precipitation

### Personal Influencing Factors:
  **1. Total daily screen time**
   - Collected through the mobile phone's utility application

  **2. Sleep duration from the previous night**
   - Collected through the Samsung Health application

  **3. Academic responsibilities**
   - Exam schedules
   - Course schedules

---

## Example Data Table: 
TikTok Usage and Influencing Factors (In countdowns, if the event passed the numbers will turn negative. If 0, then we are on the D-day)

| Date       | TikTok Usage (Hours) | Total Screen Time (Hours) | Sleep Duration (Hours) | Temperature (°C) | Precipitation (mm) | Have Exam? | Hours of Class | Grammy Awards? | Oscar Awards? | Paris Fashion Week (Day) | Ramazan 2025 Countdown | Nowruz 1404 Countdown | New Year 2025 (Passed) Countdown | US Elections Period? | Turkey Elections Period? | Iran Elections Period? | UEFA Champions League Final? |
|------------|----------------------|---------------------------|------------------------|------------------|--------------------|------------|----------------|----------------|----------------|-------------------------|------------------------|-----------------------|---------------------------------|-----------------------|---------------------------|------------------------|-------------------------------|
| 2025-03-01 | 3.5                  | 6.0                       | 7.0                    | 15               | 5                  | 1          | 4              | 1              | 0              | 3                       | 0                      | 19                    | -59                             | 0                     | 1                         | 0                      | 0                             |
| 2025-03-22 | 2.0                  | 4.5                       | 8.0                    | 18               | 0                  | 0          | 6              | 0              | 1              | 5                       | -21                    | -2                    | -80                             | 0                     | 0                         | 1                      | 0                             |
| 2025-03-25 | 4.0                  | 7.0                       | 6.0                    | 17               | 3                  | 0          | 3              | 0              | 0              | 0                       | -24                    | -5                    | -83                             | 1                     | 0                         | 0                      | 1                             |
| 2025-05-25 | 4.0                  | 7.0                       | 6.0                    | 25               | 0                  | 0          | 3              | 0              | 0              | 0                       | -85                    | -66                   | -144                            | 0                     | 0                         | 0                      | 1                             |
