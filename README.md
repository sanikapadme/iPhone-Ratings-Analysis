# iPhone-Ratings-Analysis
Uncovering iPhone market insights via EDA on Kaggle data. Visualizes consumer ratings, pricing strategies, and RAM's influence
# iPhone Sales Analysis

## Project Overview

This project focuses on analyzing iPhone sales data to uncover key insights into product performance, pricing strategies, and customer engagement. By examining various metrics such as sale price, discounts, ratings, and reviews, this analysis aims to provide a comprehensive understanding of the iPhone market dynamics.

## Dataset

The analysis uses a dataset named `apple_products.csv` which contains detailed information about various iPhone models, including:
- `Product Name`
- `Product URL`
- `Brand`
- `Sale Price`
- `Mrp` (Maximum Retail Price)
- `Discount Percentage`
- `Number Of Ratings`
- `Number Of Reviews`
- `Upc` (Universal Product Code)
- `Star Rating`
- `Ram`

## Features & Analysis

The Jupyter Notebook (`sales.ipynb`) includes the following key analytical steps and visualizations:

1.  **Data Loading and Inspection**:
    * Loads the `apple_products.csv` dataset into a Pandas DataFrame.
    * Checks for missing values to ensure data quality.
    * Provides descriptive statistics of the dataset to understand data distribution and central tendencies.

2.  **Top iPhone Models Analysis**:
    * Identifies and displays the top 10 iPhone models based on their `Star Rating` and `Number Of Ratings`.
    * Visualizes the number of ratings for the highest-rated iPhones using an interactive bar chart (Plotly Express).

3.  **Discount vs. Ratings Relationship**:
    * Explores the relationship between `Discount Percentage` and `Number Of Ratings` using an interactive scatter plot with a trendline (Plotly Express). This helps to understand if higher discounts correlate with more customer engagement.

## Technologies Used

* **Python**: Programming language for data analysis.
* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Plotly Express**: For creating interactive and aesthetically pleasing visualizations.
* **Plotly Graph Objects**: For fine-grained control over plot customization.
* **Jupyter Notebook**: For creating and sharing computational documents.

## How to Run the Project

To run this project locally, follow these steps:

1.  **Clone the repository** (if hosted on GitHub):
    ```bash
    git clone [https://github.com/YourUsername/iphone-sales-analysis.git](https://github.com/YourUsername/iphone-sales-analysis.git)
    cd iphone-sales-analysis
    ```
    (Replace `YourUsername` with your actual GitHub username)

2.  **Install necessary libraries**:
    ```bash
    pip install pandas numpy plotly jupyter
    ```

3.  **Ensure the dataset is present**:
    Make sure `apple_products.csv` is in the same directory as the `sales.ipynb` notebook.

4.  **Launch Jupyter Notebook or JupyterLab**:
    ```bash
    jupyter notebook
    # or
    jupyter lab
    ```

5.  **Open the notebook**:
    In your web browser, navigate to the `sales.ipynb` file and click on it to open. You can then run all cells to see the analysis and visualizations.

## Contributing

Feel free to fork this repository, open issues, and submit pull requests.

## Contact

Sanika Padme- padmesanika@gmail.com
