# Unable to upload the pbix file as the size is more than 25 mb 
# Client Analysis Dashboard – Power BI Project

---
## Description 
An interactive Power BI dashboard to analyze Client data, revenue performance, and profit using visually rich and dynamic reports.

---
## Dashboard Link 
https://app.powerbi.com/groups/me/reports/502c4c17-c9a9-4e5f-9133-e01e5d34aa0b/9d21e51f30bd0d09c715?experience=power-bi

---

## 📊 Project Features

- Track **YTD, QTD,MTD,** and **total revenue,total profit**
- Breakdown by **client code**,**client name** **financial year**,**financial quarter** and **region**
- Analyze **YoY%**,**QoQ%**,**MoM%**
- Identify **top-performing client**
- Insights on **client revenue**, **FTE**, and **costs**


---

## 🧩 Technologies Used

- **Power BI Desktop**
- **Power BI Servie**
- **DAX for Measures**
- **Excel (.xlsx)** as data source
- **Figma for background**
- **Slicers, Cards, Pie Charts, Maps, Line Charts**

---

## 📁 Folder Structure

car-sales-dashboard-powerbi/

├──    Client_Project.pbix # Power BI Dashboard file                                                                                                                          
├──   Client.xlsx # Source data file                                                                                                                                   
├──   docs/                                                                                                                                                               
├──   dashboard_screenshot.png                                                                                                                      
├──   README.md # Project documentation                                                                                                                                   
├──   LICENSE # MIT

## 🛠️ How to Use

1. Download or clone the repository
2. Open `Client_Dashboard.pbix` in Power BI Desktop
3. Refresh data using the attached `Client.xlsx` file
4. Interact with slicers and visuals to explore insights

## 📄 Pages Included

| Page No. | Page Name                  |
|----------|----------------------------|
| 1        | Client Summary          |
| 2        | Client Summary Table    |
| 3        | Profit Summary          |
| 4        | Profit Summary Table    |
| 5        | Revenue Summary         |
| 6        | Profit Summary Table    |

---

---

## 📷 Snap of Dashboad Pages (6) ,

<img width="1392" height="770" alt="1" src="https://github.com/user-attachments/assets/edea8f42-b7b4-4b42-8208-df2ef9b960ea" />

<img width="1388" height="763" alt="2" src="https://github.com/user-attachments/assets/16c1ca97-796c-46ba-9c82-3f8157d37507" />

<img width="1386" height="776" alt="3" src="https://github.com/user-attachments/assets/7dfeb5ae-7d14-42fb-8eea-94092cbc08ec" />

<img width="1392" height="767" alt="4" src="https://github.com/user-attachments/assets/f3a7d3c3-4ed1-4f54-8446-14b1f75c50f8" />

<img width="1382" height="772" alt="5" src="https://github.com/user-attachments/assets/5d62791d-375a-4934-bde3-084f6207ece0" />

<img width="1385" height="770" alt="6" src="https://github.com/user-attachments/assets/c3a5ddc8-bb03-4d9d-b281-b75b408b93d3" />



## 📊 Data Tables & Model

- **Main Table:** `Data` (Client, Profitability, Revenue)
- **Date Table:** 

- **Relationships:**
  - `Client[date]`  → `DateTable[date]` (Many-to-One)
  - `Profit[date]`  → `DateTable[date]` (Many-to-One)
  - `Revenue[date]` → `DateTable[date]` (Many-to-One)
  

Data Model
<img width="1236" height="783" alt="DataModelling" src="https://github.com/user-attachments/assets/9e72d41f-7921-4e0a-851a-1708803f3cf1" />




---

## License
MIT License – see LICENSE file for details.



## 📬 Contact

Created by **ROHIT CHANDORKAR**\
Let’s [connect on LinkedIn](https://www.linkedin.com/in/rohit-c-13a0bb117/) 




