# Customer Segmentation Analysis 📊

This project performs customer segmentation analysis using customer data to identify distinct groups of customers based on their purchasing behavior and demographics. The insights gained from this analysis can help businesses tailor marketing strategies and improve customer relationships.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Results and Insights](#results-and-insights)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Project Overview

This repository contains a data analysis project focused on understanding customer behavior through segmentation. The process involves:
1.  **Data Collection:** Gathering raw customer data.
2.  **Data Exploration and Cleaning:** Preprocessing the data, handling missing values, and transforming features to prepare it for analysis.
3.  **Customer Segmentation:** Applying clustering algorithms (likely K-Means or similar, based on typical segmentation projects) to group customers into distinct segments.
4.  **Analysis of Segments:** Characterizing each customer segment based on their attributes.

The primary goal is to provide actionable insights for targeted marketing campaigns and personalized customer experiences.

---

## Dataset

The analysis uses the `ifood_df (1).csv` dataset. This dataset contains various customer attributes, including:
-   **Income:** Customer's household income.
-   **Kidhome:** Number of small children in the household.
-   **Teenhome:** Number of teenagers in the household.
-   **Recency:** Number of days since the last purchase.
-   **MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds:** Amount spent on various product categories.
-   **NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumWebVisitsMonth:** Number of purchases made through different channels.
-   **AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5:** Whether the customer accepted the offer in the last 5 campaigns.
-   **Response:** 1 if customer accepted the offer in the last campaign, 0 otherwise.
-   **Age:** Customer's age.
-   **Customer_Days:** Number of days since the customer joined.
-   **Marital Status (Divorced, Married, Single, Together, Widow):** One-hot encoded marital status.
-   **Education (2n Cycle, Basic, Graduation, Master, PhD):** One-hot encoded education level.
-   **MntTotal:** Total amount spent on all products.
-   **MntRegularProds:** Amount spent on regular products.
-   **AcceptedCmpOverall:** Total number of campaigns accepted.

---

## Features

The key features utilized in this analysis include:
-   **Demographic features:** Income, Kidhome, Teenhome, Age, Marital Status, Education.
-   **Purchase behavior features:** Amounts spent on various product categories, number of purchases through different channels, and campaign acceptance rates.
These features are used to build a comprehensive view of each customer for effective segmentation.

---

## Installation

To run this project locally, you'll need Python and several libraries.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/customer-segmentation.git](https://github.com/your-username/customer-segmentation.git)
    cd customer-segmentation
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install the required libraries:**
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn scipy
    ```

---

## Usage

To execute the customer segmentation analysis:

1.  **Ensure you have the dataset:** Place the `ifood_df (1).csv` file in the root directory of the project.
2.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook "2.Customer Segmentation Analysis.ipynb"
    ```
    This will open the Jupyter interface in your browser. You can then run all cells in the notebook to reproduce the analysis.

---

## File Structure

├── ifood_df (1).csv
└── 2.Customer Segmentation Analysis.ipynb
└── README.md

-   `ifood_df (1).csv`: The raw dataset used for customer segmentation.
-   `2.Customer Segmentation Analysis.ipynb`: Jupyter Notebook containing the data exploration, cleaning, and customer segmentation analysis.
-   `README.md`: This file, providing an overview and instructions for the project.

---

## Results and Insights

The `2.Customer Segmentation Analysis.ipynb` notebook provides detailed insights into the customer segments identified. This includes:
-   Visualizations of data distributions.
-   Correlation analysis between features.
-   Detailed characteristics of each customer segment (e.g., average income, spending habits, family size, education levels).
-   Recommendations based on the segmentation for marketing strategies and business decisions.

---

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Contact

For any questions or inquiries, please contact [Manchikanti Gayathri/gayathri.manchikanti14@gmail.com].
