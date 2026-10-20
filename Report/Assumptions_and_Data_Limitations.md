# Assumptions and Data Limitations

1. **Supplier relationships:** The supplied Suppliers dataset contains SupplierID and SupplierName but no corresponding supplier key in the other datasets. Suppliers are therefore treated as a standalone reference table. Supplier-level performance cannot be measured reliably without a valid mapping to products, shipments or other operational records.

2. **Warehouse capacity:** The Warehouses dataset provides WarehouseID and Location but does not contain physical storage capacity. Warehouse comparisons will therefore use clearly labelled operational proxies, such as inventory quantity or shipment volume, rather than claiming to measure actual capacity utilization.

3. **Inventory records:** Repeated warehouse–product combinations are treated as separate inventory transactions or stock movements, in line with the project guidance. These records will not be removed as duplicates. Quantities will be aggregated where appropriate, subject to validation of the stock field's meaning and units.

4. **Business definitions:** The supplied data dictionary does not provide detailed field definitions or all business rules. Definitions for delivery performance, returns, inventory metrics and other KPIs will be inferred from the available fields and documented alongside the relevant calculations.

5. **Data completeness:** All findings are based on the supplied datasets. Missing relationships, unavailable business attributes and any unresolved data-quality issues may limit the conclusions that can be drawn.

These limitations will be considered when interpreting KPIs and making recommendations. Future data collection should include supplier-to-product mappings, warehouse capacity information, inventory transaction dates and types, and formal definitions of operational KPIs.

