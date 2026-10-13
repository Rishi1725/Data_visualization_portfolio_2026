Data Visualization Portfolio | 2026
A portfolio of business intelligence, data analysis, and visualization projects focused on transforming data into actionable business insights. This portfolio demonstrates analytical problem-solving, profitability analysis, data preparation, interactive reporting, and data-driven decision-making using Tableau, Power BI, Excel, SQL, and Python.

Featured Projects

1. E-Commerce Profitability Analysis
Business Question: Which product subcategory should receive the first margin-recovery review?
Dashboard: Explore the Profitability Analysis https://public.tableau.com/views/Assignment1430/ExploratoryDashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link 
Key Finding / Next Step: Investigate the cost and revenue drivers behind Tables' negative profitability to identify potential margin-recovery opportunities.

2. Southwest Office Solutions Account Portfolio Analysis
Business Question: Which customer segments and service tiers should be reviewed to improve net contribution?
Dashboard: Explore the Account Portfolio Analysis https://public.tableau.com/views/BNAN_Retail_Order_Analysis_Pt_2_17900574812170/AccountPortfolioDashboard?:language=en-US&:display_count=n&:origin=viz_share_link 
Key Finding / Next Step: Investigate the costs and account characteristics contributing to negative net contribution in the Consumer and Corporate Inside Sales segments.


DataCamp Certifications

3. Introduction to Power BI

Completion Date: September 29, 2026
Provider: DataCamp, in collaboration with Microsoft
Published Tableau Story: View Certification Story https://public.tableau.com/views/PowerBI-DatacampTrainingCertificate/PowerBIStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

Professional Reflection
Power BI provides an integrated environment for transforming business data into interactive reports that support decision-making. In Flex 3 or Flex 4, I manually summarized data to prepare results for analysis, while Power BI can aggregate data directly within visuals and refresh results as the underlying data changes. I would choose Power BI for recurring reporting because its data preparation, modeling, and visualization capabilities support consistent analysis across larger datasets. This allows business stakeholders to compare performance, explore trends, and access relevant insights without relying on manually updated summaries.

Key Insights
- Data Preparation: Power Query supports repeatable data-cleaning and transformation workflows.
- Interactive Reporting: Filters, slicers, and drill-downs help users investigate trends and compare business performance.
- Reporting Efficiency: Integrated data modeling and visualization can reduce manual reporting work and simplify recurring updates.

4. Introduction to DAX in Power BI

Completion Date: October 4, 2026
Provider: DataCamp
Published Tableau Story: View Certification Story https://public.tableau.com/views/PowerBI-DatacampTrainingCertificate/PowerBIStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

Professional Reflection
One calculation I created was AvgProfit_x = AVERAGEX(Sales, Sales[ItemPrice] - Sales[ItemCost]), which calculates the average difference between item price and item cost across the Sales table. I would implement this as a measure when the goal is to analyze average profit dynamically across product categories or other report filters. This calculation turns transaction-level price and cost information into a profitability metric that helps stakeholders compare products and identify stronger-performing areas. These insights can support more informed pricing and product decisions without manually recalculating results for each category.

Key Insights
- DAX Calculations: AVERAGEX evaluates an expression for each row and averages the resulting values.
- Measures and Filter Context: Measures can recalculate based on the current report context, supporting interactive comparisons.
- Business Application: Average price-cost differences help stakeholders compare products, subject to the costs included in the source data.

5. Data Visualization in Power BI

Completion Date: October 12, 2026
Provider: DataCamp
Published Tableau Story: View Certification Story https://public.tableau.com/views/PowerBI-DatacampTrainingCertificate/PowerBIStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

Professional Reflection
One calculation I created was Orders Above Target Profit Margin = SUMX(Orders, IF(Orders[Profit_Margin] > Orders[Target Profit Margin], 1, 0)), which counts rows where actual profit margin exceeds the target profit margin. I would use this as a measure to display how many order rows meet the profitability goal and allow stakeholders to explore the results using interactive filters. Turning row-level comparisons into a clear performance indicator makes it easier to monitor target attainment and investigate differences across products or categories. This helps business users identify areas that need attention and make more informed decisions using focused, interactive visualizations.

Key Insights
- KPI Development: Conditional DAX logic can turn row-level comparisons into an aggregate performance indicator.
- Visual Design: Clear charts, focused KPIs, and relevant filters help stakeholders identify patterns without unnecessary clutter.
- Business Application: Comparing actual and target margins helps stakeholders monitor profitability goals and investigate areas requiring attention.


---Technical Skills Demonstrated---

- Business Intelligence
  - Power BI report development and dashboard creation
  - Data modeling and table relationship management
  - Interactive reporting for business performance monitoring

- Data Preparation
  - Data cleaning and transformation using Power Query
  - Data organization and preparation for analysis
  - Repeatable data preparation workflows for report refreshes

- DAX and Calculations
  - Developing measures and calculated columns using DAX
  - Applying iterator functions such as `AVERAGEX` and `SUMX`
  - Implementing conditional logic and filter-responsive calculations

- Data Visualization
  - Selecting appropriate charts and visuals for business questions
  - Designing KPI indicators and applying conditional formatting
  - Building interactive reports using slicers, filters, and drill-downs

- Business Analysis
  - Evaluating product profitability using price and cost data
  - Monitoring actual profit margins against target margins
  - Comparing business performance across products and categories

- Analytical Communication
  - Translating technical calculations into business-relevant insights
  - Presenting performance metrics through clear, focused visualizations
  - Communicating findings to support data-driven business decisions
