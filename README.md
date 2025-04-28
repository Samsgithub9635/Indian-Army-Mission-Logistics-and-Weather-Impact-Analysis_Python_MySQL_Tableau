# Operation Suraksha: Data-Driven Logistics Optimization for the Indian Army

## 🚀 Project Overview
**Operation Suraksha** is a data analytics project focused on improving the **logistics and supply chain efficiency** of the Indian Army, especially in **difficult terrains like Ladakh**.  
By analyzing transport missions, weather conditions, and drone/mule operational data, the project aims to **identify delays, optimize critical supply missions**, and **enhance operational readiness**.

Due to national security and confidentiality, **dummy data** has been generated to simulate real-world logistics operations.

---

## 📦 Tech Stack Used
- **Python (Pandas)** — Data cleaning and preprocessing
- **MySQL/SQLite** — Database creation and management
- **Power BI** — Interactive dashboard visualization

---

## 🗂️ Project Structure
OperationSuraksha/
│
├── README.md                  # Project documentation (this file)
├── logistics.csv         # Logistics mission data (dummy)
├── weather.csv           # Weather conditions data (dummy)
├── drone_ops.csv         # Drone/Mule operations data (dummy)
│
├── preprocessing.ipynb           # Python script for data cleaning and preprocessing
├── ArmyLogisticsDB.sql         # SQL script to create and populate the database
│
├── OperationSuraksha.pbix      # Power BI dashboard file (interactive report)



---

## 📊 Key Features
- Analyze **logistics mission success rates** by transport mode.
- Identify **critical reasons for delays** (weather, mechanical, operational).
- Correlate **weather conditions** with **mission delays**.
- Evaluate **drone vs robotic mule performance** under different terrains and conditions.
- Suggest **data-driven improvements** for faster, safer supply chain operations.
- Real-time dashboard insights for strategic planning.

---

## 📈 Power BI Dashboard Highlights
- 📌 **Mission Status** KPIs: Completed, Delayed, Critical Missions
- 📌 **Delay Reasons** Analysis: Weather Impact, Mechanical Failures
- 📌 **Transport Mode** Utilization Trends
- 📌 **Weather Conditions** over Time (Snowfall, Visibility, Windspeed)
- 📌 **Drone and Mule Performance** Metrics
- 📌 **Geographical Flow** Map (Optional)

---

## 📚 Data Description
> **Important Note**:  
The datasets used in this project are **dummy data** created to mirror real-world army logistics scenarios.  
Original Indian Army logistics and weather data could not be used due to **confidentiality and national security reasons**.

| Dataset | Description |
|---------|-------------|
| `logistics.csv` | Logistics missions data: sources, destinations, modes, status |
| `weather.csv` | Daily weather conditions at Ladakh bases and posts |
| `drone_ops.csv` | Drone and Robotic Mule delivery operational statistics |

---

## 🛠️ How to Run the Project
Clone the repository:
   git clone https://github.com/your-username/OperationSuraksha.git

Setup environment:

   Install Python packages: pandas

   Setup MySQL/SQLite database.

   Load the CSVs into your database.

   Open Power BI Desktop and connect to your database or directly load CSVs.

   Load the provided .pbix file.

   Analyze the dashboards and derive insights!

## 🧠 Insights Derived
Extreme weather (heavy snowfall, low visibility) significantly delays drone deliveries.

Robotic mules show better consistency but slower delivery rates.

Critical supplies often face disproportionate delays requiring urgent rescheduling based on weather forecasts.

Data-driven decision making can dramatically improve mission success rates in remote sectors.

## ✍️ Future Enhancements
Integrate real-time weather APIs (e.g., OpenWeatherMap) for live scheduling.

Build a predictive delay model using Machine Learning.

Expand datasets to cover other terrains like Siachen, Arunachal Pradesh.

## 🇮🇳 Motivation
The Indian Army stands as a pillar of strength and protection for every Indian.
Through this project, I aim to use my skills to contribute to enhancing operational excellence and ensuring the safety of soldiers and citizens alike.

## 📜 License
This project is a personal project created for educational and portfolio purposes.
No license is attached. All data used is dummy data created for simulation only.

## 🙏 Acknowledgements
Inspired by the Indian Army's unwavering dedication to protecting India's sovereignty.

Special thanks to open-source contributors and data visualization communities for providing the tools and inspiration.

