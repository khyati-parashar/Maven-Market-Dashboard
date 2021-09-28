# Maven-Market-Dashboard

This Project is an in-depth analysis of sales performance of a multi-national grocery chain with locations in Canada, Mexico and the United States.

The data source are csv files which are imported, transformed and loaded into the Power BI desktop.

The project includes the following:

**Fact Tables**

- Transaction_Data

- Returns_Data

**Dimension Tables**

- Calendar

- Customers

- Products

- Regions

- Stores

A **_"Matrix visual"_** has been inserted to show Total Transactions, Total Profit, Profit Margin, and Return Rate by Product_Brand with added conditional formatting to show data bars on the Total Transactions column, and color scales on Profit Margin (White to Green) and Return Rate (White to Red) and a **_visual level Top N filter_** is applied to only show the top 30 product brands.

A **_"KPI Card"_** has been added to show **Total Transactions, Total Profit, Total Returns** with Start of Month as the trend axis and Last Month Transactions, Last Month Profits,  Last Month Returns as the target goal.

A **_"Map visual"_** has been added to show Total Transactions by store city along with a **_"Slicer"_** for store country.

Next to the map, A **_"Treemap"_** visual to break down Total Transactions by store country has been added by pulling in store_state and store_city beneath store_country in the "Group" field to enable **drill-up and drill-down** functionality.

Beneath the map, A **_"Column Chart"_** has been added to show Total Revenue by week, and a **report level filter** has beed applied to only show data for 1998.

In the lower right, A **_"Gauge Chart"_** has been added to show Total Revenue against Revenue Target(which is applied as target value).

Besides the **_Store Country_** slicer in this report, every visuals can be used as a filter which can affect / interact with other visuals, but the interaction of the **Treemap** with the **Matrix** has been diabled using the **_"Edit interactions"_** option.
