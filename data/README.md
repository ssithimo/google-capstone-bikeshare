## 📦 Dataset Description
This dataset includes 12 months of trip data from Chicago’s Divvy bike-sharing system, provided by Motivate LLC. It reflects real user activity and ride patterns over time.

---

## 📝 Files Included
Each file represents one month of data:
- `202011-divvy-tripdata.csv`
- `202012-divvy-tripdata.csv`
- ...
- `202110-divvy-tripdata.csv`

📁 ~1 GB total  
📊 ~4.5 million rides

---

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
- Data provided for **educational use** only under a [data license](https://www.divvybikes.com/system-data)

---

## 🔧 How to Use
- Download and extract the 12 CSV files
- Place them in the appropriate folder (e.g. `/input/divvy-tripdata-nov2020-oct2021/`)
- Reference them in your notebook using `read_csv()`

---
