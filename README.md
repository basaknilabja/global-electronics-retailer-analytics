# Global Electronics Retailer — Sales & Customer Analytics

**Portfolio project | Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook**

## Project Summary

An end-to-end retail analytics project that transforms multi-table sales, product, customer, and store data into business-focused insights. The workflow covers data-quality checks, cleaning, relational joins, feature engineering, sales and profitability analysis, customer purchasing behaviour, RFM segmentation, visualizations, and exportable analytical outputs.

## Business Objective

Use retail transaction data to understand commercial performance, identify product and category opportunities, evaluate customer value and repeat purchasing, and support evidence-based business decisions.

## Business Questions

- What are the overall revenue, profit, and profit margin?
- Which product categories and products contribute the most revenue?
- Which categories have the highest and lowest profit margins?
- How do sales and profitability change over time?
- How concentrated is revenue among high-value customers?
- Which RFM customer segments contribute the most revenue?
- What does repeat purchasing indicate about customer behaviour?
- What data-quality risks should be checked before acting on the findings?

## Tools and Technologies

- **Python**
- **Pandas** — data cleaning, transformation, joins, aggregation, and analysis
- **NumPy** — numerical calculations
- **Matplotlib and Seaborn** — data visualization
- **Jupyter Notebook** — analysis workflow and documentation

## Data Sources

The workflow uses five source tables:

- **Sales:** order-line transactions, order dates, delivery dates, quantities, and customer/product/store keys
- **Products:** product names, brands, categories, unit prices, and unit costs
- **Customers:** customer attributes and geographic information
- **Stores:** store locations, sizes, and opening dates
- **Exchange Rates:** currency conversion reference data

Place the five source CSV files in the locations configured in the notebook before running it.

## Analytical Workflow

1. Load and profile the source tables.
2. Inspect missing values, duplicates, data types, and key relationships.
3. Standardize text, date, numeric, and currency-formatted fields.
4. Validate primary, composite, and foreign-key relationships.
5. Join sales with product, customer, and store information.
6. Engineer revenue, cost, profit, margin, calendar, delivery, and customer-level features.
7. Analyse overall KPIs, monthly trends, product/category performance, customer concentration, repeat purchasing, and RFM segments.
8. Create visualizations and business-focused recommendations.
9. Export analytical datasets and a data-quality report.

## Key Findings

The figures below are taken from the notebook's Executive Summary.

### Overall Performance

| Metric | Result |
|---|---:|
| Revenue | **$55,755,479.59 USD** |
| Profit | **$32,662,688.38 USD** |
| Profit margin | **58.58%** |
| Orders | **26,326** |
| Customers | **11,887** |
| Units sold | **197,757** |
| Repeat customer rate | **61.18%** |

### Product and Category Performance

| Finding | Result |
|---|---|
| Top revenue category | **Computers** — $19,301,595.46 USD |
| Top revenue product | **WWI Desktop PC2.33 X2330 Black** — $505,450.00 USD |
| Highest-margin category | **Music, Movies and Audio Books** — 60.98% |
| Lowest-margin category | **Games and Toys** — 54.73% |

### Customer Analysis

| Finding | Result |
|---|---|
| Highest-value customer in the analysis | **Matthew Flemming** — $61,871.70 USD |
| Largest RFM segment by revenue | **Champions** — $19,742,710.38 USD |
| Repeat customer rate | **61.18%** |

## Business Interpretation and Recommendation

- **Revenue driver:** Computers is the leading category by revenue in the notebook's Executive Summary. The business could review its leading products and inventory availability to understand how to sustain this contribution.
- **Margin review opportunity:** Games and Toys has the lowest reported category margin at **54.73%**, compared with the overall margin of **58.58%**. Review pricing, supplier costs, discounts, and product mix in this category to identify potential improvement opportunities. The figures alone do not establish the cause of the margin difference.
- **Customer engagement:** The Champions RFM segment contributes **$19.74 million USD** in revenue. Consider testing retention or loyalty initiatives for this segment while monitoring repeat purchases and revenue over time.
- **Repeat purchasing:** The reported repeat customer rate is **61.18%**. Track this metric consistently and evaluate customer engagement initiatives against a clearly defined baseline.

These recommendations are hypotheses for further business investigation, not proof of causation. Validate definitions and assumptions before making operational or financial decisions.

## Financial Definitions and Assumptions

The notebook documents the following calculations:

- **Revenue** = Quantity × Unit Selling Price
- **Cost** = Quantity × Unit Cost
- **Profit** = Revenue − Cost
- **Profit margin** = Profit ÷ Revenue × 100

The source product price and cost fields are denominated in USD. Do not interpret these figures as currency-converted transaction totals unless exchange-rate conversion is explicitly applied in the notebook. The Executive Summary values above are reproduced from the notebook output supplied for this README.

RFM segmentation is a descriptive grouping of customer recency, frequency, and monetary value. It is not a predictive model. Observed relationships should not be treated as causal without additional analysis.

## Visualizations and Outputs

The notebook includes visual analysis of monthly revenue trends, category and product performance, RFM segments, delivery performance, and product revenue versus profit margin. It also prepares analytical outputs and a data-quality report for further review.

For reproducibility, run all notebook cells in order. Output files are exported to an `output` directory when the relevant cells complete successfully.

## How to Run the Project

1. Download or clone this repository.
2. Install Python and Jupyter Notebook, along with the libraries listed under Tools and Technologies.
3. Obtain the source CSV files and place them in the locations configured in the notebook.
4. Open `Global_Electronics_Retailer_Portfolio.ipynb`.
5. Run all cells in order.
6. Review the printed summaries, tables, charts, and generated output files.

**Note:** The source CSV files are not included in this repository unless explicitly added. Ensure you have permission to use and redistribute any dataset before publishing it.

## Project Files

- `Global_Electronics_Retailer_Portfolio.ipynb` — end-to-end analysis notebook
- `README.md` — project overview, key findings, and run instructions

## Resume-Ready Project Entry

**Global Electronics Retailer — Sales & Customer Analytics | Python, Pandas, NumPy, Matplotlib, Seaborn**

- Built an end-to-end retail analytics workflow covering data-quality checks, cleaning, key validation, and joins across sales, product, customer, and store tables.
- Engineered revenue, cost, profit, margin, calendar, delivery, and customer RFM features to evaluate commercial and operational performance.
- Analysed sales and category performance, customer value, repeat purchasing, and RFM segments to surface business opportunities.
- Summarized findings and recommendations in a documented notebook with visualizations and exportable analytical outputs.

## LinkedIn Project Description

Developed an end-to-end retail analytics project using Python, Pandas, NumPy, Matplotlib, and Seaborn. Combined sales, product, customer, and store data; implemented data-quality checks and feature engineering; and analysed revenue, profitability, category performance, customer value, repeat purchasing, and RFM segments. The project includes visualizations, verified executive-summary metrics, business recommendations, and reproducible analysis steps.
