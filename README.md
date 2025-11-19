# Alzheimer Forecasting Mexico

This project aims to forecast Alzheimer's cases in Mexico using various time series models, including Prophet. It analyzes historical data to provide insights and predictions that can aid in public health planning.

## Repository Structure

The project is organized as follows:

-   `notebooks/`: Contains Jupyter notebooks for data processing and modeling, ordered sequentially.
    -   `01_data_cleaning/`: Notebooks for data validation, outlier detection, and cleaning.
    -   `02_EDA/`: Exploratory Data Analysis.
    -   `03_models/`: Time series modeling (e.g., Prophet).
-   `data/`: Directory for data storage.
    -   `raw/`: Original, immutable data.
    -   `interim/`: Intermediate data transformed during processing.
    -   `processed/`: The final, canonical data sets for modeling.

## Installation

### Prerequisites

-   Python >= 3.12

### Setup

This project uses `uv` for dependency management, but can also be installed via `pip`.

#### Using `uv` (Recommended)

```bash
uv sync
```

#### Using `pip`

```bash
pip install -r requirements.txt
```

## Usage

To reproduce the analysis, run the notebooks in the following order:

1.  **Data Cleaning**: Navigate to `notebooks/01_data_cleaning/` and run the notebooks to prepare the data.
2.  **EDA**: Explore the data patterns in `notebooks/02_EDA/`.
3.  **Modeling**: Generate forecasts in `notebooks/03_models/`.

## License
...
