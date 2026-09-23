# Automotive Sales Report and Market Analysis | CoolCars

A Power BI portfolio project that brings together CoolCars internal performance data and wider automotive market data. The aim is to explore how vehicle sales, product choices, pricing, customer demand and operations relate to business performance.

**Tools:** Excel · Power Query · Power BI

> **Status:** This is an evolving analysis project. The repository contains the source workbooks and a Power BI project archive. Dashboard screenshots, validated findings and recommendations will be added after the report pages are finished and checked in Power BI Desktop.

## Business questions

1. How are CoolCars sales and market share changing over time?
2. Which vehicles, segments and regions contribute most to performance?
3. How do CoolCars products and prices compare with market alternatives?
4. Where might inventory, manufacturing, marketing or dealer activity need attention?

## Data and approach

| File | Role |
| --- | --- |
| [`CoolCars_Data.xlsx`](CoolCars_Data.xlsx) | Internal business data, including vehicle, pricing, product performance, manufacturing, inventory, marketing and dealer information. |
| [`Market_Data.xlsx`](Market_Data.xlsx) | Market context, including sales, products, consumer segments, microsegments and economic information. |
| [`CoolCars_Analytics.pbip`](CoolCars_Analytics.pbip) | Power BI project entry file. |
| [`CoolCars_Analytics.zip`](CoolCars_Analytics.zip) | Archived Power BI project components. Extract this file to work with the project. |

The analysis workflow covers checking the Excel sources, preparing tables in Power Query, building relationships and measures in Power BI, and comparing internal performance with market context. The data is used for a portfolio exercise; figures should be interpreted within that project context.

## Dashboard plan

| Page | Focus |
| --- | --- |
| Executive overview | High-level performance and changes by year or period. |
| Market and consumer | Demand, segments, regions and competitive position. |
| Operations and manufacturing | Production, stock and operational performance. |
| Product and pricing | Vehicle-level results, product mix and pricing. |
| Marketing and dealers | Commercial activity and dealer performance. |

These are the intended areas of analysis. **This table does not claim that all five pages are complete in the files currently uploaded to this repository.**

## View the report

GitHub cannot display an interactive Power BI report from a `.pbip` file. To open the project locally:

1. Download or clone this repository.
2. Extract `CoolCars_Analytics.zip` into the repository root. The extracted `CoolCars_Analytics.Report` and `CoolCars_Analytics.SemanticModel` folders should sit beside `CoolCars_Analytics.pbip`.
3. Open `CoolCars_Analytics.pbip` with Power BI Desktop on Windows.
4. In **Transform data → Data source settings**, update any original local file paths to the two Excel workbooks in this repository, then refresh.

## Next updates

- Add screenshots of each completed dashboard page so visitors can see the report without Power BI Desktop.
- Document the measures, filters and page interactions after checking them in the final report.
- Add supported findings and business recommendations, with the relevant time period and definitions.

---

**Author:** [Darcy Dinh](https://github.com/ddarcy017)
