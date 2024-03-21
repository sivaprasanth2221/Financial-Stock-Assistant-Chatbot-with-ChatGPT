# Stock Analysis Chatbot Assistant

## Features

- Interactive chatbot interface for stock analysis queries.
- Utilizes OpenAI's GPT-3.5 model for natural language processing.
- Integrates with Yahoo Finance through yfinance for fetching stock data.
- Provides functions for stock price analysis, moving averages, RSI, MACD, and plotting stock prices.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/sivaprasanth2221/stock-analysis-chatbot.git
   ```

2. Install the required Python packages:
   ```bash
   pip install openai pandas matplotlib streamlit yfinance
   ```

3. Set up OpenAI API key:
   - Create an OpenAI account and obtain your API key.
   - Save your API key in a file named `API_KEY`.

4. Run the Streamlit app:
   ```bash
   streamlit run main.py
   ```

5. Use the web interface to interact with the chatbot assistant:
   - Enter your stock analysis queries in the input field.
   - Receive responses and analysis results from the assistant.

## Note

- Ensure you have an active internet connection as the app fetches data from Yahoo Finance.
- This chatbot assistant is for educational and demonstration purposes and should not be used for real financial decisions without proper verification.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

You can create a `LICENSE` file with the MIT License text and include any additional information or acknowledgments in the README.md file. This README provides an overview of the project, installation instructions, usage guidelines, and notes for users.
