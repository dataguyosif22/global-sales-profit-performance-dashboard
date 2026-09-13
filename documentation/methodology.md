# Methodology

## 1. Business question

Which segments (city, product category, sub-category) drive profit rather than just sales, and how has profit trended over the reporting period?

## 2. Data source

Not independently verifiable. The dashboard is published as a view-only Power BI report; the underlying dataset, its size, and its origin (real transactional data vs. a public/sample dataset) are not exposed through the public link.

## 3. Data preparation

Not accessible from the public report. Any Power Query transformations applied before the model stage cannot be reviewed.

## 4. Data modelling

Not accessible. The report appears to model sales at the transaction level with dimensions for city, product category, sub-category, and date (for the monthly trend), but the actual table/relationship structure cannot be confirmed without access to the .pbix file.

## 5. KPI definitions

- **Total sales**: sum of sales value across all recorded transactions.
- **Total profit**: sum of profit value across all recorded transactions.
- **Profit margin**: total profit ÷ total sales, expressed as a percentage.
- **City-level sales & margin**: sales and margin recalculated per city.
- **Category / sub-category profit**: profit summed at each level of the product hierarchy.
- **Monthly profit trend**: profit summed and plotted by month.

## 6. Analysis

Analysis proceeds by comparing profit (not just sales) across cities and product levels, and separately tracking how total profit moves month to month, to distinguish genuinely profitable segments from high-revenue but low-margin ones.

## 7. Dashboard design

The published report presents summary KPI cards (total sales, total profit, margin) alongside city, category, and sub-category breakdowns and a monthly trend view.

## 8. Validation

No independent validation was possible; figures in this repository are taken directly from the published dashboard as viewed.

## 9. Limitations

- Data source, size, and time range beyond "January–May" are not confirmed.
- The .pbix file and its DAX/Power Query logic are not available for review.
- Findings are based on a single review of the published report, not a refreshed or monitored data feed.
