## About Dataset
This file contains data about a superstore. The original dataset or worksheet originally comprises **`Orders`** and  **`Returns`** spreadsheets, for further details:

1. **`Orders`**: contains the data about orders made by customers for any product. This table also contains information about customers like name, address, etc. and information about orders like product name, order-id, product category, etc.
2. **`Returns`**: contains information about the returned product with their order id and additional information.

## Data Preprocessing: 
1. The dataset was obtained using the Kaggle API and a Python library called `shutil`.
2. Preprocessing steps, including cleaning and transformation, were performed on the dataset to prepare it for analysis.
3. To adhere to the BCNF (Boyce-Codd Normal Form) standard, the original relations were decomposed into smaller ones.
4. Relationships were established within the schema to optimize data flow and ensure logical connections between different data entities.
5. Calculated columns and measures were incorporated during the preprocessing stage to facilitate aggregation analysis and enhance the overall understanding of the dataset.

## Data Visualization:
- The visuals are categorized into 3 distinct sections:
  + Overview: This section contains the most comprehensive and high-level figures, providing an overview of sales performance over the 2-year period.
  + Segment: This section focuses on in-depth breakdowns for different locations and customer segments.
  + Product: This section provides key details, including a lookup table for supervising the performance of products partitioned by categories, customers, dates, revenue, etc.
- Filters and interactivity are carefully edited to ensure optimal visualizations, enhancing the user experience without overwhelming the viewer or misleading information.