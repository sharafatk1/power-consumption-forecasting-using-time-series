# Dataset

This folder contains the hourly electricity load datasets used for training and evaluating the forecasting models.

## Dataset Information

- **Source:** New York Independent System Operator (NYISO)
- **Dataset:** OASIS Day Ahead Market Zonal Load Data
- **Duration:** 2021–2026
- **Frequency:** Hourly
- **File Format:** CSV

## Files

| File | Description |
|------|-------------|
| 2021-2022_OASIS_Day_Ahead_Market_Zonal.csv | Hourly load data for 2021–2022 |
| 2022-2023_OASIS_Day_Ahead_Market_Zonal.csv | Hourly load data for 2022–2023 |
| 2023-2024_OASIS_Day_Ahead_Market_Zonal.csv | Hourly load data for 2023–2024 |
| 2024-2025_OASIS_Day_Ahead_Market_Zonal.csv | Hourly load data for 2024–2025 |
| 2025-2026_OASIS_Day_Ahead_Market_Zonal.csv | Hourly load data for 2025–2026 |

## Dataset Usage

The datasets are combined and preprocessed before training the forecasting models.

The preprocessing pipeline includes:

- Handling missing values
- Removing duplicate records
- Datetime conversion
- Chronological sorting
- Feature engineering
- Data normalization
- Train-test splitting

## Original Source

https://www.nyiso.com/load-data
