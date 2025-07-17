## 📦 Dataset Description

This dataset includes 12 months of trip data from Chicago’s Divvy bike-sharing system, provided by Motivate LLC. It reflects real user activity and ride patterns over time.


## 📥 Data Access

The Cyclistic (Divvy) bike ride data used in this project is publicly available and can be accessed directly via:

🔗 [Divvy Trip Data Download Portal](https://divvy-tripdata.s3.amazonaws.com/index.html)

This link provides a full archive of monthly CSV files from Divvy's bike-share system, hosted by **Motivate International Inc.** through Amazon S3.

### 📂 Instructions:
1. Click the link above to open the file index.
2. Download each CSV file corresponding to the months you're analyzing.
   - For this project, we used data from **November 2020 to October 2021**
   - Example file: `202011-divvy-tripdata.csv`
3. Save all files to a local folder (e.g., `data/`) for importing into your analysis environment.


## 📝 Files Included for this project
Each file represents one month of data:
- `202011-divvy-tripdata.csv`
- `202012-divvy-tripdata.csv`
- ...
- `202110-divvy-tripdata.csv`

📁 ~1 GB total  
📊 ~4.5 million rides

## 📋 Data Fields
| Column Name        | Description                                |
|--------------------|--------------------------------------------|
| ride_id            | Unique ID of each trip                     |
| started_at         | Start timestamp                            |
| ended_at           | End timestamp                              |
| rideable_type      | Bike type: classic, docked, electric       |
| start_station_name | Name of starting station                   |
| end_station_name   | Name of ending station                     |
| member_casual      | Rider type: "member" or "casual"           |

---

## ⚠️ Notes
- Some trips have negative or missing durations → cleaned in notebook
- Geolocation fields are removed for this analysis
- Data provided for **educational use** only under a [data license](https://www.divvybikes.com/system-data) which permits use for analysis, provided attribution is maintained.

---

## 🔧 How to Use
- Download and extract the 12 CSV files
- Place them in the appropriate folder (e.g. `/input/divvy-tripdata-nov2020-oct2021/`)
- Reference them in your notebook using `read_csv()`

---
