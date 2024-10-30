# Curently working on a Course project with my Team in developing an AI Assistant (Chatbot) in an existing App called "AutoProphet" which is a financing app where users can invest on stocks.
# Our Aim is to building a Chatbot which chats with the users providing with the real-time data related to Stock Prices.
# The model will be trained on the real-time data extracting through an API called "AlphaVantage" and "Yahoo Finance API" which consists of real-time Stock prices, news and historical data.



*More features will be added and deployed*

*This is my current output results of how my AI Assistant is working*

*Refer https://github.com/karthikkumarcholleti/AI-Assistant-ChatBot/blob/main/the_big_code%20(1).py to view the output*

*Refer https://github.com/karthikkumarcholleti/AI-Assistant/blob/main/fine_tuned_model.py to view the Fine tuned model*

*Run this model to view more resuts.*

**TRY TO DOWNLOAD THE FOLLOWING FINE TUNED MODELS BEFORE TESTING IT**

https://drive.google.com/drive/folders/10V9Lh2NQoiOoGB4s_qIXJnkkxNq5dugE?usp=sharing

https://drive.google.com/drive/folders/10lFL2WT3A6kS3Ii6fT00BMZH-rZNb5Vg?usp=sharing

https://drive.google.com/drive/folders/1hykYr6Z9nqAuY9_Zqk22fj3LYwATGZ9Q?usp=sharing


**Some of the output picctures are attached below, showing how my model is working betching the data through yfinance API and Alpha Vantage API**
*Run this model to view more resuts.*
![image](https://github.com/user-attachments/assets/e2ddc91f-5738-409b-90e7-03e3c4c676ac)
![image](https://github.com/user-attachments/assets/86d219ef-74f3-488b-ab93-9a80872a801b)
![image](https://github.com/user-attachments/assets/a8d5e540-1e8f-4cd6-99b9-0305a0d07c1f)
![image](https://github.com/user-attachments/assets/b4fc3010-1827-42a0-b3fd-a047af47bf5c)
![image](https://github.com/user-attachments/assets/ef62c6ec-caf8-4b9e-ad33-f22a868c9ca1)
![image](https://github.com/user-attachments/assets/a41a09cb-6695-44a5-82cf-450028c12543)



**Stock Market AI Assistant**
This project is an AI-powered assistant designed to handle a wide variety of stock-related queries. It can provide real-time stock price information, perform trend analysis, compare stock prices, and provide stock-related news sentiment. The assistant is built using BERT for intent detection, combined with FinGPT for real-time data fetching, and is integrated with APIs like yfinance to retrieve stock data.

**Features**

*1. Stock Price Inquiry*
The assistant can fetch the current, high, low, open, and close prices of stocks for specific timeframes (e.g., today, yesterday, last week, etc.).
Paraphrased or flexible queries like "How much did Tesla peak at today?" and "What’s the current value of Apple?" are supported.

*2. Stock Trend Analysis*
Users can ask for stock trends, such as "How has Microsoft been trending this month?" or "What was Tesla’s performance last week?"
The model detects trends for periods like this week, last week, and more complex natural expressions (e.g., "this year" or "past three months").

*3. Stock Comparison*
The assistant compares multiple stocks over specified periods. For example, "Compare the current price of Tesla and Apple" or "Show me the trend comparison between Google and Amazon last month."

*4. News Sentiment Analysis*
Retrieves and analyzes the sentiment of stock-related news articles. Users can ask, "What is the sentiment of Facebook news today?"

**Technical Details**

*Intent Classification:*
The project uses BERT, fine-tuned with custom stock market data (130 queries per intent), to classify the user's intent based on stock-related queries.
Intents include price inquiry, stock trend, stock comparison, and news sentiment.

**Real-Time Data Integration:**

*FinGPT:*
Used for real-time query handling and response generation for stock prices and trends.

*yfinance API:*
Fetches real-time and historical stock data, including various price types (open, close, high, low) and trend data over custom time periods (e.g., 1D, 1W, 1M, 1Y).
![image](https://github.com/user-attachments/assets/6c8f38e3-272d-4d9b-8d82-7e66bd176f24)

![image](https://github.com/user-attachments/assets/206fdc41-62e1-4feb-a01e-b6c1aaca6186)

![image](https://github.com/user-attachments/assets/2916c610-ddab-4cbc-a46f-1cf7892ea1e2)

![image](https://github.com/user-attachments/assets/6918eb31-0090-4acb-9cb5-b373532aa0be)
![image](https://github.com/user-attachments/assets/3a5b91a5-98d9-41e6-98b1-04d47d1b4f0e)
![image](https://github.com/user-attachments/assets/ca8cb7dd-c710-4214-8224-37909a902a1c)
![image](https://github.com/user-attachments/assets/a4e2efcb-8022-4968-a0b6-a01b1c5cc8e1)
![image](https://github.com/user-attachments/assets/dd014e1d-c5cb-4a36-9cfb-17b7a5f5c7cf)

![image](https://github.com/user-attachments/assets/dd67fa58-4a3d-4c5b-808b-2c3cfdf3fe9b)

![image](https://github.com/user-attachments/assets/5f945061-ab1c-4117-8497-d68a80b07053)
![image](https://github.com/user-attachments/assets/597c38f0-db7f-46d0-b7d8-dd2e21fb2adc)
![image](https://github.com/user-attachments/assets/07f0ed2b-d236-4a45-9fac-1a726575e308)
![image](https://github.com/user-attachments/assets/d92021d5-3933-4e01-ac24-e086cbb75f4a)
