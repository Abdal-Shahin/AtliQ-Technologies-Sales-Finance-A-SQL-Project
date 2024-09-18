## ATLIQ TECHNOLOGIES: SALES & FINANCE - A SQL PROJECT
<p align="center">
  <img src="https://github.com/user-attachments/assets/6c601e2a-0622-44c3-bcee-672c632e7cb3" alt="tech-gadgets-750x375">
</p>

## COMPANY OVERVIEW

**AtliQ Technologies**  
AtliQ Technologies is a leading computer devices manufacturer based in India, catering to 74 prominent customers, including Amazon and Croma. The company operates across 27 global markets, such as India, South Korea, and Italy, spanning 4 major regions. With a diverse product portfolio of 73 products and 26 variants (e.g., Plus, Standard), AtliQ specializes in 6 key segments, including peripherals, accessories, networking, and storage solutions.

## PROBLEM STATEMENT

AtliQ Technologies, a global computer devices manufacturer, faced challenges in gaining actionable insights from its large-scale sales data spread across 74 customers and 27 markets. The company needed to optimize its sales strategies by identifying key revenue drivers such as top-performing products, markets, and customers.

Additionally, AtliQ required detailed reports on sales performance across fiscal years, market share, and regional trends to enhance decision-making. However, the lack of fiscal year data and limited visibility into pre- and post-invoice sales deductions complicated their financial analysis and reporting.

To address these challenges, I utilized SQL to generate calculated columns, reports, stored procedures, and views that streamlined data processing and provided clarity on key performance indicators such as gross sales, net sales, and market share across regions.

## OBJECTIVES
- Identify key revenue drivers such as top-performing products, markets, and customers.

- Streamline financial analysis by generating detailed reports on gross sales, net sales, market share, and sales trends across fiscal years and regions.

- Provide clarity on pre- and post-invoice sales deductions, improving the accuracy of sales and revenue calculations.

- Deliver insights on forecast accuracy, market share, and regional performance

### DATASET: 
1.4 million records

### CALCULATED COLUMNS:
**1**. Created a fiscal year column from the date field.
<p align="center">
  <img src="https://github.com/user-attachments/assets/767c4020-97ed-4bca-9f0c-3340db943ecf" alt"Centered Image" />
</p>

### DERIVED INSIGHTS AND REPORTS:
**1**. What was the total gross price for transactions made by Croma in fiscal year 2021?
<p align="center">
  <img src="https://github.com/user-attachments/assets/6cbd3d71-8d3e-4096-814f-c8620480851a" alt="Centered Image" />
</p>

**2**. Monthly sales reports for Croma.
<p align="center">
  <img src="https://github.com/user-attachments/assets/71e613b4-9e5e-42a6-88e1-d22bf7196c84" alt="Image 3" />
</p>
 
**3**. Yearly sales reports for Croma.
<p align="center">
  <img src="https://github.com/user-attachments/assets/5d591ce6-bbbf-42f3-b25a-4fa9f3e3f393" alt="Image 4" />
</p>

**4**. Customer-wise Market share analysis.
<p align="center">
  <img src="https://github.com/user-attachments/assets/e5cde5a8-4dc1-4749-ab12-e85be19d2f83" alt="Image 16" />
</p>

**5**. Region-wise market share analysis.
<p align="center">
  <img src="https://github.com/user-attachments/assets/27077a46-cd71-41a9-8aff-bcbf704e0f73" alt="Image 17" />
</p>

**6**. Fiscal-Monthly Sales Trend
<p align="center">
  <img src="https://github.com/user-attachments/assets/bdf7251b-7456-44f1-8727-78710719290c" alt="Image 1" />
</p>

**7**. What's the Forecast Accuracy for AtliQ Technologies?
<p align="center">
  <img src="https://github.com/user-attachments/assets/5714e9f8-1ab8-4a92-ac7a-1751e51e4f77" alt="Image 2" />
</p>

### STORED PROCEDURES:
**1**. Monthly gross sales by customers.
<div align="center">
  <img src="https://github.com/user-attachments/assets/c43d1700-042b-427c-824c-4d9d72780162" alt="Proced Monthly Gross Sales">
</div>

  <p align="center">
  <img src="https://github.com/user-attachments/assets/bebf0cad-7ae3-4c46-80f9-f3339fa2cadd" alt="Image 5" />
</p>
C_code = Customer code

**2**. Market type breakdown.
<p align="center">
  <img src="https://github.com/user-attachments/assets/7b72f70a-e6f2-40d5-bd55-ff0c27111a5c" alt="Image 7" />
  <br />
  <img src="https://github.com/user-attachments/assets/ad042db8-0aae-4be4-ab90-e7b1ab18ac18" alt="Image 6" />
</p>

### VIEWS CREATED:
<p align="center">
  <img src="https://github.com/user-attachments/assets/b4d1e5ad-417e-4a2d-8955-b9a38110592c" alt="Image 8" />
</p>

**1**. Gross sales
<div align="center">
  <img src="https://github.com/user-attachments/assets/58e82217-74d8-4bc6-a7cb-bf649c741368" alt="View gross sales 1"><br>
  <img src="https://github.com/user-attachments/assets/cdd8244c-2a8a-4996-ab3b-0f515477d42b" alt="View gross sales 2">
</div>  

**2**. Net invoice sales
<div align="center">
  <img src="https://github.com/user-attachments/assets/982da616-efcf-4fba-9634-e26bf656cdd3" alt="View NIS 1"><br>
  <img src="https://github.com/user-attachments/assets/de1a7492-dfc8-4d4e-9e94-a718820eec7a" alt="View NIS 2">
</div>


**3**. Net sales
<div align="center">
  <img src="https://github.com/user-attachments/assets/147cab8b-0e23-46af-a58e-2202fa193dd6" alt="View NS 1"><br>
  <img src="https://github.com/user-attachments/assets/6a6a5c4e-96e8-4f34-9541-fabb4fc08696" alt="View NS 2">
</div>

**4**. Post-invoice deductions
<div align="center">
  <img src="https://github.com/user-attachments/assets/be71980c-3e6a-4a16-8e0f-21909f9f7e2a" alt="View PID 2"><br>
  <img src="https://github.com/user-attachments/assets/5b93585b-3d99-49bc-9ad7-6e608d12ce87" alt="View PID 1">
</div>

**5**. Pre-invoice discounts
<div align="center">
  <img src="https://github.com/user-attachments/assets/3f9bfe6f-7cd2-4ba9-b6b6-db21e23b6dd0" alt="PID2"><br>
  <img src="https://github.com/user-attachments/assets/ada5ccc0-a130-439e-a6da-efd66eaf1fb7" alt="PID1">
</div>

### CONCLUSION 
●	In this project, I presented insights on 10+ ad-hoc business requests to the executive management team, by querying 1million+ rows database using SQL.

●	Designed and implemented 4+ views, and stored procedures that delivered valuable insights to the executive team.

●	Led the initiative to generate sales and forecast trend reports; and identifying top-performing markets, products, and customers, empowering stakeholders to analyze data effectively and make informed strategic decisions.
