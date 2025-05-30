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
6. [Tools & Libraries Used](#tools--libraries-used)
7. [Hypotheses and Results](#hypotheses-and-results)
8. [Machine Learning Models & Prediction](#machine-learning-models--prediction)
9. [Key Findings](#key-findings)
10. [Future Work](#future-work)
11. [Example Data Table](#example-data-table)

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
2. How does the **temperature and weather** conditions affect TikTok consumption?
3. How does **academic workload** (exams, class schedules) influence TikTok consumption?
4. What role do **global events** (e.g., award shows, elections, cultural events) play in influencing TikTok consumption?  
5. Can I make a predictive model to estimate my future TikTok consumption based on these factors?  
6. Perhaps, can I use these findings to optimize my social media(Tiktok) consumption?  

---

## Data Collection & Sources
The analysis was conducted using both personal data collected directly from TikTok and additional data from external sources that may influence my media consumption:

### The Primary Data Source:
  - Total hours spent on TikTok daily. *(Calculated from the TikTok app data)*
  - Total number of videos watched on TikTok daily. *(Collected through TikTok app)*

### External Influencing Factors:
   - **Major Global Events**
     - Religious
     - Political
     - Social/Cultural
     - Music-related
     - Sports-related
     - Fashion-related
     - Competitions/Award shows
     - Etc. *(All collected through manual research or calendars)*

   - **Weather Conditions**
     - Temperature *(Collected through Weather API)*
     - Precipitation *(Collected through Weather API)*
     - Snow *(Collected through Weather API)*
     - Snow Depth *(Collected through Weather API)*
     - UV Index *(Collected through Weather API)*

### Personal Influencing Factors:
   - **Academic Responsibilities**
     - Academic Calendar *(Collected through Sabancı University Website)*
   - **Weekend/Weekday**
     - Weekend/Weekday because of free time *(Collected through calendar)*     

---

## Tools & Libraries Used

**1. Programming Language:**
- **Python**: For data analysis and model building.

**2. Data Analysis & Machine Learning:**
- **Pandas**: For data manipulation/analysis.
- **NumPy**: For numerical computing.
- **Scikit-learn**: For machine learning models and evaluation.

**3. Data Visualization:**
- **Matplotlib**: For creating data visualizations.
- **Seaborn**: For advanced data visualization and statistical graphics.

**4. Data Collection:**
- **TikTok**: To collect personal usage data.
- **Weather API**: To get weather data for analysis. ([Link](https://www.google.com/url?q=https%3A%2F%2Fwww.visualcrossing.com%2Fweather-query-builder%2F))
- **Sabancı University Website**: To get course/exam schedules for analysis.

---

## Hypotheses and Results

### 📅 Day
- **H1:** TikTok usage may follow a time trend over the semester (increasing or decreasing gradually).  
  **Result:** It did in fact show a lot of fluctuations.

### ⏱️ TikTok Usage (Hours)
- **H2:** TikTok usage is influenced by personal habits, external events, and environmental factors.  
  **Result:** Even if not always strong correlations, it seems there are effects of the factors.

### 🌡️ Temperature Feels Like
- **H3:** Lower temperatures lead to higher TikTok usage, as I prefer staying indoors.  
  **Result:** It is observed that I spend more time when the temperature is between 10–15°C.

### 🌧️❄️☁️ Precipitation, Snow, Snow Depth, UV Index
- **H4:** Rainy/snowy days are associated with increased TikTok usage.  
  **Result:** No strong correlation found.

### 🎵 2025 Grammy Awards (Countdown)
- **H5:** TikTok usage increases near major music events due to trending content and artists.  
  **Result:** It is observed that I spend more time when the event is closer.

### 🎬 2025 Oscar Awards (Countdown)
- **H6:** Usage increases around the Oscars.  
  **Result:** It is observed that I spend more time when the event is closer.

### 👗 2025 Paris Fashion Week (Bool)
- **H7:** TikTok usage may increase during Fashion Week.  
  **Result:** It is observed that I spend more time when the event is closer.

### 🕌 2025 Ramazan (Bool)
- **H8:** TikTok usage may increase during Ramazan.  
  **Result:** No strong correlation found.

### 🎉 1404 Nowruz (Countdown)
- **H9:** Leading up to Nowruz, TikTok usage may increase due to cultural or celebratory content.  
  **Result:** It is observed that I spend more time when the event is closer.

### 🎊 2025 New Year (Countdown)
- **H10:** TikTok usage may increase around New Year's Day.  
  **Result:** It is observed that I spend more time when the event is closer.

### 🗳️ 2024 United States Presidential Election (Countdown)
- **H11:** Usage may increase during this period.  
  **Result:** No strong correlation found.

### ⚽ 24/25 UEFA Champions League (Bool)
- **H12:** Matches or finals may influence TikTok usage.  
  **Result:** It is observed that I spend more time on the match days.

### 🎓 24/25 School Year (Bool)
- **H13:** TikTok usage is lower during the active school year compared to breaks or holidays.  
  **Result:** Need more data.

### 📆 Weekday (Bool)
- **H14:** Weekdays are associated with less TikTok usage due to academic schedule and deadlines.  
  **Result:** It is observed that I spend less time on the weekdays.

### 🛌 Weekend (Bool)
- **H15:** Weekends are associated with higher TikTok usage due to more free time.  
  **Result:** It is observed that I spend more time on the weekends.

---

## Machine Learning Models & Prediction

### Dataset Overview
The analysis was conducted on **245 days** of data with **21 features**, including weather conditions, global events, and personal factors.

### Models Tested
Four different machine learning models were implemented and evaluated:

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **K-Nearest Neighbors Regressor**

### Baseline Models
Simple baseline predictors were established for comparison:
- **Mean Predictor**: MAE = 98.79 videos
- **Median Predictor**: MAE = 93.46 videos (best baseline)

### Cross-Validation Results
Using time-series cross-validation with 5 splits:

| Model | Mean Absolute Error (MAE) |
|-------|---------------------------|
| K-Nearest Neighbors | 108.22 ± 17.82 |
| Random Forest | 114.21 ± 22.93 |
| Linear Regression | 134.05 ± 33.11 |
| Decision Tree | 151.38 ± 37.99 |

### Test Set Performance
Unfortunately, all machine learning models performed worse than the baseline on the test set:

| Model | MAE | RMSE | R² Score |
|-------|-----|------|----------|
| K-Nearest Neighbors | 179.01 | 202.03 | -3.525 |
| Random Forest | 179.23 | 204.20 | -3.623 |
| Linear Regression | 231.40 | 253.89 | -6.147 |
| Decision Tree | 294.37 | 323.20 | -10.581 |

**Note:** All models showed negative R² scores, indicating they performed worse than simply predicting the mean.

---

## Key Findings

### Statistical vs. Practical Significance
While most statistical tests did not return significant p-values, several visual patterns were observed:
- **UEFA matches** showed noticeable impact on usage
- **Fashion Week** periods correlated with increased consumption  
- **Weekend vs. weekday** patterns were clearly evident
- **Major events** (Grammy Awards, Oscars, Nowruz, New Year) showed trending effects

These patterns suggest real-world effects that may become statistically significant with more data or additional features.

### Model Performance Insights
The machine learning models struggled to predict TikTok usage accurately, with the **Median Predictor baseline** (MAE = 93.46) outperforming all sophisticated models. This suggests that:
- Current features may not capture the complexity of social media consumption patterns
- More data or different feature engineering approaches may be needed
- Personal usage patterns might be more random than initially hypothesized

---

## Future Work

To improve the predictive model performance, future work will focus on:

- **Data Collection**: Gathering more days of usage data for better model training
- **Feature Engineering**: 
  - Adding more granular time-based features (hour of day, day of week interactions)
  - Including content-based features (trending topics, personal interests)
  - Perhaps incorporating mood or emotional state indicators

---

## Example Data Table

TikTok Usage and Influencing Factors (Countdowns or Boolean)

| Day         | Videos Watched | TikTok Usage (Hours) | FeelsLike (°C) | Precip (mm) | Snow (cm) | Snow Depth (cm) | Cloud Cover (%) | UV Index | General             | 2025 Grammy Awards (Countdown) | 2025 Oscar Awards (Countdown) | 2025 Paris Fashion Week (Bool) | 2025 Ramazan (Bool) | 1404 Nowruz (Countdown) | 2025 New Year (Countdown) | 2024 United States Presidential Election (Countdown) | 24/25 UEFA Champions League (Bool) | 24/25 School Year (Bool) | Weekday (Bool) | Weekend (Bool) |
|-------------|----------------|-----------------------|----------------|-------------|-----------|-----------------|-----------------|----------|----------------------|-------------------------------|-------------------------------|------------------------------|---------------------|------------------------|------------------------|----------------------------------------------------|----------------------------------|------------------------|----------------|----------------|
| 2024-09-11  | 278            | 1.158                 | 25.7           | 8.0         | 0.0       | 0.0             | 53.0            | 6        | Rain                | 145.0                         | 173.0                         | 0.0                          | 0.0                 | 191.0                  | 112.0                  | 55.0                                              | 0.0                              | 0.0                    | 1.0            | 0.0            |
| 2024-09-12  | 61             | 0.254                 | 25.5           | 16.0        | 0.0       | 0.0             | 40.3            | 7        | Rain                | 144.0                         | 172.0                         | 0.0                          | 0.0                 | 190.0                  | 111.0                  | 54.0                                              | 0.0                              | 0.0                    | 1.0            | 0.0            |
| 2024-09-13  | 321            | 1.338                 | 26.1           | 0.0         | 0.0       | 0.0             | 17.1            | 7        | Clear Day           | 143.0                         | 171.0                         | 0.0                          | 0.0                 | 189.0                  | 110.0                  | 53.0                                              | 0.0                              | 0.0                    | 1.0            | 0.0            |
| 2024-09-14  | 101            | 0.421                 | 27.0           | 0.0         | 0.0       | 0.0             | 43.3            | 7        | Partly Cloudy Day    | 142.0                         | 170.0                         | 0.0                          | 0.0                 | 188.0                  | 109.0                  | 52.0                                              | 0.0                              | 0.0                    | 0.0            | 1.0            |

---

*This project demonstrates the application of data science techniques to personal digital behavior analysis, providing insights into social media consumption patterns and the challenges of predicting complex human behaviors.*
