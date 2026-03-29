<div align="center">

# :trophy: Kaggle Competitions

### Competition solutions, approaches, and lessons learned from Kaggle challenges

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/)

</div>

---

## Overview

A portfolio of Kaggle competition entries showcasing problem-solving approaches, feature engineering strategies, model ensembling techniques, and post-competition analysis. Each entry includes the full pipeline from EDA through final submission with detailed documentation of what worked, what didn't, and key takeaways.

## Competitions

| # | Competition | Task | Approach | Best Score | Medal |
|---|-------------|------|----------|------------|-------|
| 1 | **Titanic: Machine Learning from Disaster** | Binary Classification | Feature engineering, ensemble of GBMs | -- | :construction: Planned |
| 2 | **House Prices: Advanced Regression** | Regression | Stacking, target encoding, feature selection | -- | :construction: Planned |
| 3 | **Spaceship Titanic** | Binary Classification | CatBoost, missing value imputation | -- | :construction: Planned |
| 4 | **Store Sales - Time Series Forecasting** | Time Series | Prophet, LightGBM, hierarchical forecasting | -- | :construction: Planned |
| 5 | **Natural Language Processing with Disaster Tweets** | NLP Classification | Fine-tuned BERT, TF-IDF + LGBM | -- | :construction: Planned |
| 6 | **Digit Recognizer (MNIST)** | Image Classification | CNN, data augmentation, ensemble | -- | :construction: Planned |
| 7 | **Tabular Playground Series** | Various | AutoML, feature engineering, gradient boosting | -- | :construction: Planned |
| 8 | **Feedback Prize - Evaluating Student Writing** | NLP / Token Classification | DeBERTa, multi-task learning | -- | :construction: Planned |

## Approach Playbook

Each competition follows a structured approach:

1. **EDA & Understanding** -- Thorough exploration of data distributions, missing values, and target characteristics
2. **Baseline Model** -- Quick baseline with minimal feature engineering to establish a benchmark
3. **Feature Engineering** -- Domain-driven and automated feature creation
4. **Model Selection** -- Compare multiple algorithms (GBMs, neural networks, linear models)
5. **Hyperparameter Tuning** -- Optuna-based Bayesian optimization
6. **Ensembling** -- Stacking, blending, and weighted averaging of diverse models
7. **Post-Mortem** -- Analysis of top solutions and lessons learned

## Tech Stack

| Category | Tools |
|----------|-------|
| **Languages** | Python |
| **Gradient Boosting** | XGBoost, LightGBM, CatBoost |
| **Deep Learning** | PyTorch, TensorFlow, HuggingFace Transformers |
| **AutoML** | Optuna, Auto-sklearn |
| **Data Processing** | pandas, NumPy, Polars |
| **Feature Engineering** | Featuretools, category_encoders |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Experiment Tracking** | Weights & Biases, MLflow |

## Project Structure

```
Kaggle_Competitions/
|-- titanic/                    # Titanic survival prediction
|-- house_prices/               # House prices regression
|-- spaceship_titanic/          # Spaceship Titanic classification
|-- store_sales/                # Store sales forecasting
|-- disaster_tweets/            # NLP disaster tweet classification
|-- digit_recognizer/           # MNIST digit classification
|-- tabular_playground/         # Tabular Playground Series entries
|-- feedback_prize/             # Student writing evaluation
|-- utils/                      # Shared competition utilities
|-- privacy.md                  # Privacy policy
`-- README.md
```

## Getting Started

```bash
# Clone the repository
git clone https://github.com/DatariusAI/Kaggle_Competitions.git
cd Kaggle_Competitions

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Set up Kaggle API
pip install kaggle
# Place kaggle.json in ~/.kaggle/
kaggle competitions download -c titanic
```

## Roadmap

- [ ] Titanic competition with top 10% solution
- [ ] House Prices with advanced feature engineering
- [ ] Time series forecasting competition entry
- [ ] NLP competition with transformer fine-tuning
- [ ] Computer vision competition entry
- [ ] Write detailed post-mortems for each competition
- [ ] Create reusable competition utilities library

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Part of the [DatariusAI](https://github.com/DatariusAI) portfolio**

</div>
