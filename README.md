# Moving-Average-Trading-Bot

A 3 moving average trading bot with top down analysis operating on multiple time frames and includes a news filter to filter out unpredictable market conditions. There are 3 primary symbols I would recommend this metatrader5 EA for:
GOLD
BITCOIN
NAS100

You can use any settings you find most apropriate for your trading style and current situation and conditions, although I have found the best settings so far to be as folllows:

GOLD:
![image](https://github.com/user-attachments/assets/cbb1beaf-f735-42bc-b0b7-1848b3d05b4f)

BITCOIN:
![image](https://github.com/user-attachments/assets/620561ea-cbf9-42cf-985b-fc2c5db42de9)

NAS100:
![image](https://github.com/user-attachments/assets/69913638-bb94-4f5a-91ac-df27ee5a5d03)

Now, as for the results there are a few important points to not beforehand. I have started the account off with 500 dollars and a leverage of 200/500 as this is what I believe most people would be comfortable starting off with. Note that the leverage chosen does not imcrease your risk so long as you are using the built in feature I have added that actumatically calculates lot size based of the persentage of your balance you are prepared to risk per trade(so a ligher leverage would probibly be better). Although I have started the account with 500 dollars, more would be better , as Gold and Bitcoin are particularly expensive to buy. I am using 3 months ( 2025/02/05 - 2025/05/05) of past data with 100% accurate real tick historical data, meaning results are very accurate. It is possible to preform a longer backtest but results will not be accurate and it is very important to not that historical data that is not 100% accurate scews results vastly. I have created bots that return millions with unbelievable results based on a backtest but preform horribly in real life conditions, this is why it is important to use historical data that is 100% accurate based on real ticks. It is also not possible for the news filter to work during backtests so for these results the news filter is set to false.

As for the results:

Gold:
![image](https://github.com/user-attachments/assets/43bea8d0-3bb8-460b-9f47-6e7eae6b6bf7)

BITCOIN:
![image](https://github.com/user-attachments/assets/c68ce220-5c94-44b6-a26a-9fbae5098cf7)

NAS100:
![image](https://github.com/user-attachments/assets/bf329624-4d04-46cc-9c6c-f4f3779dd036)

Recommended Symbols

This bot has been tested and optimized for the following instruments:

    GOLD (XAUUSD)

    BITCOIN (BTCUSD)

    NAS100 (Nasdaq 100 index)

Strategy Overview

The bot uses a combination of:

    Three moving averages to identify short-, medium-, and long-term trends.

    Top-down analysis, evaluating multiple timeframes to improve signal quality.

    News filtering, which disables trading during major news events (only functional in live/forward testing).

Users can freely customize the strategy's parameters to suit their individual trading style, risk appetite, or market conditions.
Optimal Settings (Based on My Testing)

These are the most effective settings found during 3 months of rigorous backtesting (from 2025-02-05 to 2025-05-05) using 100% accurate real tick data:
GOLD:

  ![image](https://github.com/user-attachments/assets/43bea8d0-3bb8-460b-9f47-6e7eae6b6bf7)

BITCOIN:

  ![image](https://github.com/user-attachments/assets/c68ce220-5c94-44b6-a26a-9fbae5098cf7)

NAS100:

  ![image](https://github.com/user-attachments/assets/bf329624-4d04-46cc-9c6c-f4f3779dd036)  
