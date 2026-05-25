# Earnings-Call Text and the Dynamics of Uncertainty and Trading

This repository contains the working paper:

**Earnings-Call Text and the Dynamics of Uncertainty and Trading**

The paper studies how qualitative information in earnings-call transcripts is absorbed into financial markets. Using sentence embeddings, PCA, ridge regression, LightGBM, and strict out-of-sample validation, it examines whether earnings-call text improves forecasts of abnormal returns, realised variance, and abnormal trading volume across post-call horizons.

## Paper summary

Earnings calls combine hard quantitative information, such as earnings surprises, with qualitative disclosure from management discussion and analyst Q&A. This project asks whether that qualitative information contains incremental predictive value beyond standard financial controls and hard earnings information.

The main findings are:

- Earnings-call text strongly improves forecasts of **realised variance** at short horizons, with the signal decaying after roughly two weeks.
- Text generates large and persistent improvements in **abnormal volume** forecasting, suggesting that qualitative disclosure shapes investor attention and trading activity.
- Text has only modest predictive value for **abnormal returns**, with small gains concentrated at medium horizons.
- Text-driven realised variance and abnormal volume are strongly co-moving, while the return signal is largely orthogonal to both.
- Text-driven uncertainty predicts subsequent abnormal trading activity, consistent with gradual information absorption and heterogeneous investor interpretation.

## Repository status

This repository currently contains the working paper draft.  
The empirical codebase is being prepared for release and will be added in a future update.

## Contents

TBC
