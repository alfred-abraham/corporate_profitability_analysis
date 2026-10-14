# Corporate Profitability Analysis and Projection

## Overview

An analysis of historical NYSE company financial data that compares profitability and builds three-year profit scenarios.

## Objective

Identify historically profitable companies, examine profit growth, and compare projected upside and downside under different growth assumptions.

## Data

The project uses a Kaggle corporate financial dataset containing company identifiers and historical financial figures for publicly listed NYSE companies. The source CSV is not included in this repository.

## Approach

1. Explore profit distributions and rank companies by historical average profitability.
2. Calculate historical profit growth rates.
3. Project three years of profits using maximum, mean, and minimum historical growth for optimistic, average, and pessimistic scenarios.
4. Compare scenario outcomes across companies.

The complete calculations and outputs are in [the project notebook](notebooks/corporate_profitability_analysis.ipynb).

## Results

- Verizon (VZ), Bank of America (BAC), and AT&T (T) showed strong upside under optimistic and average assumptions.
- Verizon had the highest potential returns in the optimistic scenario.
- Wells Fargo (WFC) showed relatively lower downside in the modeled scenarios.
- The companies with the highest modeled upside were not always those with the lowest modeled downside.

These are findings from historical scenario analysis, rather than forecasts of current investment returns.

## Tools

Python, pandas, NumPy, and Jupyter Notebook.

## How to Run

1. Clone this repository and enter its directory.
2. Install dependencies and launch Jupyter:

   ```bash
   python -m pip install -r requirements.txt
   python -m pip install notebook
   python -m notebook
   ```

3. Obtain the corporate financial dataset used by the analysis.
4. Open [`notebooks/corporate_profitability_analysis.ipynb`](notebooks/corporate_profitability_analysis.ipynb). Change its `/content/Corporate Financial Dataset.csv` path to your CSV location.
5. Run the cells in order. For Google Colab, upload the CSV to `/content/`.

## Limitations and Next Steps

- Projections depend on historical growth and are sensitive to volatility and the available data period.
- The scenarios omit macroeconomic conditions, interest rates, industry shocks, and strategic changes.
- Future work could incorporate these drivers and test alternative scenario assumptions.
- The analysis is illustrative and should not be interpreted as financial advice.

## License

See [LICENSE](LICENSE) for repository licensing. Refer to the dataset source for its usage terms.
