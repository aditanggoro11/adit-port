# LQ45 Stock Index Forecasting with GRU-ODE

This project forecasts five-minute LQ45 closing prices from irregular high-frequency observations. It implements a custom Gated Recurrent Unit with Ordinary Differential Equations (GRU-ODE), allowing the recurrent state to evolve according to the elapsed time between observations.

## Highlights

- Uses `Datetime` and `Close` data from an LQ45 CSV file.
- Derives the elapsed time between observations and supplies it to the model.
- Compares Euler and RK4 ODE solvers during a hyperparameter search.
- Uses chronological train/validation/test splits to reduce temporal leakage.
- Reports MAE, RMSE, MAPE, and R² for the held-out test set.

## Requirements

The script was developed in Google Colab. Install these Python packages before running it:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

## Data format

Provide a CSV with at least these columns:

```text
Datetime,Close
2024-01-02 09:00:00+00:00,9472.31
```

When run in Colab, the script prompts for the CSV upload. It sorts observations by `Datetime` before generating sequences.

## Run

1. Open `Stock Price Forecasting _ Irregular Time Series.py` in Google Colab or a Python environment.
2. Upload the LQ45 CSV when prompted.
3. Run the notebook/script cells in order.
4. Review the generated metrics, plots, and `gridsearch_full_results.csv` checkpoint.

## Included material

- `Stock Price Forecasting _ Irregular Time Series.py` — model implementation and evaluation workflow.
- `Skripsi Adit Rev1.pdf` — thesis documentation.
- `Presentasi Sidang Skripsi_Fattan(1).pptx` — thesis presentation.

## Notes

Forecasting results are research outputs, not financial advice. Do not use them as the sole basis for investment decisions.
