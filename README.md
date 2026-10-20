# SwiftLog Logistics Supply Chain Analytics & Business Intelligence

An end-to-end Business Intelligence and Data Analytics project focused on analyzing supply chain operations, order fulfillment, inventory management, delivery performance, returns, and revenue realization for **SwiftLog Logistics Limited, Nigeria**.

## 📌 Executive Summary

SwiftLog Logistics Supply Chain Analytics & Business Intelligence is a data analytics project completed as part of the **AnalystLab Africa Internship**, Data Analytics Track.

The project aims to help SwiftLog Logistics understand operational performance, identify delivery bottlenecks, monitor inventory distribution, evaluate order cancellations and product returns, and support evidence-based business decisions.

The analysis uses 11 datasets covering customers, orders, order items, products, suppliers, warehouses, inventory, shipments, delivery performance, employees, and returns.

The datasets include:

- 5,000 orders
- 1,000 customers
- 250 products
- 150 suppliers
- 15 warehouses
- 200 employees
- 15,000 order-item records
- 5,000 shipment records

The project uses Microsoft Power BI to develop an interactive business intelligence dashboard, supported by data preparation, data modeling, DAX calculations, KPI analysis, and business recommendations.

## 🎯 Project Objectives

- Evaluate order fulfillment and delivery performance.
- Analyze revenue realization, cancellations, and pending orders.
- Identify inventory imbalances and potential stock availability issues.
- Assess product returns and their recorded causes.
- Understand customer retention and revenue contribution.
- Develop an interactive Power BI dashboard for operational monitoring.
- Provide actionable recommendations to support management decision-making.
- Document data quality issues, assumptions, and analytical limitations.

## 📊 Key Performance Indicators (KPIs)

The following preliminary results were supplied during the project analysis and should be reconciled against the final Power BI measures before submission.

| KPI | Reported Result |
|---|---:|
| Delivered revenue | ₦7.11 million |
| On-time delivery rate | 36.28% |
| Cancellation rate | 32.52% |
| Cancelled orders | 1,706 |
| Pending orders | 1,716 |
| Product return rate | 9.46% |
| Customer retention rate | 95.96% |
| Total recorded inventory | Approximately 1.01 million units |

**Note:** KPI definitions, calculation methods, denominators, and reporting filters should be documented. Inventory turnover and other derived measures must be validated against their appropriate units and time periods.

## 🛠️ Data Preparation and Modeling

### 1. Data Import and Preparation

The project involved importing 11 CSV datasets into Power BI and examining their structure, column names, data types, keys, relationships, and data quality.

Key preparation activities included:

- Inspecting datasets and profiling records.
- Checking missing values and duplicate records.
- Reviewing date formats and data type consistency.
- Standardizing fields where necessary.
- Investigating repeated inventory records.
- Validating primary and foreign keys.
- Documenting assumptions and limitations arising from the available data.

### 2. Data Modeling

The datasets were reviewed to establish appropriate relationships and support analysis across orders, customers, products, inventory, shipments, warehouses, employees, and returns.

The final model should reflect verified relationships and suitable table granularity. Supplier-level performance analysis requires additional supplier-to-product, order-item, or shipment mappings because the supplied Suppliers dataset contains only `SupplierID` and `SupplierName`.

### 3. Analytics and DAX

Power BI measures and calculated fields support analysis of revenue, order status, delivery duration, delivery delays, returns, and inventory.

All measures should be validated against the underlying records and documented business definitions before final reporting.

## 📈 Power BI Dashboard

The project dashboard is organized around the following analytical areas:

1. **Executive Overview** — high-level KPIs for orders, revenue, cancellations, and operational performance.
2. **Customer Analytics** — customer distribution, purchasing patterns, retention, and revenue contribution where supported by the available data.
3. **Inventory and Warehouse Management** — recorded inventory levels, stock distribution, and potential stock imbalances.
4. **Shipment and Delivery Performance** — delivery outcomes, delays, delivery duration, and comparisons across available regions.
5. **Supplier and Product Performance** — product contribution and returns analysis, with supplier-level assessments subject to verified data relationships.

The dashboard is intended to provide management with a consolidated view of business performance and help identify areas requiring operational attention.

## 🔍 Key Business Insights

The following findings are based on the preliminary figures provided during the analysis and must be checked against the final dashboard.

### 1. Delivery and Fulfillment

The reported on-time delivery rate of 36.28% is below the stated operational target of 80%. This indicates a need to investigate delivery delays, dispatch processes, regional differences, and other potential causes of poor fulfillment performance.

### 2. Revenue Realization and Cancellations

The preliminary analysis reports delivered revenue of ₦7.11 million and 1,706 cancelled orders. These results indicate that order cancellations may be an important area for further investigation.

Cancelled order value and realized revenue should be calculated using consistent order-level definitions. Freight expenditure on cancelled orders should not be described as a confirmed loss unless dispatch and freight-cost records substantiate it.

### 3. Inventory Distribution

The supplied data contains repeated warehouse-product combinations with different recorded stock values and no inventory date field. Consequently, total recorded inventory does not automatically establish current stock availability, inventory movement, or turnover.

Warehouse-level stock imbalances and possible shortages should be verified against demand, replenishment, and inventory transaction records.

### 4. Product Returns

The preliminary analysis reports a product return rate of 9.46%, with wrong-item shipments and transit damage identified as important recorded return reasons.

These findings support investigating picking accuracy, packaging standards, handling procedures, and the consistency of return-reason records.

### 5. Data Quality and Supplier Visibility

The available supplier data does not establish direct relationships between suppliers and individual products or shipments. Supplier scorecards therefore require additional relationship data before supplier-specific performance conclusions can be supported.

## 💡 Business Recommendations

1. **Improve delivery performance:** Investigate the causes of delays, monitor overdue shipments, and establish achievable improvement targets leading toward the 80% operational target.

2. **Reduce cancellations:** Analyze cancellation reasons and introduce order confirmation and status monitoring before dispatch where operationally appropriate.

3. **Improve inventory visibility:** Validate repeated inventory records, establish reliable stock-level reporting, and investigate potential shortages and excess stock across warehouses.

4. **Strengthen fulfillment quality:** Introduce picking verification, barcode scanning where feasible, and appropriate packaging standards to reduce wrong-item shipments and transit damage.

5. **Improve customer experience:** Monitor delivery complaints, repeat purchasing, and customer-level service outcomes before designing targeted retention initiatives.

6. **Strengthen supplier data:** Capture supplier relationships at the appropriate product or order-item level to enable reliable supplier performance analysis.

7. **Improve data infrastructure:** Maintain consistent date and timestamp fields, document KPI definitions, and implement data validation checks to improve the reliability of future reporting.

## 📉 Expected Business Impact

If implemented and evaluated using appropriate baseline measures, the recommendations could help SwiftLog Logistics:

- Improve delivery reliability and customer satisfaction.
- Reduce preventable cancellations and fulfillment errors.
- Improve inventory allocation and stock visibility.
- Strengthen revenue monitoring and operational cost control.
- Improve supplier accountability when supporting relationship data becomes available.
- Enable faster, evidence-based management decisions through Power BI.

These are expected benefits rather than confirmed financial savings. Their actual impact should be measured against validated baseline KPIs after implementation.

## 💻 Technology Stack

- **Business Intelligence:** Microsoft Power BI
- **Data Preparation:** Power Query
- **Analytics:** DAX and Power BI data modeling
- **Data Sources:** 11 relational CSV datasets
- **Documentation and Version Control:** Markdown and GitHub

## 📁 Project Deliverables

The project follows the required Week Five folder structure:

- `Data/` — original datasets.
- `Dashboard/` — final Power BI dashboard file.
- `Report/` — Executive Business Intelligence Report and dashboard screenshots PDF.
- `Presentation/` — executive presentation.
- `Images/` — project and dashboard visuals.
- `References/` — supporting sources and references.
- `README.md` — project overview and documentation.

## 👤 Author and Attribution

**Author:** Victoria Kosgei  
**Program:** AnalystLab Africa Internship  
**Track:** Data Analytics  
**Client Case Study:** SwiftLog Logistics Limited  
**Project:** SwiftLog Logistics Supply Chain Analytics & Business Intelligence

---

*This project was developed as part of the AnalystLab Africa Internship to apply data preparation, data modeling, business intelligence, and analytical problem-solving skills to a supply chain operations case study.*
