# InvestorAI

InvestorAI is an intelligent stock analysis and prediction Agent system that combines real-time market data, financial news analysis, and machine learning-based price forecasting using LSTM neural networks.


## Features

| Feature               | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Real-time Data**     | Fetch current prices/volume for any ticker                                  |
| **News Analysis**      | Latest financial news with sentiment scoring                               |
| **Price Prediction**   | 30-day forecasts using LSTM neural networks                                |
| **AI Assistant**       | Natural language interface powered by LangGraph and Groq                          |
| **Technical Indicators** | 15+ indicators including MACD, Bollinger Bands, RSI                        |
| **Conversational AI**  | Conversational memory for follow-up questions                                  |

---

## Technical Architecture
### Core Components
1. LangGraph Agent: Orchestrates the AI workflow with tool selection and execution
2. LSTM Neural Network: Deep learning model for time series prediction
3. Yahoo Finance Integration: Real-time data and news retrieval
4. Technical Analysis Engine: Advanced feature engineering pipeline

## Technical Specifications
### Data Processing Pipeline
1. Data Collection: Historical stock data from 2020-present
2. Feature Engineering: 15+ technical indicators calculated
3. Normalization: MinMaxScaler for consistent scaling
4. Sequence Creation: 30-day lookback windows
5. Train/Test Split: 80/20 split with time series integrity

### Machine Learning Pipeline
The LSTM model incorporates sophisticated technical indicators:

| Indicators               | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Volatility Measures**     | Daily variation, 7-day standard deviation, ATR                                  |
| **Moving Averages**      | 7-day SMA, 14-day EMA                              |
| **Momentum Indicators**   | MACD, Stochastic Oscillator                                |
| **Trend Analysis**       | ADX, DMI                          |
| **Price Relationships** | High-Close, Low-Open ratios                        |
| **Performance Metrics**  | Cumulative returns, price changes                                  |



### Model Training Process

1. Data Preparation: Load and preprocess historical data
2. Feature Engineering: Calculate technical indicators
3. Sequence Generation: Create 30-day input sequences
4. Model Training: Train LSTM with validation
5. Evaluation: Calculate performance metrics
6. Prediction: Generate 30-day future forecasts

## API Keys Required
1. LangSmith API Key
2. Groq API Key
