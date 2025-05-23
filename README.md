This system predicts rainfall for a specific date in India.

It is done by:
Processing and analyzing 33 years of high-resolution IMD gridded rainfall data (1992–2024), covering 12054 days and a spatial grid of 129×135 points (over 1.7 million data points per year).
Developed and automated a robust data pipeline to convert raw binary rainfall files into xarray DataArrays, handling missing values and enabling efficient multi-year analysis and visualization.
Engineered and trained a high-performance deep learning model (over 200 epochs) for daily rainfall prediction, achieving a mean absolute error (MAE) below 0.005 (normalized scale) and supporting predictions up to 77.1 mm/day.
Implemented a forecasting tool capable of generating spatial rainfall predictions for any date and location in India with visual outputs 
