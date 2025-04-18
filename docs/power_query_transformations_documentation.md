

##  Power Query Transformation Documentation

###  Table: `sc_data`

| **Step**                          | **Description**                                                                                                                                              |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Source**                       | Connected to the Excel file located at `C:\Users\projects\supply_chain_analytics\sc_data.xlsx`.                        |
| **Navigation**                   | Navigated to the sheet named `"sc_data"` and loaded it into Power Query.                                                                                     |
| **Promote Headers**              | Promoted the first row to column headers using `Table.PromoteHeaders` to give meaningful names to each column.                                              |
| **Change Column Types**          | Used `Table.TransformColumnTypes` to assign correct data types (e.g., `Int64.Type`, `type number`, `type text`) to all relevant columns.                    |
| **Remove Unnecessary Column**    | Removed the unnamed `"Column1"` column using `Table.RemoveColumns`, as it was not required for analysis.                                                    |
| **Trim Text in SKU Code**        | Applied a transformation on the `SKU_Code` column using `Text.Trim` to remove any leading/trailing spaces.                                                  |


> The table is clean, with all column headers properly defined, types correctly set, and only relevant data retained for modeling and analysis.

---

###  Table: `selected_metric`

| **Step**                          | **Description**                                                                                                                                              |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Source**                       | Connected to the Excel file located at `C:\Users\projects\supply_chain_analytics\selected_metric.xlsx`.                |
| **Navigation**                   | Navigated to the sheet named `"selected_metric"` and loaded it into Power Query.                                                                             |
| **Promote Headers**              | Promoted the first row to headers using `Table.PromoteHeaders` to provide clear column labels.                                                               |
| **Change Column Types**          | Assigned data types using `Table.TransformColumnTypes`: `Selected_Metric` as `text` and `Index` as `Int64.Type`.                                            |




> This table is ready for use in parameter selection, slicers, or dynamic visuals



