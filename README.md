# Credit Risk Analysis and Prediction

## Overview

This project focuses on Credit Risk Analysis and Prediction using customer transaction and demographic data. The dataset contains information on customer card payment history and demographic details, which are used to classify customers as either high risk or low risk for specific banking products. This project is ideal for budding data scientists and data analysts to experiment with machine learning and statistical modeling concepts.

## Dataset

The project utilizes two main datasets:

### 1. `payment_data.csv`
This dataset contains customer card payment history. The features are:

- **id**: Customer ID
- **OVD_t1**: Number of times overdue type 1
- **OVD_t2**: Number of times overdue type 2
- **OVD_t3**: Number of times overdue type 3
- **OVD_sum**: Total overdue days
- **pay_normal**: Number of times normal payment was made
- **prod_code**: Credit product code
- **prod_limit**: Credit limit of the product
- **update_date**: Account update date
- **new_balance**: Current balance of the product
- **highest_balance**: Highest balance in history
- **report_date**: Date of the recent payment

### 2. `customer_data.csv`
This dataset contains customer demographic data and category attributes, which have been encoded. The features include:

- **Category features**: `fea_1`, `fea_3`, `fea_5`, `fea_6`, `fea_7`, `fea_9`
- **Numerical features**: `fea_2`, `fea_4`, `fea_8`, `fea_10`, `fea_11`
- **label**:
  - `1`: High credit risk customer
  - `0`: Low credit risk customer

## Project Structure

The project is organized as follows:

- `data/`: Contains the datasets used for analysis and model training (`payment_data.csv` and `customer_data.csv`)
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, model development, feature engineering, model training, and evaluation
- `models/`: Saved models and evaluation results
- `README.md`: Project overview and documentation

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/credit-risk-analysis.git

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or inquiries, please contact **Argha Dey Sarkar** at **email2argha@gamil.com**.
