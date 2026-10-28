# 🏆 FIFA World Cup Analysis | Power BI Dashboard

## 📌 Project Overview

This project analyzes historical **FIFA World Cup data** using **Microsoft Power BI** and the **Maven Analytics World Cup dataset**.

The dashboard combines historical World Cup information with detailed 2022 tournament and international match data to explore tournament trends, goals, matches, winning nations, host countries, and the growth of participating teams over time.

The main objective of this project was to transform raw football data into an **interactive and visually engaging dashboard** that makes historical World Cup statistics easier to explore and understand.

---

## 🎯 Project Objectives

* Analyze historical FIFA World Cup tournaments
* Track goals and matches across different tournaments
* Identify the most successful World Cup-winning nations
* Analyze World Cup host countries
* Understand how the number of qualified teams has changed over time
* Create interactive KPIs and visualizations using Power BI
* Practice DAX calculations and data modeling
* Build a dashboard suitable for business-style analytical storytelling

---

## 📂 Dataset

The project uses the **Maven Analytics World Cup dataset**, consisting of multiple tables:

| Table                    | Description                                                                                  |
| ------------------------ | -------------------------------------------------------------------------------------------- |
| `2022 World Cup Groups`  | Group-stage information from the 2022 World Cup                                              |
| `2022 World Cup Matches` | Detailed match information from the 2022 tournament                                          |
| `2022 World Cup Squads`  | Player and squad information                                                                 |
| `International Matches`  | International football match data                                                            |
| `World Cup Matches`      | Historical World Cup match-level data                                                        |
| `World Cups`             | Tournament-level information such as year, host, winner, goals, matches, and qualified teams |

---

## 📊 Key KPIs & DAX Measures

The dashboard includes several important KPIs developed using **DAX**:

* **Total World Cups**
* **Total Matches**
* **Total Goals**
* **Total Goals in World Cups**
* **Host Countries**
* **Champions**
* **Average Qualified Teams**
* **Average Matches per Tournament**

These measures were created to provide a quick overview of World Cup history and allow users to analyze the data interactively.

## 📈 Dashboard Visualizations

The dashboard includes the following visualizations:

### ⚽ Goals Across World Cups

A trend visualization showing how the number of goals scored has changed across different World Cup tournaments.

### 🏟️ Matches Played by Tournament

Displays the number of matches played in each World Cup tournament.

### 🏆 Top World Cup Winning Nations

Highlights countries with the highest number of World Cup victories.

### 🌍 World Cup Host Countries

A geographic visualization showing countries that have hosted the FIFA World Cup.

### 📊 Growth in Qualified Teams

Shows how the number of teams qualifying for the tournament has changed over the years.

## 🎛️ Interactive Filters

Users can interact with the dashboard using:

* **Year**
* **Host Country**
* **Winner**

These slicers allow users to explore specific tournaments, hosts, and winning nations.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **DAX**
* **Power Query**
* **Data Modeling**
* **Data Cleaning**
* **Data Visualization**
* **Maven Analytics Dataset**


## 🧮 DAX Concepts Used

Some of the important DAX concepts practiced in this project include:

* `COUNTROWS()`
* `DISTINCTCOUNT()`
* `SUM()`
* `AVERAGE()`
* `CALCULATE()`
* `FILTER()`
* `VALUES()`
* Context transition and filter context
* KPI calculations
* Aggregation and analytical measures

## 🔄 Data Preparation & Modeling

The project involved:

1. Importing multiple CSV datasets into Power BI
2. Reviewing and cleaning the data using Power Query
3. Checking column data types and missing values
4. Creating relationships between relevant tables
5. Building DAX measures for KPIs
6. Designing interactive visualizations
7. Adding slicers for dynamic filtering
8. Formatting the dashboard for better readability and storytelling

## 💡 Key Learning Outcomes

Through this project, I strengthened my understanding of:

* Building Power BI dashboards from multiple datasets
* Creating reusable DAX measures
* Understanding relationships between tables
* Working with filter context
* Designing KPI cards
* Creating interactive slicers
* Selecting appropriate visualizations
* Transforming raw data into meaningful insights
* Presenting analytical findings through data storytelling


## 📁 Repository Structure

FIFA-World-Cup-PowerBI/
│
├── Dataset/
│   ├── 2022_world_cup_groups.csv
│   ├── 2022_world_cup_matches.csv
│   ├── 2022_world_cup_squad.csv
│   ├── international_matches.csv
│   ├── world_cup_matches.csv
│   └── world_cups.csv
│
├── Dashboard/
│   └── FIFA_World_Cup_Analysis.pbix
│
├── Screenshots/
│   └── dashboard_preview.png
│
└── README.md
```

> **Note:** If the dataset files are too large for GitHub, you can exclude them and provide the original dataset source instead.

---

## 🚀 How to Use the Project

1. Clone or download this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. If required, update the dataset/file paths.
4. Refresh the data.
5. Use the slicers to explore different World Cup years, host countries, and winners.
6. Interact with the charts to explore historical World Cup trends.

---

## 📌 Project Highlights

This project demonstrates practical experience with:

**Power BI → DAX → Power Query → Data Modeling → Data Visualization → KPI Development → Interactive Dashboard Design**

It is part of my ongoing **Data Analytics and Power BI portfolio**, where I build projects using real-world datasets to strengthen my analytical and business intelligence skills.

---

## ⭐ If you found this project useful

Feel free to explore the repository and check out my other **Power BI and Data Analytics projects**.

