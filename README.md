# Zomato Data Analysis

## Overview

This project involves the analysis of a Zomato dataset to extract meaningful insights about the food and restaurant industry. The analysis includes exploring various aspects of the dataset such as restaurant locations, cuisines, ratings, and pricing.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Dataset

The dataset used for this analysis is sourced from Zomato and contains information about various restaurants including their names, locations, cuisines, ratings, and more.

- **Source**: [Kaggle - Zomato Dataset](https://www.kaggle.com/shrutimehta/zomato-restaurants-data)
- **Attributes**:
  - `Restaurant ID`
  - `Restaurant Name`
  - `Country Code`
  - `City`
  - `Address`
  - `Locality`
  - `Locality Verbose`
  - `Longitude`
  - `Latitude`
  - `Cuisines`
  - `Average Cost for two`
  - `Currency`
  - `Has Table booking`
  - `Has Online delivery`
  - `Is delivering now`
  - `Switch to order menu`
  - `Price range`
  - `Aggregate rating`
  - `Rating color`
  - `Rating text`
  - `Votes`

## Installation

To run this project, you will need to install the required libraries. Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the dependencies.

```bash
pip install pandas numpy matplotlib seaborn jupyter python-dotenv
```

## Usage 

1. Clone the Respository: 

```bash
git clone https://github.com/ReDxDaGer/Zomato-Data-Analysis.git

cd Zomato-Data-Analysis
```

2. Prepare your environment: 

- Create a `.env` file in the root directory with your API keys or other environment variables if needed.

3. Run the Jupyter notebook:

```bash
jupyter notebook
```
- Open `Data-analysis.ipynb` and run the cells to perform the analysis.

## Analysis

The analysis is divide into several parts: 

1. Data Cleaning: 

 - Handling missing values
 - Standardizing and normalizing data

2. Exploratory Data Analysis (EDA):

 - Descriptive statistics
 - Visualizations (e.g., distribution of ratings, most popular cuisines, price range distribution).

3. Geographical Analysis:
 
 - Mapping restaurant locations
 - Analyzing regional preferences

4. Rating Analysis: 
 
 - Distribution of ratings
 - Factors affecting ratings

5. Cuisines Analysis:

 - Popular cuisines
 - Price range for different cuisines


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

1. Fork the repository. 

2. Create your feature branch (`git checkout -b feature/your-feature`)

3. Commit your changes (`git commit -m 'Add some feature'`)

4. Push to the branch (`git push origin feature/your-feature`)

5. Open a pull request