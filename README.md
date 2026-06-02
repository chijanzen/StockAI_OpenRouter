StockAI_OpenRouter
A sophisticated financial analysis suite integrating multi-model AI (via OpenRouter) with technical stock market indicators.
Overview
StockAI_OpenRouter provides a data-driven approach to stock market analysis. It combines quantitative technical indicators (RSI, MACD, Weinstein’s 4-stage theory) with AI-generated insights to help developers and investors make informed decisions.
Key Technical Indicators
RSI (Relative Strength Index): For identifying overbought/oversold conditions.
MACD: For trend identification and momentum analysis.
Weinstein’s 4-stage Theory: Framework for long-term trend analysis.
Installation
Clone the repository:
   git clone [https://github.com/chijanzen/StockAI_OpenRouter.git](https://github.com/chijanzen/StockAI_OpenRouter.git)

Set up your Python environment:
   pip install -r requirements.txt

Set your API keys in the environment variables:
   export OPENROUTER_API_KEY='your_key_here'

Usage
Run Analysis: Execute the main script to fetch latest market data and generate AI insights:
   python main.py --symbol <STOCK_TICKER>
Customization: Adjust config.json to switch between different AI models supported by OpenRouter or to tweak technical indicator parameters.
