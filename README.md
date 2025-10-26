# TimesFM-TRM: Combining Time Series Forecasting with Reasoning Models

This project explores the potential of combining state-of-the-art time series foundation models with reasoning models for financial forecasting. The core idea is to leverage the predictive power of models like TimesFM and enhance it with the reasoning capabilities of models like TRM to analyze vast amounts of financial asset time series data.

## Key Components

The project will focus on integrating two main research papers:

### 1. TimesFM: Time Series Foundation Model

*   **Paper:** [times_fm.pdf](./papers/times_fm.pdf)
*   **arXiv:** [https://arxiv.org/abs/2310.10688](https://arxiv.org/abs/2310.10688)

TimesFM is a powerful foundation model for time series forecasting. It is designed to handle a wide variety of time series data and has shown impressive results in many forecasting tasks.

### 2. TRM: Less is More for Long-Term Time Series Forecasting with Light-weight Temporal Representation Model

*   **Paper:** [less_is_more_trm.pdf](./papers/less_is_more_trm.pdf)
*   **arXiv:** [https://arxiv.org/abs/2510.04871](https://arxiv.org/abs/2510.04871)

TRM is a reasoning model that has shown promise in understanding and reasoning about complex data. This project will investigate how its reasoning capabilities can be applied to the outputs of TimesFM to generate more robust and explainable financial forecasts.

## Goal

The primary goal is to build a system that can:

1.  Use TimesFM to generate forecasts for a comprehensive set of financial assets.
2.  Use TRM to reason about these forecasts, identify patterns, and potentially improve accuracy.
3.  Provide a framework for backtesting and evaluating the combined model's performance on historical financial data.
