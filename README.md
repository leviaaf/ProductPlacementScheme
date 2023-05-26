# Product_Placement_Scheme_Visualization
This repository contains code for visualizing the product placement scheme in a store based on association results. The code reads data from a CSV file and generates a visualization based on a grid layout.

## Requirements
To run this code, you need the following dependencies:
- [`numpy`](https://numpy.org/)
- [`matplotlib.pyplot`](https://matplotlib.org/stable/api/pyplot_summary.html)

## Usage
1. Clone the repository to your local machine or [download](https://github.com/leviaaf/ProductPlacementScheme/blob/aefc24c2e104eab0cd6ea7f3d5f5b3ddd95ab49e/Product_Placement_Scheme.ipynb) the code files.
2. Make sure you have the required dependencies installed.
3. Place the CSV file containing the product association data in the same directory as the code files.
4. Open the code file in your preferred Python environment.
5. Run the code.

The code will prompt you to upload the CSV file. Select the appropriate file from your local machine.

The visualization will be displayed in a plot window, depicting the product placement scheme in the store. The grid represents the store layout, with each product labeled and positioned in its corresponding grid cell.

## Data Format
The CSV file should have the following format:

```
"Product";"Frequency";"Support"
"Product A, Product B";10;0.5
"Product C";5;0.3
...
```

- Each row represents a product name, frequency, and support separated by semicolons.
- The product name can contain multiple categories separated by commas (e.g., "Product A, Product B").
- The frequency is an integer representing the number of times the product appears.
- The support is a floating-point number representing the proportion of transactions that include the product.

## Output
The output of the code is a visualization of the product placement scheme in the store. The grid represents the store layout, and each product is labeled and placed in its corresponding grid cell.

The visualization helps in understanding the distribution of different products within the store and facilitates the optimization of product placement strategies.
