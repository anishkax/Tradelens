## Overview
This project focuses on the development of a comprehensive stock forecasting model that leverages a news factor analyzing framework for enhanced interpretability. By analyzing historical stock data for 10 companies spanning the last five years, the model provides accurate forecasts, visual plots, and component breakdowns, enabling predictions for horizons ranging from 1 to 4 years.

### **Tradelens**
The Tradelens platform is an innovative financial technology solution designed to provide users with real-time stock analytics, AI-powered market predictions, and customizable alerts. The platform features a user-friendly interface, dark mode support, and seamless navigation through various financial insights. The homepage offers a well-structured layout with a modern aesthetic, ensuring ease of access to crucial market data. Additionally, the integration of advanced algorithms enhances predictive capabilities, allowing users to make informed investment decisions with confidence.

Security and user experience are at the core of Tradelens' functionality. The login system incorporates a secure authentication mechanism, ensuring data protection for users. The design of the login interface is streamlined, providing an intuitive and engaging experience. Furthermore, the inclusion of password recovery and account registration options enhances accessibility. The UI is crafted to maintain high responsiveness, ensuring usability across various devices, including desktops and mobile platforms.

The Tradelens platform also includes a dedicated news section that aggregates relevant financial news, keeping users updated on market trends. By offering real-time updates and critical insights, the platform empowers investors with the necessary information to make strategic decisions. The stock analytics page further enhances user experience by displaying key financial metrics, historical performance, and AI-driven predictions, giving traders an edge in their investment strategies.

## Features
- **Live Market Data**: Fetches real-time and historical stock data using Alpha Vantage.
- **Technical Indicators**: Includes Moving Averages, RSI, MACD, and Bollinger Bands.
- **Stock Forecasting**: Uses Facebook Prophet for time-series forecasting.
- **Interactive Visualizations**: Charts powered by Plotly for seamless data exploration.
- **User-Friendly Interface**: Simple and intuitive UI for ease of use.
- **News Sentiment Analysis**: Integrates financial news to improve prediction accuracy.
- **AI-Powered Predictions**: Uses XGBoost and deep learning models for enhanced forecasting.

## Tech Stack's Used
### **Frontend Technologies**
- **Streamlit** – Front-end framework for interactive web apps.
- **HTML, CSS, JavaScript** – Standard web technologies for UI design.
- **Chart.js & Plotly** – Generates dynamic and interactive visualizations.

### **Backend & Machine Learning**
- **Alpha Vantage** – Fetches financial market data.
- **Prophet** – Machine learning model for forecasting.
- **XGBoost** – Gradient boosting algorithm for stock prediction.
- **Pandas & NumPy** – Data handling and numerical computations.
- **NLP for Sentiment Analysis** – Uses Natural Language Processing to analyze financial news impact.
- **Deep Learning Models**: LSTM, N-BEATS, and Transformers for advanced market forecasting.

## Installation Guide
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- pip package manager

### Installation Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/anishkax/Tradelens.git
   cd Tradelens
   ```
2. Install dependencies manually:
   ```sh
   pip install streamlit alpha_vantage prophet plotly pandas numpy xgboost nltk scikit-learn flask
   ```
3. Verify Streamlit installation:
   ```sh
   streamlit --version
   ```

## Running the App
Start the application by running:
```sh
streamlit run app.py
```

## Future Enhancements
- **Integration with Additional APIs**: Support for Polygon.io and Yahoo Finance.
- **Advanced Deep Learning Models**: Implement Transformers and Multi-Head Attention.
- **Automated Trading System**: Develop a bot for executing trades based on predictions.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.
