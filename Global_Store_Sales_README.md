# Global Store Sales Performance Dashboard (Power BI)

An interactive Power BI dashboard that tracks sales, profit, cost, orders and quantity for a retail store. It shows where the money comes from, which regions and categories make a profit, how products are shipped, and how the sales team performs.

## Dataset

The data covers 9,994 order lines (5,009 orders) across four regions: Central, East, South and West. It is loaded into Power BI as a set of related tables:

| Table | What it holds |
|---|---|
| Orders | Order lines with sales, profit, cost and quantity |
| Customers | Customer details |
| Products | Product, category and sub-category |
| Locations | State and region |
| Shipment | Ship mode for each order |
| Sales Reps | Sales team members |
| Calendar | Date table used for month and year analysis |

Four helper tables (Overview_Parameter, State_Parameter, Top N Parameter and TopBottom) drive the interactive switches on the dashboard.

## What I did

1. **Loaded and prepared the data** in Power Query, and connected the tables in a relational data model.
2. **Built a Calendar table** so sales and profit can be compared by month, year, last month and last year.
3. **Wrote DAX measures** for Total Sales, Total Profit, Total Cost, Total Orders and Total Quantity, plus the month-over-month and year-over-year changes shown under each KPI card.
4. **Created parameters** so the viewer can switch between Total Profit and Total Sales, rank states by profit or sales, and show the Top or Bottom N states.
5. **Designed the dashboard** with KPI cards, a profit trend, a shipping breakdown, a state ranking, a profit decomposition tree and a sales team chart.

## Key findings

**Headline numbers**

| Metric | Value | vs last month | vs last year |
|---|---|---|---|
| Total Sales | $2.30M | +3.79% | +46.88% |
| Total Profit | $286.40K | +3.05% | +48.42% |
| Total Cost | $2.01M | +3.89% | +46.64% |
| Total Orders | 5,009 | | |
| Total Quantity | 37.87K | | |

Profit margin is about 12.5% of sales.

**Profit by region**

| Region | Profit | Share of total profit |
|---|---|---|
| West | $108,418 | 37.9% |
| East | $91,523 | 32.0% |
| South | $46,749 | 16.3% |
| Central | $39,706 | 13.9% |

West and East together produce about 70% of all profit.

**Profit by category (East region)**

| Category | Profit |
|---|---|
| Technology | $47,462 |
| Office Supplies | $41,015 |
| Furniture | $3,046 |

In the East, Technology and Office Supplies carry the profit, while Furniture adds very little.

**Quantity by ship mode**

| Ship mode | Units | Share |
|---|---|---|
| Standard Class | 22.8K | 60% |
| Second Class | 7.4K | 20% |
| First Class | 5.7K | 15% |
| Same Day | 2.0K | 5% |

**Sales by sales team**

| Team | Sales |
|---|---|
| Organic | $1.44M |
| Charlie | $0.24M |
| Delta | $0.23M |
| Bravo | $0.22M |
| Alfa | $0.17M |

Organic sales make up about 63% of total sales. The four named sales reps each contribute between $0.17M and $0.24M.

**Monthly profit trend**

Profit moves up and down from month to month, and it is higher in the later months of the year than in the early months.

## Dashboard features

- **Year slicer** to filter every visual to one year or all years.
- **Total Profit / Total Sales switch** to change the measure shown.
- **Top / Bottom buttons** with a **Rank by Profit / Rank by Sales** option to compare the best and worst states.
- **Decomposition tree** to break profit down by region, then by category.

## Tools

Power BI Desktop (Power Query, data modelling, DAX, parameters, interactive visuals)

## Author

Rofee'ah Tijani
GitHub: [Rofeeah-Tijani](https://github.com/Rofeeah-Tijani)
