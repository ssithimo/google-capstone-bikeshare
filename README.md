# 🚲 Cyclistic Bike Sharing Data Analysis (Capstone Project)

## 📊 Project Overview
This capstone project analyzes 12 months of bike-sharing data from Motivate LLC's Divvy system in Chicago, as part of the Google Data Analytics Certificate. Our fictional company, **Cyclistic**, wants to **convert casual riders into annual members** by uncovering patterns in rider behavior.

## 🎯 Business Task
> "How can Cyclistic convert casual riders into annual members?"

We explore differences in usage patterns, trip durations, bike preferences, and station popularity between casual and member riders.

---

## 📁 Dataset
- Source: Motivate LLC via Divvy
- Period: **November 2020 – October 2021**
- Format: 12 monthly CSV files
- Size: ~1 GB total

📌 [Data license and usage terms here](https://www.divvybikes.com/system-data)

---

## 🛠 Tools Used
- **Language**: R
- **Libraries**: `tidyverse`, `lubridate`, `ggplot2`
- **Environment**: RStudio / Kaggle / Colab (R kernel)

---

## 🧼 Process Summary
1. **Import & Combine** 12 monthly datasets
2. **Clean & Tidy** the data (remove NAs, duplicates, and negative trip durations)
3. **Feature Engineering**: Add trip duration, day of week, month
4. **EDA & Visualizations**: Analyze ride frequency, trip time, bike type, and station usage

---

## 💡 Key Insights
- 🔁 Members take more rides overall; casuals dominate weekends
- ⏱ Casual riders have **2x longer** average trip durations
- 🚴‍♂️ Classic bikes are the most popular across both groups
- 📍 Top stations differ between rider types — suggesting different motivations and routes

---

## 🧠 Recommendations
- 🎯 **Target casual riders** in spring/summer with discounts
- 📍 Promote memberships at high-traffic stations and tourist areas
- 🤝 Partner with nearby attractions to offer bundled incentives

---

## ▶️ How to Run
1. Download all 12 CSV files
2. Open the R notebook in your preferred IDE or environment
3. Make sure `tidyverse` is installed:  
   ```R
   install.packages("tidyverse")
4. Update file paths if not using Kaggle
5. Run each section sequentially
