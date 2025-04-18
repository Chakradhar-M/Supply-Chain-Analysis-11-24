
##  Data Model Documentation  

- This project is built on top of **processed flat data**, so no formal data modeling (like relationships or star schema) was required.

- The report uses **three independent tables**, each serving a specific purpose in the analysis:

### 1️⃣ `sc_data`  
Main fact-style table containing all supply chain records such as product details, inventory, shipping, manufacturing, and supplier info.

### 2️⃣ `selected_metric`  
A helper table used for parameter selection in visuals or dynamic measures.

### 3️⃣ `measures_table`  
A disconnected table created to hold key DAX measures used throughout the report for performance tracking and KPI display.

### **Data Model Screeshot**
![Supply Chain Data Model](https://github.com/Chakradhar-M/Supply-Chain-Analysis-11-24/blob/main/resources/supply_chain_data_model.png?raw=true)
