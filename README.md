# A/B Testing Analysis

This repository contains a Jupyter Notebook that demonstrates A/B testing analysis using statistical simulations. The goal is to evaluate the performance of different strategies by analyzing their daily and cumulative rewards.

## Files

- `A_B_testing.ipynb`: The main notebook that contains all the code and analysis.

## Features

1. **Simulation Data**:
   - The notebook includes data for three strategies (`Strategy_1`, `Strategy_2`, and `Strategy_3`).
   - Each strategy is represented by a matrix where rows represent individual simulations and columns represent daily rewards.

2. **Statistical Calculations**:
   - Calculates daily mean and standard deviation for each strategy.
   - Computes cumulative rewards over time for each strategy.
   - Includes confidence intervals (2.5% and 97.5%) for the cumulative rewards.

3. **Visualizations (Optional)**:
   - The notebook can include plots to visualize the cumulative rewards and their confidence intervals for each strategy over time.

4. **Comparison of Strategies**:
   - Helps identify the strategy with the most consistent performance or highest rewards.

5. **Bayesian Thompson Sampling Method**:
   - The notebook optionally implements Bayesian Thompson Sampling, a probabilistic method for optimizing decisions.
   - Thompson Sampling is used to balance exploration and exploitation by sampling from the posterior distribution of each strategy's performance.
   - It is particularly effective in dynamic environments where uncertainty exists about the true performance of strategies.

## Requirements

To run the notebook, you need the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `jupyter`

Install them using pip:

```bash
pip install numpy pandas matplotlib jupyter
```

## How to Use

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Open the notebook:

   ```bash
   jupyter notebook A_B_testing.ipynb
   ```

3. Run the cells to execute the analysis. The results will include:
   - Summary statistics (daily mean, standard deviation).
   - Cumulative reward trends with confidence intervals.

4. Modify the data or parameters to test your own strategies or scenarios.

## Results

The notebook provides detailed statistics and visualizations to compare strategies. It calculates:

- **Daily Performance**:
  - Average rewards per day across all simulations.
  - Variability in daily performance (standard deviation).

- **Cumulative Performance**:
  - Overall growth of rewards over time.
  - Confidence intervals to account for variability.

- **Bayesian Insights**:
  - Insights from the Bayesian Thompson Sampling approach to evaluate and select the optimal strategy dynamically.


## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributions

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

---

Feel free to reach out if you have questions or feedback!

