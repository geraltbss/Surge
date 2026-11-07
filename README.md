# Sales Data Engineering — Surge

A sales data engineering assignment exploring a retail sales dataset with Apache Spark. The notebook cleans and prepares the data, organizes it into a simple sales model, and uses charts to explore sales and profit patterns.

## What the notebook covers

- Loads transaction and sales-target data from CSV files
- Cleans values, converts data types, and standardizes column names
- Organizes customers, products, regions, shipping, orders, and sales into separate tables
- Combines sales with target data for analysis
- Explores sales and profit by category, sales over time, customer segments, and relationships between numeric fields
- Includes a star-schema diagram

## Data files

- `Dataset1.csv` — retail transaction records
- `Dataset2.csv` — sales targets by category, date, and customer segment

The repository also contains processed data and a notebook with the analysis.

## Tools used

- Python
- Apache Spark / PySpark
- Pandas
- Matplotlib
- Seaborn
- Plotly

## Run the notebook

The analysis is in `Surge.ipynb`. It was set up for a Google Colab-style environment and includes cells to install Java and Apache Spark 3.0.3 and initialize PySpark.

1. Open the notebook in Google Colab or another compatible Jupyter environment.
2. Make sure `Dataset1.csv` and `Dataset2.csv` are available in the notebook's working directory.
3. Run the notebook cells from top to bottom.

The setup cells use Java 8 and download Spark 3.0.3. Other Java or Spark versions may require updating those cells.

## Repository contents

| Path | Description |
|------|-------------|
| `Surge.ipynb` | Data preparation, dimensional modeling, and exploratory analysis |
| `Dataset1.csv` | Transaction-level sales data |
| `Dataset2.csv` | Sales target data |
| `processed.csv` | Processed sales data |
| `Star.drawio` | Editable schema diagram |
| `star_schema.drawio.png` | Exported schema diagram |

This repository records an assignment analysis; charts and observations should be interpreted in the context of the provided datasets.
