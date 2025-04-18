

## 📐 Measures Table Documentation

| **Measure Name**                    | **Measure Function**                                                                 | **DAX Formula** |
|------------------------------------|--------------------------------------------------------------------------------------|-----------------|
| Average Defect Rate                | Calculates the average product defect rate.                                         | `AVERAGE(sc_data[Defect_Rates])` |
| Average Manufacturing Cost         | Computes the average manufacturing cost, excluding very low values (<5).            | `AVERAGEX(FILTER(sc_data, sc_data[Manufacturing_Costs] >= 5), sc_data[Manufacturing_Costs])` |
| Average Manufacturing Lead Time    | Calculates average lead time taken in manufacturing.                                | `AVERAGE(sc_data[Manufacturing_Lead_Time])` |
| Average Shipping Cost              | Returns the average cost of shipping products.                                      | `AVERAGE(sc_data[Shipping_Costs])` |
| Average Shipping Time              | Returns the average time taken for shipping.                                        | `AVERAGE(sc_data[Shipping_Times])` |
| Average Supplier Lead Time (Days)  | Calculates average delivery lead time from suppliers.                               | `AVERAGE(sc_data[Supplier_Lead_Time])` |
| Manufacturing Sites Count          | Counts the number of unique manufacturing sites.                                    | `DISTINCTCOUNT(sc_data[Manufacturing_Site])` |
| New Products Stock Value           | Sums the total value of newly produced stock.                                       | `SUM(sc_data[Newly Produced Stock Value])` |
| Number Of Products                 | Counts distinct SKUs to show product variety.                                       | `DISTINCTCOUNT(sc_data[SKU_Code])` |
| Stock At Store                     | Sums the available stock at store locations.                                        | `SUM(sc_data[Stock_At_Store])` |
| Warehouse Count                    | Counts the number of unique warehouse sites.                                        | `DISTINCTCOUNT(sc_data[WareHouse_Site])` |
| Total Shipping Cost                | Sums up all shipping costs.                                                         | `SUM(sc_data[Shipping_Costs])` |
| Total Revenue Generated            | Returns the total revenue from product sales.                                       | `SUM(sc_data[Revenue_Generated])` |
| Total Profit                       | Calculates profit by subtracting total cost from revenue.                           | `[Total Revenue Generated] - [Total Costs]` |
| Total Products Sold                | Total quantity of products sold.                                                    | `SUM(sc_data[Products_Sold_Qty])` |
| Total Production Volume            | Total number of products manufactured.                                              | `SUM(sc_data[Production_Volumes])` |
| Total Other Costs                  | Sums all other operational or indirect costs.                                       | `SUM(sc_data[Other_Costs])` |
| Total Order Quantities             | Sums the quantity of all orders placed.                                             | `SUM(sc_data[Order_Quantities])` |
| Total Manufacturing Cost           | Returns total manufacturing-related costs.                                          | `SUM(sc_data[Manufacturing_Costs])` |
| Total Costs                        | Calculates the sum of manufacturing, shipping, and other costs.                     | `[Total Manufacturing Cost] + [Total Other Costs] + [Total Shipping Cost]` |



