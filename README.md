# 💰 Fintech Loan Portfolio Risk Management Dashboard

## Purpose
This project delivers a **4-page interactive Power BI dashboard** designed for executive leadership and risk management teams at a consumer lending institution. Its core purpose is to replace static reporting with **real-time, data-driven analysis** to quantify risk exposure, identify unprofitable loan segments, and set clear targets for underwriting policy adjustments.

## Tech Stack & Data

| Category | Tool / Language | Details |
| :--- | :--- | :--- |
| **Business Intelligence** | Power BI | Primary visualization and interactive dashboarding. |
| **Data Transformation** | Power Query (M) | Advanced ETL, data cleaning, and handling of irregular character formats. |
| **Analytical Language** | DAX | Used for complex custom measures like `Default Rate` and `Total Charged Off Amount`. |
| **Modeling** | Star Schema | Established model for data integrity across all four pages. |
| **Data Source** | Loan & Customer Data (CSV) | Contains loan performance, borrower demographics, and regional mapping data. |

## 📊 Key Features & Walkthrough

### 1. Business Problem
The core challenge was scaling the loan portfolio responsibly. Management lacked a clear, real-time view of whether new volume growth was being offset by a disproportionate rise in defaults, particularly within specific geographic areas and customer demographics.

### 2. Goal of the Dashboard
The goal was to create a single source of truth that allows analysts to **isolate high-risk segments** instantly (e.g., Grade F loans in the South region) and quantify the **dollar impact** of defaults to inform strategic adjustments to pricing and underwriting criteria.

### 3. Walkthrough of Key Visuals (Briefly)

* **Executive Summary (Page 1):** Focuses on high-level health. The **Dual-Axis Chart (Volume vs. Default Trend)** immediately answers if growth is coming at the expense of loan quality. [Snapshot of page 1 (home_page).png]
* **Credit Risk & Performance (Page 2):** Diagnoses the financial cost. Key visuals include the **Total Charged Off Amount KPI** (dollar loss) and a matrix linking risk grade to interest rate and funded amount. [Snapshot of page 2.png]
* **Borrower Segmentation (Page 3):** Identifies the riskiest customers. The matrix connects high-risk loan grades (F/G) to specific **Annual Income Groups** to pinpoint high-risk demographics. [Snapshot of page 3.png]
* **Geographic Deep Dive (Page 4):** Provides spatial intelligence. The **Filled Map** and detailed scorecards allow for granular analysis of loss performance by specific regions and states. [Snapshot of page 4.png]

### 4. Business Impact & Insights

* **Financial Impact:** Introduced the **`Total Charged Off Amount`** measure, enabling management to quantify actual dollar losses and budget for risk provisioning accurately.
* **Profitability Optimization:** Identified specific loan types and regions where the interest rate charged did not adequately cover the observed default risk.
* **Strategic Underwriting:** Delivered intelligence to adjust underwriting criteria for identified high-risk segments (e.g., Grade F/G borrowers in the $50K-$100K income range).
* **Efficiency:** Automated the monthly risk reporting process, providing **near-real-time** insights and freeing up analyst time for strategic forecasting.

---

## 🖼️ Screenshots

The following snapshots illustrate the dashboard's design and analytical layout:

| Page Name | Screenshot |
| :--- | :--- |
| Executive Summary | ![Executive Summary Snapshot](Snapshot of page 1 (home_page).png) |
| Credit Risk & Performance | ![Credit Risk Snapshot](Snapshot of page 2.png) |
| Borrower Segmentation | ![Borrower Segmentation Snapshot](Snapshot of page 3.png) |
| Geographic Deep Dive | ![Geographic Deep Dive Snapshot](Snapshot of page 4.png) |






