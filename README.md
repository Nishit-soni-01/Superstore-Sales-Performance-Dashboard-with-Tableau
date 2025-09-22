# Superstore-Sales-Analysis-Tableau-Dashboard
### Dashboard Link: https://public.tableau.com/views/Superstore-Sales-Analysis-Tableau-Dashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
## Problem Statement

This project aims to create a holistic, multi-page Tableau dashboard for a deep-dive analysis of the Superstore sales data. The goal is to provide stakeholders with a comprehensive and interactive tool to monitor performance, identify trends, and make data-driven decisions. The dashboard is segmented into five key areas: a general **Overview**, and detailed dashboards for **Product**, **Customer**, **Shipping**, and **Returns** analysis.

### Steps Followed

-   **Step 1: Data Connection and Modeling**
    -   Connected to three distinct CSV files in Tableau: `Orders`, `Returns`, and `Users`.
    -   In the **Data Source page**, relationships (joins) were established between the tables. A key relationship was created between the `Orders` and `Returns` tables using `Order ID` to analyze returned sales.

-   **Step 2: Calculated Fields**
    -   Created several **Calculated Fields** to compute essential KPIs for each section of the dashboard.
    -   Key calculations include: `Total Sales`, `Total Profit`, `Count of Orders`, `Count of Returns`, `Return Rate %`, and `Average Shipping Days`.

-   **Step 3: Dashboard Design and Navigation**
    -   Designed a cohesive five-dashboard story with a consistent theme and clear navigation actions.
    -   Implemented interactive **Filters** on the overview dashboard for `Region`, `State`, and `Category` to allow users to filter the entire workbook dynamically.

-   **Step 4: Worksheet and Dashboard Creation**
    -   **Overview Dashboard:** Created high-level KPI text boxes, pie charts for "Sales by Category" and "Sales by Segment," and a dual-axis chart for "Sales and Profit over time."
    -   **Product Dashboard:** Built bar charts for "Sales by Sub-Category" and "Profit by Sub-Category," a scatter plot to analyze "Sales vs. Profit by Product," and a detailed product text table.
    -   **Customer Dashboard:** Designed a map for "Sales by State," a bar chart for the "Top 10 Customers by Sales," and a detailed customer table.
    -   **Shipping Dashboard:** Added KPI text boxes for shipping metrics, a pie chart for "Sales by Ship Mode," and charts analyzing shipping costs.
    -   **Returns Dashboard:** Included KPI text boxes for "Return Rate" and "Total Returned Sales," with bar charts breaking down "Returns by Category" and "Sub-Category."

-   **Step 5: Publishing**
    -   The final, interactive dashboard was published to **Tableau Public** (or Tableau Server) for accessibility and sharing.

---

# Dashboard Snapshot

The workbook contains multiple interactive dashboards for a comprehensive analysis of business operations.
<img width="1915" height="1037" alt="Screenshot 2025-09-22 202939" src="https://github.com/user-attachments/assets/ab506bb7-be32-45d0-9ce1-fb9178d96183" />
<img width="1911" height="1039" alt="Screenshot 2025-09-22 202928" src="https://github.com/user-attachments/assets/fdba97d3-ccd6-4bfe-8ef7-beaddcd26e62" />
<img width="1919" height="1029" alt="Screenshot 2025-09-22 202920" src="https://github.com/user-attachments/assets/8dd7586a-1579-4111-9b95-4a5fb278034c" />
<img width="1907" height="1044" alt="Screenshot 2025-09-22 202908" src="https://github.com/user-attachments/assets/51eb52d4-5c85-4b07-990b-6e77b7ce0d84" />
<img width="1899" height="978" alt="Screenshot 2025-09-22 202950" src="https://github.com/user-attachments/assets/d7c8cada-eab6-4f49-b055-68fd3938e96c" />



---

# Insights

### [1] Sales and Profit Overview

-   **Key KPIs:** The store generated **$2.3 Million in sales**, resulting in **$286.4K in profit** from over **5,000 orders**.
-   **Top Contributors:** The **Technology** category drives the most sales, and the **Consumer** segment is the largest customer group.
-   **Performance Trend:** The dual-axis chart shows a consistent seasonal trend, with sales and profits peaking near the end of the year.

### [2] Product Performance

-   **Top Sub-Categories:** **Phones** and **Chairs** are the highest-selling sub-categories.
-   **Profitability Issues:** While **Tables** generate significant sales, they are the **least profitable sub-category**, consistently resulting in a net loss.
-   **Product Analysis:** The scatter plot reveals specific products that, despite high sales, yield very low profit margins, highlighting areas for pricing strategy review.

### [3] Customer Insights

-   **Top Markets:** The map visualizes that **California** and **New York** are the two states with the highest sales.
-   **Key Customers:** The dashboard identifies and ranks the top 10 most valuable customers by sales, allowing for focused marketing and retention efforts.

### [4] Shipping and Logistics

-   **Primary Ship Mode:** **Standard Class** is the most utilized shipping method by a large margin.
-   **Efficiency:** The average shipping duration across all orders is approximately **4 days**.

### [5] Return Analysis

-   **Overall Return Rate:** The store has a **return rate of 5.91%**, with 296 orders returned.
-   **Problem Areas:** The "Returns by Sub-Category" chart indicates which products are most frequently returned, pointing to potential issues with product quality or customer expectations that need to be addressed.
