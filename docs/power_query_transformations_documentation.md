
##  Power Query Transformation Documentation  


### `sc_data` Table Transformations

**Source**:  
`C:\Users\projects\supply_chain_analytics\sc_data.xlsx`

**Transformations Performed:**

1. **Imported Excel Workbook**  
   - Loaded the `sc_data` worksheet from the specified file path.

2. **Promoted Headers**  
   - Converted the first row of the dataset into column headers for usability.

3. **Changed Column Data Types**  
   - Assigned appropriate data types to each column to ensure consistency:
     - **Whole Number**: `Stock_At_Store`, `Products_Sold_Qty`, `Stock_At_Warehouse`, `Lead_Times`, `Order_Quantities`, `Shipping_Times`, `Supplier_Lead_Time`, `Production_Volumes`, `Manufacturing_Lead_Time`, `Total_Available_Stock`, `Demand`, `Supply`
     - **Decimal Number**: `Unit_Price`, `Revenue_Generated`, `Shipping_Costs`, `Manufacturing_Costs`, `Defect_Rates`, `Other_Costs`, `Latitude`, `Longitude`
     - **Text**: `Product_Type`, `SKU_Code`, `Customer_Demographics`, `Shipping_Carrier`, `Supplier_Name`, `Location`, `Inspection_Results`, `Transportation_Mode`, `Shipping_Routes`, `Manufacturing_Site`, `WareHouse_Site`, `Stock_Status`

4. **Removed Unnecessary Column**  
   - Dropped `Column1`, which was an index or placeholder column not required for analysis.

5. **Trimmed Text in SKU_Code**  
   - Applied `Text.Trim` on the `SKU_Code` column to remove any leading or trailing spaces, ensuring cleaner joins and filtering downstream.

---

###  `selected_metric` Table Transformations

**Source**:  
`C:\Users\projects\supply_chain_analytics\selected_metric.xlsx`

**Transformations Performed:**

1. **Imported Excel Workbook**  
   - Loaded the `selected_metric` worksheet from the specified file path.

2. **Promoted Headers**  
   - Promoted the first row as headers to make column names readable and analyzable.

3. **Changed Column Data Types**  
   - Assigned the following data types:
     - **Text**: `Selected_Metric`
     - **Whole Number**: `Index`

