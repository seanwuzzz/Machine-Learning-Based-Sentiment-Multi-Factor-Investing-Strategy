# Machine-Learning-Based-Sentiment-Multi-Factor-Investing-Strategy

## Overview
- Market: Taiwan Equity Market (TSE, OTC)
- Models: SVM, KNN, XGBoost
- Signals: Financial factors, price-based factors, news sentiment
- Rebalancing: Multi-channel rebalancing
- Evaluation: IC, Sharpe ratio, CAGR, turnover

Financial news texts are encoded using BERT to generate semantic embeddings, which are subsequently processed by SVM and k-Nearest Neighbors models for sentiment classification.

The inferred sentiment factors are integrated with proprietary financial and market-based factors through an XGBoost-based factor combination framework.

The resulting composite signals are employed to construct a multi-factor trading strategy targeting Taiwan listed and OTC stocks.

### Disclaimer
This project is for educational and informational purposes only and does not constitute financial advice. All data used, including that from TEJ, Yahoo Finance, is publicly available and used in accordance with their respective terms of service.

The results and strategies demonstrated herein are based on historical data and a self-determined factors, and they do not guarantee future performance. Always perform your own due diligence and consult a licensed financial advisor before making investment decisions.

The creator of this project assumes no responsibility for any financial losses or damages resulting from the use or interpretation of the information provided.
