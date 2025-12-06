# Forbes Global 2000 - Exploratory Data Analysis

## Overview

This project performs a comprehensive exploratory data analysis (EDA) of the **Forbes Global 2000** list, examining the world's largest public companies by revenue, profit, assets, and market value. The analysis uncovers financial trends, industry distributions, geographic patterns, and insights into global corporate leadership.

## Project Objectives

- Analyze financial metrics (revenue, profit, assets, market value) across the Global 2000
- Identify leading companies and industries in the global economy
- Explore geographic and regional distributions of corporate power
- Examine correlations between financial indicators
- Visualize trends and patterns in global corporate performance
- Generate actionable insights about the world's largest enterprises

## Dataset

The analysis utilizes the **Forbes Global 2000 dataset**, which includes:

- **Company Name**: Name of the corporation
- **Country/Region**: Geographic location headquarters
- **Industry**: Business sector classification
- **Revenue**: Annual revenue in billions USD
- **Profit**: Annual profit in billions USD
- **Assets**: Total assets in billions USD
- **Market Value**: Market capitalization in billions USD
- **Rank**: Global ranking position

## Key Analyses

### Financial Metrics Analysis
- Distribution and statistics of revenue, profit, assets, and market value
- Identification of top performers and outliers
- Correlation analysis between financial indicators
- Profitability ratios and efficiency metrics

### Industry Distribution
- Number of companies per industry sector
- Average financial metrics by industry
- Industry contribution to global corporate wealth
- Emerging vs. traditional sectors

### Geographic Trends
- Regional representation in the Global 2000
- Country-wise corporate concentration
- Regional financial performance comparison
- Geographic diversity and centralization patterns

### Data Visualizations
- Distribution histograms and density plots
- Box plots for outlier detection
- Scatter plots for correlation analysis
- Bar charts for industry and geographic comparisons
- Heatmaps for correlation matrices
- Pie charts for market share distributions

## Tech Stack

- **Python 3.8+**: Primary programming language
- **Pandas**: Data manipulation, cleaning, and aggregation
- **NumPy**: Numerical computations and array operations
- **Matplotlib**: Static visualization creation
- **Seaborn**: Statistical data visualization and aesthetic enhancements
- **Jupyter Notebook**: Interactive analysis and documentation

## Project Structure

```
forbes-global-2000-eda/
├── data/
│   └── forbes_global_2000.csv          # Source dataset
├── notebooks/
│   ├── 01_data_loading_cleaning.ipynb   # Data import and preprocessing
│   ├── 02_financial_analysis.ipynb      # Financial metrics analysis
│   ├── 03_industry_analysis.ipynb       # Industry distribution insights
│   └── 04_geographic_analysis.ipynb     # Regional and country trends
├── visualizations/
│   ├── financial_distributions.png
│   ├── industry_comparison.png
│   ├── geographic_distribution.png
│   ├── correlation_heatmap.png
│   └── top_companies.png
├── scripts/
│   └── eda_analysis.py                  # Standalone analysis script
├── README.md                            # Project documentation
└── requirements.txt                     # Python dependencies
```

## Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip or conda package manager

### Clone the Repository
```bash
git clone https://github.com/yourusername/forbes-global-2000-eda.git
cd forbes-global-2000-eda
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Requirements File
```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
```

## Usage

### Run Jupyter Notebooks
```bash
jupyter notebook notebooks/
```

Navigate to individual notebooks for step-by-step analysis with explanations and visualizations.

### Run Standalone Script
```bash
python scripts/eda_analysis.py
```

This generates a comprehensive report with all analyses and saves visualizations to the `visualizations/` folder.

## Key Findings

### Financial Insights
- Top companies demonstrate significant diversity in profitability despite similar revenue levels
- Correlation between assets and market value varies significantly by industry
- Outliers identified in profit-to-revenue ratios indicating high-efficiency operators

### Industry Highlights
- Banking and financial services dominate by count and total market value
- Technology sector shows highest average market value per company
- Energy and manufacturing remain significant by asset base despite market shifts

### Geographic Patterns
- United States, China, and Japan lead in company representation
- European companies show concentration in specific sectors
- Emerging markets increasing representation in technology and e-commerce sectors

## Visualization Highlights

The project includes various visual analyses:

- **Financial Distribution Plots**: Understanding spread and central tendencies of key metrics
- **Industry Comparison Charts**: Sector-wise performance and composition
- **Geographic Heatmaps**: Regional concentration and representation
- **Correlation Analysis**: Relationships between financial indicators
- **Top Performers**: Ranking and highlighting industry leaders

## Methodology

1. **Data Loading & Exploration**: Import dataset and initial quality assessment
2. **Data Cleaning**: Handle missing values, outliers, and data type conversions
3. **Descriptive Statistics**: Calculate summary statistics for all numeric fields
4. **Correlation Analysis**: Examine relationships between financial metrics
5. **Grouping & Aggregation**: Analyze patterns by industry and geography
6. **Visualization**: Create comprehensive visual representations
7. **Insights Generation**: Draw conclusions and identify trends

## Insights & Conclusions

This EDA reveals a highly concentrated global corporate landscape dominated by established financial institutions and large multinational corporations. Regional differences are pronounced, with North America and Asia-Pacific leading in representation and market value. The analysis highlights the resilience of traditional sectors while showcasing growing importance of technology and digital-forward companies.

## Future Enhancements

- Time-series analysis comparing year-over-year changes
- Machine learning clustering to identify company archetypes
- Predictive modeling for company performance
- Deep dive into emerging market trends
- Sectoral shift analysis and trend forecasting

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature suggestions.

## License

This project is licensed under the MIT License - see LICENSE file for details.

## Acknowledgments

- Data source: [Forbes Global 2000](https://www.forbes.com/global2000/)
- Analysis inspired by financial and corporate trends research
- Built with Python data science community tools and best practices


