# LSTMppo-DRL-StockTrade

This repository is associated with the research article titled **"A Deep Reinforcement Learning Approach Combining Technical and Fundamental Analyses with a Large Language Model for Stock Trading."** The repository will host code and resources implementing a stock trading system that leverages Deep Reinforcement Learning (DRL) techniques, combining **Long Short-Term Memory (LSTM)** networks with **Proximal Policy Optimization (PPO)** to model the complexities of stock market trading. Additionally, the model incorporates market data and financial news embeddings from **FinBERT** to create a rich state representation for the agent.

**Note**: The code and datasets are currently being prepared and will be uploaded soon. Stay tuned for updates!

## Key Highlights

- **Deep Reinforcement Learning (DRL) Framework**: Combines technical indicators and fundamental news analysis.
- **Hybrid LSTM-PPO Architecture**: Aimed at capturing intricate temporal patterns in stock market data.
- **Sentiment Analysis Integration**: Utilizes FinBERT to analyze financial news, enhancing decision-making processes.
- **Drawdown Penalty Mechanism**: Incorporated in the reward function to improve portfolio stability.
  
## Article Abstract

Stock trading strategies are essential for successful investment, yet developing a profitable approach is challenging due to the complex and dynamic nature of the stock market. This project introduces a **Deep Reinforcement Learning (DRL)** framework for automated stock trading that integrates technical and fundamental analyses with a large language model. The model incorporates financial news headlines, processed using **FinBERT**, to create a comprehensive state representation. The experimental results demonstrate superior performance in cumulative return, maximum earning rate, and Sharpe ratio, indicating that the proposed model outperforms existing methods in terms of both resilience and profitability.

## Planned Features

1. **Data Collection and Preprocessing**:
   - Stock market data from **Yahoo Finance** and financial news data from **Benzinga**.
   - News embeddings generated using **FinBERT**.

2. **Trading Agent**:
   - The agent is built on the **LSTM-PPO** architecture.
   - Action space consists of continuous buy/sell signals for each stock in the portfolio.
   - Reward function includes a custom **drawdown penalty** for portfolio stability.

3. **Model Training and Evaluation**:
   - Backtesting on U.S. stocks and performance metrics such as **Cumulative Return (CR)**, **Max Earning Rate (MER)**, and **Sharpe Ratio (SR)**.
   - Comparisons with baseline models such as **A2C**, **PPO**, and other ensemble methods.

## Installation

To run the code (when uploaded), the following dependencies will be required:

```bash
pip install stable-baselines3[extra]
pip install transformers
pip install talib-binary
```

Additional instructions for setting up the environment will be provided after the code is uploaded.

## License

This repository is licensed under the **MIT License**.

## Citation

If you use this repository or reference the associated article in your work, please cite the paper as follows:

```
@article{Veisi2024DRL,
  title={A Deep Reinforcement Learning Approach Combining Technical and Fundamental Analyses with a Large Language Model for Stock Trading},
  author={Mahan Veisi, Sadra Berangi, Mahdi Shahbazi Khojasteh, Armin Salimi-Badr},
  journal={IEEE},
  year={2024}
}
```

## Future Work

- **Incorporation of Social Media Sentiment**: Expand the state space with real-time sentiment analysis from social platforms.
- **Dynamic Risk Management**: Further refine the drawdown penalty to optimize risk-adjusted returns across various market conditions.

