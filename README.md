# 🚕 Uber Data Analytics Project

This repository contains a Power BI project developed to analyze Uber ride data. The project visualizes important KPIs such as total trips, total fare, average trip duration, distance covered, and the percentage of night trips. The goal is to extract actionable insights from raw ride data using interactive dashboards and data visualization techniques.

---

## 🎯 Project Objectives

- To design an interactive and insightful Power BI dashboard for Uber ride data.
- To analyze and summarize key metrics such as trip counts, fare amounts, and ride durations.
- To identify ride patterns over time (daily, monthly, yearly).
- To highlight peak trip times and the percentage of night trips.
- To develop data analytics and dashboard development skills.

---

## 📦 Project Structure


---

## 📊 Tools and Technologies Used

- **Power BI** – For data transformation, modeling, and dashboard creation.
- **Microsoft Excel** – For initial data preparation and exploration.
- **DAX** – Used within Power BI for custom measures and calculated columns.
- **Data Sources** – Uber ride dataset with fields like Trip ID, Start Time, End Time, Fare, Distance, etc.

---

## 🧠 Methods & Architecture

### Data Model

- **Fact Table:** Contains transactional data like trip details (Trip ID, Time, Fare, Distance, Duration).
- **Dimension Tables:** Time (Date, Month, Year), Location (Pickup and Drop-off).
- **Relationships:** Established between time and fact tables using Power BI’s data modeling features.

### Measures Created

- Total Trips
- Total Fare
- Average Trip Duration
- Total Distance
- Night Trips % (trips between 9 PM – 6 AM)

---

## 🖼️ Dashboard Screenshots

The dashboard is divided into multiple views:

1. **KPI Summary** – Showcasing total trips, fare, and average duration.
2. **Trends View** – Visualizing trips by month, day, and time.
3. **Night Trip Analysis** – Pie chart/line graph showing night trip trends.
4. **Filters and Slicers** – Year, Month, and Time of Day for drill-down analysis.

You can find all visual examples in the `/Screenshots/` folder.

---

## 📌 Expected Outcomes & Deliverables

- An interactive Power BI dashboard (.pbix file).
- A well-documented GitHub repository including visuals.
- Project screenshots and architecture overview.
- Clear and summarized insights based on Uber ride data.

---

## 📘 Learnings & Reflection

- Learned to structure data using fact and dimension tables.
- Gained practical experience in building KPIs and visual storytelling.
- Developed proficiency in Power BI including use of slicers, filters, and DAX measures.
- Understood real-world data analytics project flow from start to dashboard deployment.

---

## 🚀 Future Scope

- Integrate real-time ride data using APIs.
- Add geospatial visualizations using Power BI Map visuals.
- Include driver ratings, wait times, and cancellation analysis.
- Deploy the dashboard as a web-embedded report (Power BI Service).

---

## 🔗 GitHub Repository

You are currently viewing this on GitHub:  
**[Uber Data Analytics Repository](https://github.com/RajeebLochan/Uber_Data_Analytics)**

Feel free to explore, fork, and contribute!

---

## 🙌 Acknowledgments

This project was created as part of a data analytics internship. Special thanks to the mentors and the platform for guiding me through the learning process.

---

📩 For any suggestions or collaborations, feel free to reach out via GitHub or email.
