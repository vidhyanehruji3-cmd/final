1. Data Generation

You must generate OR select a multivariate time series dataset that contains:

At least two different seasonal patterns

Multiple input features

Clear documentation of how the dataset was created or sourced

Example: Use NumPy or statsmodels to create data with daily + weekly seasonality.

2. Build a Transformer Forecasting Model

Implement a clean, production-ready Python class that includes:

Custom Transformer encoder/decoder OR seq-to-seq architecture

Scaled dot-product self-attention

Appropriate positional encoding

Full training and prediction functions

3. Build & Train a Baseline Model

Train a baseline model such as:

LSTM

SARIMA

Tune hyperparameters for both Transformer and baseline models.

4. Comparative Analysis

Compare both models using:

At least 3 evaluation metrics (e.g., MAE, RMSE, MAPE)

Visualizations of predictions vs. actual values

Discussion of computational efficiency and training behavior

5. Attention Interpretation

Analyze attention weights from the Transformer to understand:

Which time steps the model focuses on

How it learns seasonality, trends, or feature dependencies

Insights about long-range vs short-range temporal relationships

🔹 Expected Deliverables Summary
1. Complete Executable Python Code

Your submission must include:

All imports

Data generation code

Model classes

Training loops

Prediction & evaluation logic
Everything must be runnable as a full script.

2. Comparative Analysis Report

A written analysis containing:

Evaluation metrics (Transformer vs LSTM/SARIMA)

Hyperparameter choices and justification

Computation time / efficiency

Visual comparison plots

3. Attention Interpretation Report

A textual explanation of:

What the attention maps show

Which historical steps the model considers important

How patterns align with true seasonality

Why the Transformer performed better or differently from the baseline
