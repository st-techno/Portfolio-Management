
## Portfolio Management using Perps, Options, AI / ML Techniques

## Key Features:

Advanced Architecture Options:

LSTM Network: Dual-layer LSTM with dropout regularization

Transformer Model: Custom implementation with self-attention mechanisms

Hybrid Approach: Convolutional layers combined with attention mechanisms

Improved Feature Engineering:

60-day historical window for pattern recognition

MinMax scaling for normalized input values

Sequence-to-value prediction architecture

## Risk Management:

Dynamic position sizing based on volatility predictions

Automated portfolio rebalancing

Visual P&L distribution analysis

Model Validation:

20% validation split during training

Mean squared error optimization

Adaptive learning rates (Adam optimizer)

## Implementation Notes:

Data Handling:

Uses Binance's historical daily price data

Automatically fetches and preprocesses 2 years of historical data

Implements sliding window sequence generation

## Model Selection:

Defaults to Transformer architecture for its superior performance

Can switch to LSTM by changing model_type parameter

Includes convolutional layers for local feature extraction

## Performance Optimization:

Batch processing for efficient training

Dropout layers for regularization

## Learning rate scheduling in optimizer

This implementation reflects current best practices in financial time series prediction, combining insights from recent research papers with practical trading system considerations. 

The Transformer architecture particularly aligns with findings from comparative studies showing its advantage in capturing long-range dependencies in financial data.

