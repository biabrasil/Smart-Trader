# Smart-Trader
Smart Trader allows users to input a stock ticker (e.g., AAPL, TSLA, MSFT) and receive AI-powered insights about the stock’s outlook. The app fetches and displays a combination of technical indicators, analyst-style recommendations, recent news articles, social media buzz, and geopolitical factors that may influence the stock.

<img width="1900" height="929" alt="Screenshot 2025-08-19 234353" src="https://github.com/user-attachments/assets/51317643-904c-41dd-847c-e0cc06c57963" />

## When a user enters a ticker:

Technical Indicators such as RSI, volume, MACD, and volatility are displayed, alongside an overall sentiment score (bearish → neutral → bullish).

Recommendation & Confidence are summarized with a clear icon and rating, giving quick actionable insight.

Recent News articles are aggregated and displayed with sources, dates, and direct links for deeper reading.

Social Buzz shows trending discussions or sentiments from platforms like Twitter, Reddit, and Facebook.

Geopolitical & Market Analysis highlights broader external factors and risk scores that could impact the stock’s performance.

# Tech Stack
The app is built with React + Tailwind CSS for a modern, responsive UI, and leverages a custom hook (useStockIntel) to fetch stock intelligence data asynchronously. It emphasizes clarity, interactivity, and a holistic view of market sentiment to help users make informed decisions quickly.
