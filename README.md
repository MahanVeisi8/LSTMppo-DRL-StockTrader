# LSTMppo-DRL-StockTrade

### **A Deep Reinforcement Learning Approach Combining Technical and Fundamental Analyses with a Large Language Model for Stock Trading**

The official GitHub repository for **LSTMppo-DRL-StockTrade**, implementing a Deep Reinforcement Learning (DRL) system for automated stock trading. This repository is associated with the article authored by **Mahan Veisi**, **Sadra Berangi**, **Mahdi Shahbazi Khojasteh**, and **Armin Salimi-Badr**.

[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2407.13372)

---

## Latest
- `10/07/2024`: The repository has been created. The code will be publicly available soon. Stay tuned for updates!

---

## Method
<details>
  <summary>
  <font size="+1">Abstract</font>
  </summary>
Stock trading strategies are essential for successful investment, yet developing a profitable approach is challenging due to the dynamic nature of the stock market. This repository introduces a **Deep Reinforcement Learning (DRL)** framework for automated stock trading that integrates technical and fundamental analyses using a large language model (FinBERT). The experimental results demonstrate superior performance in cumulative return, maximum earning rate, and Sharpe ratio, showing that the proposed model outperforms traditional methods.
</details>

---

## Installation

### Environment Setup

```bash
# Step 1: Create a virtual environment using conda or micromamba
micromamba create -n lstmppo-drl python=3.9 -y
or
conda create -n lstmppo-drl python=3.9 -y

# Step 2: Install required libraries
pip install -r requirements.txt
```

---

## Datasets
Datasets will be added soon. The stock price data is sourced from **Yahoo Finance**, and news data is collected from **Benzinga**. News sentiment analysis will be performed using **FinBERT**.

---

## Citation

If you find this repository helpful in your research or project, please cite the article and consider giving a ⭐ on the repository.

```
@article{Veisi2024DRL,
  title={A Deep Reinforcement Learning Approach Combining Technical and Fundamental Analyses with a Large Language Model for Stock Trading},
  author={Mahan Veisi, Sadra Berangi, Mahdi Shahbazi Khojasteh, Armin Salimi-Badr},
  journal={IEEE},
  year={2024}
}
```

---

## Acknowledgements
This code is inspired by works like **[Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3)** and **[FinBERT](https://huggingface.co/yiyanghkust/finbert-tone)** for sentiment analysis.
