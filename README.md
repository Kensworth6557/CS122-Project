**Wallstreet Brief**

Authors: Kenny, Jason Y.

Description: Our project grabs all the news in the financial world and concises it into a 5-10 brief read to give the user useful information when deciding what stocks to buy. It will utilize free APIs to retrieve articles, stock prices, company information, etc. It will serve the user data through our React UI that's connected to our Flask backend that will facilitate our API calls and serve data to the UI for our users to see. Each briefing explains the biggest takeaways in the financial world for a current day, why it matters, and whether information thats being gathered could indicate a share being 'bullish', 'bearish', or neutral. Users would also be able to create watchlists for certain stocks, track market sentiment, and view personalized updates through an interactive dashboard.


**Project Outline:**
- Interface plan: Our project will be a web application utilizing React for UI and Flask to serve data to the UI. 
- Data Collection and Storage Plan: In order to gather financial data/news for the current day, we're going to use a mixture of web scraping and financial/stock related APIs for our Flask backend to use and serve data with.
- Data Analysis and Visualization Plan: Given the data retrieved from the APIs, we will collect the most recent news for the day and give a summary of the biggest takeaways in the financial world in a paragraph. In addition the summary, we will also provide an individual ticker rating based on the fundamental metrics such as Valuation Ratios, Profitability Margins, Revenue Growth, and Risk. After a query for a stock, we will display the current price and metrics, our own score recommending to buy, sell, or hold, and related news to the stock.
