# Used Car Price Analysis

This repository contains a Jupyter notebook analyzing factors driving used car prices using a dataset of 426,880 listings. The project follows the CRISP-DM framework and achieves an R2 score of 0.82 with key drivers identified as 'year', 'odometer', and 'Toyota' manufacturer.

## Notebook
- [UsedCarPriceAnalysis.ipynb](https://github.com/Faranakysf/UsedCarDealership/blob/ef4951897eea16222b222bf75ade49d68a9f37bb/Car_Dealershp%20Case.ipynb)

## Files and Structure
- `UsedCarPriceAnalysis.ipynb`: Main analysis notebook with modeling and visualizations.
- `images/`: Directory containing generated plots (e.g., `PriceYearDistribution.png`, `PriceManufacturDistribution.png`).
- `data/vehicles.csv`: Reducted Data of used car listings. Note: The reducted data has been used because I was not able to upload the large data. The original vehicles.csv (28.45MB with 426,880 rows) is sampled to 10% (42,688 rows), reducing the size to ~2.84MB, well under 25MB which allowed size for upload. Features Preserved: All 18 columns from the original dataset are retained, ensuring compatibility with the analysis.

## Results
- **Model Performance**: R2: 0.82, RMSE: $5,123 (on a 10% sample).
- **Key Insights**: Newer cars (post-2015), low mileage (<85,548 miles), and brands like Toyota, Ford, and Chevrolet drive higher prices.

## Recommendations
- Stock newer cars (2015+).
- Target low-mileage vehicles.
- Promote top brands (Toyota, Ford, Chevrolet).
- Use the model for data-driven pricing.
