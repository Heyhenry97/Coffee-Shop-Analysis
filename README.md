# Coffee Shop Sales Analysis

## Overview

This repository contains a comprehensive analysis of sales data for three coffee shop locations: Astoria, Hell's Kitchen, and Lower Manhattan. The analysis employs various data science techniques to uncover insights into transaction patterns, revenue distribution, and product sales performance across these locations. 

The repository includes the following files:

- **`Analysis.ipynb`**: A Jupyter Notebook that presents the detailed analysis and insights derived from the sales data.
- **`Data.parquet`**: The raw dataset used for the analysis, containing transaction records and related information.

## Analysis Summary

### Revenue Distribution by Store

- **Astoria**: 
  - Orders are mostly small, with medium and large orders following. There are occasional instances where medium orders exceed small orders, but this pattern reverts by early afternoon.

- **Hell's Kitchen**: 
  - The order frequency pattern is similar to Astoria, with only minor differences between small and medium orders.

- **Lower Manhattan**: 
  - The pattern differs significantly from the other two locations, with large orders being the most frequent. This indicates effective upselling and higher demand throughout the day.

### Revenue Distribution Insights

- **Current Revenue Distribution**:
  - Each branch contributes approximately 33% of the total revenue, showing a balanced operation among the three locations.

- **Optimized Long-Term Revenue Distribution**:
  - **Lower Manhattan**: Given its high-traffic nature, it has the potential for higher sales. Recommended revenue allocation: 40-50%.
  - **Hell's Kitchen**: A busy area with strong dining and entertainment presence. Recommended revenue allocation: 25-30%.
  - **Astoria**: Though vibrant, it is less central compared to the other two locations. Recommended revenue allocation: 20-30%.



1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Heyhenry97/Coffee-Shop-Analysis.git
