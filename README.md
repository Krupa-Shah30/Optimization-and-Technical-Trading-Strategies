# Technical Trading Strategies and Portfolio Optimization

## Project Overview

This project implements and analyzes various technical trading strategies using financial market data. It focuses on optimizing a portfolio using Moving Average Crossover and Bollinger Bands strategies across multiple instruments. The goal is to create a diversified portfolio with superior risk-adjusted returns.

## Key Features

- Implementation of Moving Average Crossover (flat and short) strategies
- Bollinger Bands strategy implementation
- Sensitivity analysis for strategy parameter optimization
- Portfolio construction using Mean-Variance Optimization (MVO)
- Performance evaluation using Sharpe ratio
- In-sample and out-of-sample testing

## Data

The project uses historical price data for various financial instruments, including stocks, ETFs, currencies, and commodities. The data spans from December 31, 1999, to December 31, 2018, for the initial analysis, with an extended period for out-of-sample testing.

## Methodology

1. Data Preprocessing
   - Loading and cleaning financial time series data
   - Handling missing values and data normalization

2. Strategy Implementation
   - Moving Average Crossover (flat and short versions)
   - Bollinger Bands

3. Parameter Optimization
   - Sensitivity analysis for MA window sizes and Bollinger Bands parameters
   - Sharpe ratio optimization for each instrument and strategy

4. Portfolio Construction
   - Mean-Variance Optimization for weight allocation
   - Creation of a diversified portfolio across different asset classes

5. Performance Evaluation
   - Calculation of Sharpe ratios, annual returns, and maximum drawdowns
   - Comparison of strategy performance against benchmarks
   - In-sample and out-of-sample testing

## Key Findings

- Optimal parameters vary significantly across instruments
- The combined portfolio achieves higher risk-adjusted returns compared to individual strategies
- Out-of-sample testing validates the robustness of the optimized portfolio

## Technologies Used

- Python
- Pandas for data manipulation
- NumPy for numerical computations
- Matplotlib for data visualization

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/technical-trading-strategies.git
   ```

2. Install required packages:
   ```
   pip install pandas numpy matplotlib
   ```

3. Run the main script:
   ```
   python main.py
   ```

## Usage

The project is structured into several key components:

1. Data loading and preprocessing
2. Strategy implementation functions
3. Parameter optimization scripts
4. Portfolio construction and analysis

To run a full analysis, execute the main script, which will guide you through the entire process from data loading to final portfolio evaluation.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

- Financial data provided
- Inspired by quantitative finance research and modern portfolio theory
