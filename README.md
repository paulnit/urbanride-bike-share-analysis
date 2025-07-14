# urbanride-bike-share-analysis
My first data analysis project on bike share data
## 🧰 Tools Used

- **SQL (BigQuery)** – For data cleaning and transformation
- **R** – For exploring and visualizing trends
- **Tableau Public** – For an interactive dashboard
- **GitHub** – For version control and project documentation
---
## 🧹 SQL Data Cleaning

The raw trip data was cleaned using SQL:
- Removed null values and ride_id duplicates
- Removed trips <1 minute or >24 hours
- Extracted:  
  - `trip_duration_mins`  
  - `day_of_week`, `month`, `hour_of_day`

🧾 Final dataset: `updatedlast.csv`
---




## 📈 R Visualizations

R was used to generate quick EDA (exploratory data analysis) visuals:

### 1. 📊 Average Ride Duration by Rider Type
- Compares casual vs member ride times
- 📄 [CSV Output](r-outputs/average_ride_duration.csv)

### 2. 📅 Monthly Ride Trends
- Reveals seasonal ridership patterns
- 📄 [CSV Output](r-outputs/monthly_ride_trends.csv)

### 3. 📆 Ride Distribution by Day of Week
- Which days see the most rides
- 📄 [CSV Output](r-outputs/ride_distribution_by_day.csv)

### 4. 🚴 Total Rides by User Type
- Breakdown of total rides taken by casual vs members
- 📄 [CSV Output](r-outputs/total_rides_by_user_type.csv)







## 📊 Tableau Dashboard

Explore the interactive version here:
🔗 [UrbanRide Dashboard on Tableau Public](https://public.tableau.com/authoring/urbanrideshareanalysis/urbanridesharemay2024-25sheet12#1)




![Dashboard Preview](screenshots/dashboard-preview.png)

### Dashboard Includes:
- Rides by day of week
- Ride duration by user type
- Monthly trends
- Bike preference by rider




## 🧠 Key Insights

- **Casual riders** take longer rides on average than **members**
- **Weekends** are busier for casuals; **members** ride more during weekdays
- Ridership peaks in **summer** (July), dips in **winter** (January)
- **Classic bikes** are the most used, especially by members

---

## 🧑‍💻 Author

**[Nitin Paul/Paulnit]**  
📫 [LinkedIn or Portfolio URL]  
🔍 Seeking opportunities as a Junior Data Analyst

---

## 🧾 Credits

Inspired by the Google Data Analytics Capstone structure.  
Bike-share data is fictional and used for educational purposes only.
