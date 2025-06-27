# myntra-fashion-analysis

Data-driven analysis of women’s fashion trends, pricing, and profitability on Myntra using Python.

## Project Structure

```
myntra-fashion-analysis/
├── README.md
├── requirements.txt
├── data/
│   └── myntra_sample.csv
└── workspace/
    └── main.ipynb
```

## Features & Analysis

This project provides a comprehensive analysis of Myntra's women's fashion data, including:

### 1. Data Exploration
- Preview of the dataset and available columns.

### 2. Category Performance
- Sales by main product category.
- Top-selling individual categories for women.
- Product counts for each category.

### 3. Pricing Insights
- Distribution of discounted prices for women’s products.
- Most common price ranges for each category.
- Average, minimum, and maximum discounted prices by category.

### 4. Brand Competition
- Number of brands in each top category.
- Top brands by product count in dresses and suits.
- Average discounted price per brand.
- Price distribution among brands.

### 5. Size Analysis
- Most common sizes for dresses and suits.
- Average discounted price by size for dresses and suits.

### 6. Discount Analysis
- Average discount percent by brand.
- Distribution of discount percentages.

### 7. Small vs Big Brands
- Price range and distribution for small brands (≤5 products) vs big brands in dresses.
- Pie charts and histograms for price range comparison.

### 8. Deep Dives
- Detailed analysis for top categories like sarees, dresses, and suits.
- Brand performance, price stats, and distribution visualizations.

### 9. Exports for Reporting
- Export of summary tables as CSV and Excel.
- Saving of key plots as images.

## Getting Started

1. **Clone the repository**
   ```sh
   git clone <repo-url>
   cd myntra-fashion-analysis
   ```

2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

3. **Run the analysis**
   Open `workspace/main.ipynb` in Jupyter or VS Code and run the cells.

## Data

- Place your Myntra data CSV in `data/myntra_sample.csv`.

## Outputs

- Summary tables and plots are saved in the `workspace/` directory.

## License

MIT License