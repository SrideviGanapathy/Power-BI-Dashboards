### AdventureWorks Purchasing & Inventory Analysis Dashboard

This Power BI Dashboard was created from one of Microsoft's sample databases: AdventureWorks 2022. AdventureWorks is a fictious bicycle and accessories manufacturing company selling its product across six countries in total in North America, Europe and Asia Pacific. The database was hosted in SQL Server 2022 and was brought into Power BI using SQL queries.

The goal of this dashboard is to provide insights into Purchasing and Inventory data of the company, thereby shedding light on parts of the company's supply chain. The dashboard has two pages: Purchasing/Supplier analysis and Inventory analysis.

##  Purchasing/Supplier analysis

* The data table indicates the supplier credit rating (based on their performance), rejection % and average lead time of each of the suppliers. From this visual, an overview of the quality, speed and performance level of the suppliers can be understood.

* The timeliness of order fulfillment pie chart indicates that except for a fractional percentage of orders which were on-time or late, a huge portion of the orders (99.86%) was fulfilled early i.e (before expected delivery). This implies that AdventureWorks' suppliers are very relaible with respect to timely deliveries.

* On analysing the accuracy of order quantity, 8.8% of the orders were found to be incomplete i.e, the supplier delivered lesser number of components than that was ordered. Incomplete orders can lead to unexpected shortages in inventory. Purchasing professionals can try to minimise this percentage through discussions with suppliers and careful monitoring.

* The rejected quantity and rejection % graph illustrates the total quantity of components rejected from each supplier and the percentage. The highest rejection quantities were from SUPERSALES, Vision Cycles and Prosevare. The highest rejection percentages were from International (5.88%), Anderson's Custom Bikes (5.38%) and Signature Cycles (5.35%). These suppliers have to be monitored and encouraged to increase their qualty checks before dispatch.

* The purchase order status visual shows that 92.36% of all purchase orders have been completed and 5.39% of the the orders are pending.

## Inventory Analysis

* Analysis of invnetory by the material type indicates that majority of the inventory value ($19M) is held by finished goods and raw materials occupies $9M in value.

* The current total inventory value was analysed to be $28.18M compared to the target of $33.66M . The target value was arrived at by calculating the inventory cost of maintaining all materials and products at the safety stock level. In this case, current inventory is lower than the target which is a good sign indicating the inventory is within optimal level.

* The raw material table shows the components purchased from suppliers that require reorder or monitoring. The components that have fallen below the reorder point need to be reordered (Hex Nut 1 & Lower Head Race) and the components lying below the safety stock level but above reorder point require keen monitoring from the purchasing team.

* On analysing the inventory status of the materials, on the whole, 363 components/products have sufficient stock levels, 79 require reorders and 62 require monitoring. The 79 components that require reordering need the immediate attention to avoid issues in the supply chain.

* The inventory value table shows the total current inventory value of every individual material or product. The table indicates that HL Mountain Frame Black has the highest inventory value ($0.6M).

* On analysing inventory value by the subactegory of finished goods, Road Bikes ($6.9M) had the highest inventory value followed by Mountain Bikes ($4.8M) and and Touring Bikes ($2.9M).

## Conclusion

This dashboard provides insights into the purchasing and inventory data of the company which would be valuable for purchasing and supply chain professionals within the company to monitor the costs and ensure material availability for manufacturing.
