# E-Commerce Sales Analysis Project

## Project Overview
This project analyzes Brazilian E-commerce data to identify sales patterns, customer behavior, and product performance using Python, SQL, and various data visualization libraries.

## Dataset
The analysis uses the Brazilian E-commerce Public Dataset by Olist, available on Kaggle. This dataset contains information about 100,000+ orders from 2016 to 2018 made at multiple marketplaces in Brazil.

### Dataset Files Used:
- `olist_orders_dataset.csv`: Order information (status, purchase timestamp, etc.)
- `olist_order_items_dataset.csv`: Items purchased in each order
- `olist_products_dataset.csv`: Product information
- `olist_customers_dataset.csv`: Customer information and location
- `product_category_name_translation.csv`: English translation of product categories

Dataset Source: [Brazilian E-commerce Public Dataset by Olist on Kaggle](https://www.kaggle.com/datasets/olist/brazilian-ecommerce)

## Analysis Features
1. **Sales Performance Analysis**
   - Monthly sales trends
   - Year-over-year comparison
   - Total revenue analysis

2. **Regional Analysis**
   - Sales distribution by state
   - Customer geographic analysis
   - Regional performance metrics

3. **Seasonal Trends**
   - Monthly sales patterns
   - Seasonal performance heatmap
   - Peak sales period identification

4. **Product Performance**
   - Top-performing product categories
   - Sales and profit correlation
   - Product category distribution

## Technical Stack
- **Python Libraries:**
  - Pandas: Data manipulation and analysis
  - NumPy: Numerical computations
  - Matplotlib & Seaborn: Static visualizations
  - Plotly: Interactive visualizations
  - SQLAlchemy: Database operations

- **Database:**
  - PostgreSQL: Data storage and SQL queries

## Project Structure
```
DATA ANALYST PROJECT/
│
├── data/
│   └── archive/             # Contains all dataset CSV files
│
├── notebooks/
│   └── ecommerce_analysis.ipynb  # Main analysis notebook
│
├── database_setup.sql       # Database schema and setup
└── README.md               # Project documentation
```

## Key Insights
1. Sales distribution across Brazilian states
2. Seasonal sales patterns and peak periods
3. Most popular product categories
4. Profit-sales correlation analysis

## Getting Started
1. Install required Python packages:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly sqlalchemy psycopg2-binary
   ```

2. Set up PostgreSQL database:
   - Create database named 'ecommerce_db'
   - Run database_setup.sql to create tables

3. Run the Jupyter notebook:
   - Open ecommerce_analysis.ipynb
   - Update PostgreSQL connection string with your credentials
   - Run all cells in order

## Visualizations
The project includes:
- Interactive dashboards using Plotly
- Sales trend visualizations
- Regional distribution maps
- Product performance charts
- Seasonal heatmaps

## Future Enhancements
- Customer segmentation analysis
- Predictive sales forecasting
- Advanced product recommendations
- Real-time dashboard updates

## Credits
- Dataset provided by Olist Store
- Analysis and visualization by [Your Name]
- Part of Data Analysis Portfolio Projects
