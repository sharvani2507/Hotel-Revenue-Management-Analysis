# Hotel Revenue Management Analysis

A data-driven analysis project aimed at optimizing hotel revenue management through dynamic pricing, customer segmentation, cancellation prediction, and promotion effectiveness. This project focuses on utilizing machine learning techniques to maximize hotel profitability and enhance operational efficiency.

## Table of Contents  
- [Introduction](#introduction)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Build Instructions](#build-instructions)  
- [Directory Structure](#directory-structure)  
- [Project Results](#project-results)

## Introduction  
This project analyzes various aspects of hotel revenue management, including dynamic pricing, demand forecasting, and customer behavior analysis. By leveraging data analytics and machine learning models, it provides actionable insights that help hotels adjust pricing strategies, optimize promotions, and manage cancellations.

## Features  
- **Dynamic Pricing:** Implemented using XGBoost to forecast hotel room prices based on seasonality, occupancy rates, and lead time.
- **Customer Segmentation:** Clustered customers using KNN for targeted marketing and personalized experiences.
- **Cancellation Prediction:** Built a neural network to predict booking cancellations and help reduce revenue loss.
- **Promotion and Event Analysis:** Analyzed the effectiveness of promotions and events in driving bookings, and identified peak booking periods.

## Technologies Used  
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib 
- **Tools:** Jupyter Notebook, Git

## Build Instructions  
To run the analysis and models, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/sharvani2507/Hotel-Revenue-Management-Analysis
    ```
2. Navigate to the project directory:
    ```bash
    cd hotel-revenue-management
    ```
3. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter notebooks to execute the analysis:
    ```bash
    jupyter notebook
    ```

## Directory Structure  
```bash
hotel-revenue-management/
├── README.md
├── data/
│   ├── hotel.csv
│   └── hotel_bookings.csv
├── notebooks/
│   ├── Customer segmentation.ipynb
│   ├── Dynamic pricing.ipynb
│   ├── Cancellation prediction.ipynb
│   └── Events and Promotion period.ipynb
└── reports/
    └── Krack The Hack - Triad of Trends.pdf
```

## Project Results  
- **Customer Segmentation:** Identified key customer groups that enabled targeted marketing efforts, leading to increased bookings.
- **Cancellation Prediction:** The cancellation model predicted cancellations with an accuracy of 100%, reducing potential revenue loss.

---
