# Sales Data Analysis using Power Query and Power BI

This repository contains a data analysis project focused on analyzing the sales data of a manufacturer company and its competitors from seven different countries. The project involves performing data transformations using Power Query or Power BI to create a data model that fulfills specific requirements and allows for effective analysis and visualization.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to transform and analyze sales data from the manufacturer company and its competitors. By leveraging Power Query or Power BI, we aim to create a comprehensive data model that adheres to star or snowflake schema principles and establishes one-to-many relationships between tables. The transformed data will facilitate in-depth analysis and visualization of sales trends and performance.

## Dataset

The dataset provided for this project consists of the following files:

- **Sales_fact**: Contains the sales data for the manufacturer company within the USSales folder.
- **InternationalSales folder**: Contains the sales data from six other countries.
- **Sales_dimensions**: Contains three sheets—Product, Geo, and Manufacturer—providing additional dimension data for analysis.

## Installation

To replicate or explore the project locally, follow these installation steps:

1. Clone this repository to your local machine using the following command:

```
git clone https://github.com/your-username/your-repository.git
```

2. Install Power Query or Power BI based on your preference and system requirements.

3. Ensure that the necessary datasets are available in the appropriate folder structure as mentioned in the project description.

## Usage

1. Open Power Query or Power BI, depending on your preferred tool.

2. Use the data transformation capabilities of Power Query or Power BI to perform the necessary steps for creating the final data model.

3. Create the five tables—Date, Geography, Manufacturer, Product, and Sales—according to the provided requirements in the project description.

4. Apply the star or snowflake schema principles to establish the appropriate one-to-many relationships between the tables.

5. Validate and optimize the data model to ensure completeness, accuracy, and efficiency.

6. Utilize the features of Power Query or Power BI to generate insightful visualizations and perform analysis on the sales data from different dimensions.

7. Experiment with various visualization techniques to present key sales trends, revenue insights, and performance metrics.

## Project Structure

The project structure is organized as follows:

```
├── data/
│   ├── USSales/
│   │   ├── Sales_fact.csv
│   │   ├── Sales_dimensions.xlsx
│   │
│   └── InternationalSales/
│       ├── Country1_sales.csv
│       ├── Country2_sales.csv
│       ├── ...
│       └── Country6_sales.csv
│
├── readme.md
├── .gitignore
└── PowerBI/
    ├── Sales Dashboard.pbit
```

- The `data` directory contains the sales data files, including the USSales folder and the InternationalSales folder.

- The `PowerBI` directory includes Power BI files for data transformation (`Data_Transformation.pbix`) and visualization (`Visualization.pbix`).

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements or would like to add new features, please feel free to submit a pull request.

## License

The project is licensed under the [MIT License](LICENSE).
