# Insurance Analytics Suite

- **Short Description:**  
  This project presents an end-to-end data analytics implementation for the insurance domain. Using MySQL as the backend and Power BI for visualization, the dashboards provide actionable insights into portfolio profitability, claim patterns, and underwriting efficiency, replicating a real-world analytics environment.
  
---

- **Tech Stack:**  
  - **Power BI** – for dashboard creation and visualization  
  - **MySQL** – for data storage, transformation, and modeling  
  - **SQL Queries** – for data extraction and preparation  
  - **DAX (Power BI)** – for calculated measures and KPIs  
  - **Excel/CSV** – as the initial data source  

---

- **Data Source:**  
  Data was designed to simulate an **insurance company’s operational database**, containing:  
  - **insurance_policy** – policy-level details, effective and expiry dates, premiums, and status.  
  - **insurance_claim** – claim-level details with amounts paid, reserves, and loss severity.  
  - **insurance_exposure** – exposure type, insured values, and risk categories.  
  - **insurance_transaction** – financial movements related to claims and premiums.  
  - **insurance_account** – customer and regional mapping.
 
  These datasets were stored in **MySQL**, queried through **SQL joins**, and then connected to **Power BI** via the MySQL connector.

---

- **Features and Highlights:**

  **The Business Problem:**  
  Insurance firms need real-time visibility into premium performance, claim patterns, and underwriting results to reduce loss ratios and improve profitability.

  **The Goal of the Dashboard:**  
  To create a unified reporting solution that enables stakeholders to:  
  - Track premium and loss trends.  
  - Identify regional and product-level performance.  
  - Analyze claim behavior and risk concentration.  
  - Evaluate underwriting quality and portfolio health.  

  **Key Visuals and Their Purpose:**  
  1. **Insurance Performance Overview** – Executive summary of overall performance.  
     - KPIs for Total Premium, Paid Losses, Loss Ratio, and Reserve Ratio.  
     - Treemap for product-level contribution to loss ratio.  
     - Combo chart for monthly premium vs incurred losses.  
     - Matrix showing reserve concentration by region.  
  2. **Claim & Risk Analysis** – Operational insight into claim patterns.  
     - Donut chart for claim status distribution.  
     - Gauge for overall loss ratio.  
     - Line area chart for paid losses vs reserves trend.  
     - Regional claim activity comparison.  
  3. **Underwriting & Operational Insights** – Portfolio health and efficiency analysis.  
     - KPI cards for Policy Count, Premium, Exposures, and Renewal Rate.  
     - Funnel chart visualizing policy lifecycle stages.  
     - Column chart for regional growth or attrition.  
     - Detailed policy table with premium and loss ratio indicators.  

  **Business Impact and Insights:**  
  - Provided a clear view of loss ratio trends across product lines and regions.  
  - Helped identify underperforming regions and exposure types driving high reserve ratios.  
  - Highlighted claim handling efficiency and reserve management quality.  
  - Enabled executives to monitor underwriting mix (Renewed, Expired, InForce, Cancelled) and its financial impact.  
  - Overall improved decision-making on pricing, risk management, and claims control.

---

- **Screenshot:**  
  - [Insurance Performance Overview](https://github.com/shandilyaswagat/Insurance-Dashboard/blob/main/Insurance_Performance_Dashboard.png)  
  - [Claim & Risk Analysis](https://github.com/shandilyaswagat/Insurance-Dashboard/blob/main/Claim_Risk_Analysis.png)  
  - [Underwriting & Operational Insights](https://github.com/shandilyaswagat/Insurance-Dashboard/blob/main/Underwriting_Operaton_Insights.png)

