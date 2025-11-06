# Nigeria Population Forecasting with Prophet

This project uses time series forecasting to predict Nigeria's population from historical data up to the year 2050 using the Prophet library.

## Project Structure
- `Population.csv`: Historical population data for Nigeria.
- `population_forecast.ipynb`: Jupyter notebook containing all analysis, modeling, and visualization steps.
- `README.md`: Project overview and instructions.

## Workflow
1. **Data Loading**: Import population data from `Population.csv`.
2. **Preprocessing**: Convert year column to datetime and prepare data for Prophet.
3. **Modeling**: Fit a Prophet model to the data.
4. **Forecasting**: Predict future population values up to 2050.
5. **Visualization**: Plot historical and forecasted population, including uncertainty intervals.
6. **Results Table**: Display estimated population and confidence range for each year from 2025 to 2050.

## How to Run
1. Open `population_forecast.ipynb` in Jupyter Notebook or VS Code.
2. Run each cell sequentially to reproduce the analysis and results.
3. The final cells display a table of population estimates and ranges for 2025–2050.

## Requirements
- Python 3.7+
- pandas
- matplotlib
- seaborn
- prophet

Install dependencies with:
```bash
pip install pandas matplotlib seaborn prophet
```

## Output Interpretation
- **Forecast Chart**: Shows historical data, forecast, and uncertainty intervals.
- **Results Table**: For each year, provides the best estimate and a range (lower and upper bounds) for Nigeria's population.

## License
This project is for educational and research purposes.
