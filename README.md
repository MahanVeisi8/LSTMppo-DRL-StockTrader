# LSTMppo-DRL-StockTrade

### **A Deep Reinforcement Learning Approach Combining Technical and Fundamental Analyses with a Large Language Model for Stock Trading**

The official GitHub repository for **LSTMppo-DRL-StockTrade**, implementing a Deep Reinforcement Learning (DRL) system for automated stock trading. This repository is associated with the article authored by **[Mahan Veisi](https://github.com/MahanVeisi8)**, **[Sadra Berangi](https://github.com/sadraberangi)**, **[Mahdi Shahbazi Khojasteh](https://github.com/MehdiShahbazi)** and **Armin Salimi-Badr**.


---

## Latest
- `10/07/2024`: The repository has been created. The code will be publicly available soon. Stay tuned for updates!

---

## Method
<details>
  <summary>
  <font size="+1">Abstract</font>
  </summary>
Stock trading strategies are essential for successful investment, yet developing a profitable approach is challenging due to the dynamic nature of the stock market. This repository introduces a Deep Reinforcement Learning (DRL) framework for automated stock trading that integrates technical and fundamental analyses using a large language model (FinBERT). The experimental results demonstrate superior performance in cumulative return, maximum earning rate, and Sharpe ratio, showing that the proposed model outperforms traditional methods.
</details>

---

## Installation

### Environment Setup

```bash

To set up the environment for this project, follow these steps:

```bash
# Step 1: Create a virtual environment using micromamba or conda:
micromamba create -n lstmppo-drl python=3.9 -y
or
conda create -n lstmppo-drl python=3.9 -y

# Step 2: Activate the virtual environment:
micromamba activate lstmppo-drl
or
conda activate lstmppo-drl
```

# Step 3: Install the required libraries from the requirements file:
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
