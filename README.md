# Applying Deep Reinforcement Learning to Systematic Equities

## Overview
This project explores the application of Deep Reinforcement Learning (DRL) to develop systematic equity trading strategies. By leveraging the Asynchronous Advantage Actor-Critic (A3C) algorithm combined with advanced neural network architectures (CNN and BiLSTM), this research aims to optimize decision-making for equities trading under dynamic market conditions. The framework incorporates both quantitative market indicators and qualitative sentiment data to improve profitability and manage risk effectively.

## Features
- **Data Integration**: Combines historical market data, technical indicators, macroeconomic variables, and sentiment scores derived from financial news.
- **Model Architecture**:
  - Actor-Critic framework based on the A3C algorithm.
  - CNN layers for local pattern extraction and BiLSTM layers for long-term dependencies.
- **Baseline Comparisons**: Evaluates performance against other DRL algorithms, including DQN, A2C, and PPO.
- **Backtesting**: Demonstrates the trading strategy on major stock indices (S&P 500, NASDAQ, DJIA).

## Project Structure
- `main.ipynb`: Contains the primary implementation, including training, testing, and evaluation.
- `data/`: Directory containing processed data inputs, including pricing, indicators, and sentiment scores.
- `results/`: Stores performance metrics and visualizations.
- `Project Report.pdf`: Detailed project report documenting methodology, results, and analysis.

## Key Results
- **Performance Metrics**:
  - Achieved higher cumulative returns and Sharpe ratios compared to baseline DRL algorithms.
  - Reduced maximum drawdown, improving risk management.
- **Sentiment-Aware Agent**:
  - Incorporating sentiment data enhanced profitability across all tested indices.
  - Outperformed traditional DRL models in terms of cumulative return and risk-adjusted performance.

## Future Work
- Integrate advanced feature extraction techniques such as attention mechanisms or transformers.
- Develop multi-agent reinforcement learning frameworks for collaborative trading strategies.
- Explore hybrid discrete-continuous action spaces for finer-grained decision-making.
- Experiment with other DRL algorithms such as Soft Actor-Critic (SAC) and Twin Delayed Deep Deterministic Policy Gradient (TD3).
- Explore ensemble agents that combine SAC, TD3, and the current sentiment-aware A3C-CNN-BiLSTM agent to leverage their complementary strengths for improved performance.
