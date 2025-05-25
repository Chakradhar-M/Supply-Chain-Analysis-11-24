<h1 align="center">🚚 Supply Chain Analysis</h1>

<div style="display: flex; justify-content: space-between; padding: 10px; background-color: #f4f4f4; border-radius: 8px;">
  <h4>📅 Date: Nov 2024</h4>
  <h4>🛠️ Tools Used: Power BI, Figma, Excel</h4>
  <h4>🏷️ Domain: Supply Chain Analytics </h4>
</div>

---

### 📌 Background

The beauty and personal care industry is one of the fastest-growing markets globally, offering products like skincare, haircare, and cosmetics. Behind the scenes, a strong supply chain is critical to keep shelves stocked, fulfill online orders, and meet customer expectations.

In this industry, products are made from ingredients sourced from different suppliers. These materials are then sent to factories where products are manufactured, stored, and later transported to retail stores and warehouses. Many retail stores also serve as delivery hubs for online shoppers.

Managing this entire process, right from sourcing and manufacturing to delivery, requires constant tracking and improvement. If anything goes wrong, like low inventory or delayed shipping, it can impact both customer satisfaction and business profits. That’s why companies use data to understand how their supply chain is performing and to find areas for improvement.

This project focuses on helping a beauty products company analyze and improve its supply chain using Power BI.

---

### 🎯 Objective

To build an interactive Power BI report that supports the supply chain team by providing:

✔️ Insights into inventory movement and stock levels  
✔️ Evaluation of supplier performance and reliability  
✔️ Analysis of shipping timelines and cost efficiency  
✔️ Product-level performance metrics to guide decision-making

---

###  📂 Essential Project Links  

| 🧭 Resource | 🔗 Access |
|------------|----------|
| <img src="https://github.com/Chakradhar-M/PBI_Images/blob/main/Portfolio_Icons/database.png?raw=true" width="20" style="vertical-align:middle;"> **Data Source** | 👉 [Click to View Data Source](https://zoomcharts.com/en/microsoft-power-bi-custom-visuals/challenges/onyx-data-november-2024) |
| <img src="https://github.com/Chakradhar-M/PBI_Images/blob/main/Portfolio_Icons/power-bi.png?raw=true" width="22" style="vertical-align:middle;"> **Power BI Live Report** | 📊 [View Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzhjMjdjZmUtNjRmNC00NTFiLWFjOTctZDBhMzQ5NWRhZTExIiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9) |
| <img src="https://github.com/Chakradhar-M/PBI_Images/blob/main/Portfolio_Icons/youtube.png?raw=true" width="20" style="vertical-align:middle;"> **Project Presentation** | 🎬 [Watch Presentation](#) |
| <img src="https://github.com/Chakradhar-M/PBI_Images/blob/main/Portfolio_Icons/linkedin.png?raw=true" width="22" style="vertical-align:middle;"> **LinkedIn Post** | 🔗 [Read on LinkedIn](https://www.linkedin.com/posts/chakradhar-mantena_supply-chain-power-bi-report-activity-7266533596125896704-08lj?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD9y4SkBuDMCUOFBEF1QAO3K3-8MrRRtZZk) |

📌 **Tip:** Right-click or Ctrl + Click to open links in a new tab.

---

### 📊 Sample Raw Data

<div style="overflow-x:auto;">

<table>
  <thead>
    <tr>
      <th>Product&nbsp;type</th>
      <th>SKU</th>
      <th>Price</th>
      <th>Availability</th>
      <th>Number&nbsp;of&nbsp;products&nbsp;sold</th>
      <th>Revenue&nbsp;generated</th>
      <th>Customer&nbsp;demographics</th>
      <th>Stock&nbsp;levels</th>
      <th>Lead&nbsp;times</th>
      <th>Order&nbsp;quantities</th>
      <th>Shipping&nbsp;times</th>
      <th>Shipping&nbsp;carriers</th>
      <th>Shipping&nbsp;costs</th>
      <th>Supplier&nbsp;name</th>
      <th>Location</th>
      <th>Latitide</th>
      <th>Longitude</th>
      <th>Lead&nbsp;time</th>
      <th>Production&nbsp;volumes</th>
      <th>Manufacturing&nbsp;lead&nbsp;time</th>
      <th>Manufacturing&nbsp;costs</th>
      <th>Inspection&nbsp;results</th>
      <th>Defect&nbsp;rates</th>
      <th>Transportation&nbsp;modes</th>
      <th>Routes</th>
      <th>Costs</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>haircare</td>
      <td>SKU0</td>
      <td>69.80800554211577</td>
      <td>55</td>
      <td>802</td>
      <td>8661.996792392383</td>
      <td>Non-binary</td>
      <td>58</td>
      <td>7</td>
      <td>96</td>
      <td>4</td>
      <td>Carrier&nbsp;B</td>
      <td>2.956572139430807</td>
      <td>Supplier&nbsp;3</td>
      <td>Mumbai</td>
      <td>19.0760</td>
      <td>72.8777</td>
      <td>29</td>
      <td>215</td>
      <td>29</td>
      <td>46.27987924050832</td>
      <td>Pending</td>
      <td>0.22641036084992516</td>
      <td>Road</td>
      <td>Route&nbsp;B</td>
      <td>187.75207545920392</td>
    </tr>
    <tr>
      <td>skincare</td>
      <td>SKU1</td>
      <td>14.843523275084339</td>
      <td>95</td>
      <td>736</td>
      <td>7460.900065445849</td>
      <td>Female</td>
      <td>53</td>
      <td>30</td>
      <td>37</td>
      <td>2</td>
      <td>Carrier&nbsp;A</td>
      <td>9.71657477143131</td>
      <td>Supplier&nbsp;3</td>
      <td>Mumbai</td>
      <td>19.0760</td>
      <td>72.8777</td>
      <td>23</td>
      <td>517</td>
      <td>30</td>
      <td>33.61676895373</td>
      <td>Pending</td>
      <td>4.854068026388706</td>
      <td>Road</td>
      <td>Route&nbsp;B</td>
      <td>503.0655791496692</td>
    </tr>
    <tr>
      <td>haircare</td>
      <td>SKU2</td>
      <td>11.319683293090566</td>
      <td>34</td>
      <td>8</td>
      <td>9577.74962586873</td>
      <td>Unknown</td>
      <td>1</td>
      <td>10</td>
      <td>88</td>
      <td>2</td>
      <td>Carrier&nbsp;B</td>
      <td>8.054479261732155</td>
      <td>Supplier&nbsp;1</td>
      <td>Mumbai</td>
      <td>19.0760</td>
      <td>72.8777</td>
      <td>12</td>
      <td>971</td>
      <td>27</td>
      <td>30.688019348284204</td>
      <td>Pending</td>
      <td>4.580592619199229</td>
      <td>Air</td>
      <td>Route&nbsp;C</td>
      <td>141.92028177151906</td>
    </tr>
  </tbody>
</table>

</div>

🔗 Check out the **Data Dictionary** here 👉 [Click Here](https://github.com/Chakradhar-M/Supply-Chain-Analysis-11-24/blob/main/dataset/data_dictionary.md)

---
