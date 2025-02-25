# Acme Corporation Sales Optimization

## Overview
This repository contains the algorithms and datasets developed to help Acme Corporation predict and enhance their sales across various business segments using advanced data analytics. This tool aims to enable the company to better understand future sales trends and identify optimal strategies for increasing profits.

## Repository Structure
- `dataset.ipynb`: Notebook for generating the synthetic dataset.
- `algorithm.ipynb`: Notebook containing the algorithms for maximizing sales and margins.
- `Acme_Synthetic_Data_final.csv`: The synthetic dataset created for testing the algorithms.
- `detailed_sales_maximization_report.csv`: Output file from the sales maximization algorithm.
- `detailed_margin_sales_optimization_report.csv`: Output file from the margin maximization algorithm.

## Organizational Structure
Acme Corporation is organized into a hierarchical model with multiple levels:
1. **Portfolio**: Top-level division (e.g., Hair/Body, CC/Fragrances).
2. **Geography**: Regional markets (e.g., North America, Europe).
3. **Category**: Type of products (e.g., Hair, Body, Fragrance).
4. **Brand**: Specific brands (e.g., Brand A, Brand B).
5. **Segment**: Detailed product types (e.g., Shampoo, Perfume).

## Data Generation Process
The synthetic dataset includes 500 entries representing specific products. Each entry details financial metrics and business contexts:
- **Attributes**: Portfolio, Geography, Category, Brand, Segment, Sales, Margin, Min_Trend, Max_Trend, Min_Contribution, Max_Contribution.

### Constraints Applied
- **Trend Constraints**: Minimum and maximum growth trends ranging from -15% to 30%.
- **Contribution Constraints**: Minimum and maximum contributions from each product ranging from 5% to 50%.

## Algorithms Overview
1. **Maximize Sales**: Targets maximum possible sales under given constraints.
2. **Maximize Margin**: Focuses on achieving the highest possible profit margins.
3. **Hit A Sales Target While Maximizing Margin**: Aims to meet specific sales targets while optimizing margins.
4. **Hit A Margin Target While Maximizing Sales**: Seeks to achieve margin goals without compromising sales volume.

## Running the Notebooks
To run the notebooks and generate the reports:
1. Ensure you have Python and Jupyter installed.
2. Open `dataset.ipynb` to generate the dataset.
3. Run `algorithm.ipynb` to execute the sales and margin optimization algorithms.