
Moving Average Trading Bot

This EA is intentionally limited to strategy tester use only for demonstration purposes.
This is a 3 moving average trading bot for MetaTrader 5 that uses top-down analysis across multiple timeframes. It also includes a built-in news filter to avoid trading during unpredictable or high-impact events.

I built this bot mainly for three symbols that I've found it works best with:

    GOLD (XAUUSD)

    BITCOIN (BTCUSD)

    NAS100 (Nasdaq 100 Index)

You can adjust the settings however you like depending on your trading style or the current market conditions, but I’ve found some settings that work especially well, which I’ll share below.
Strategy Breakdown

The bot uses:

    A 3 moving average setup to catch trend changes and confirm momentum

    Multi-timeframe (top-down) analysis to avoid false signals

    A news filter (optional) to skip trades around big economic releases

Suggested Settings

These are the settings I’ve had the most success with during testing.
GOLD:
![image](https://github.com/user-attachments/assets/cbb1beaf-f735-42bc-b0b7-1848b3d05b4f)


BITCOIN:
![image](https://github.com/user-attachments/assets/620561ea-cbf9-42cf-985b-fc2c5db42de9)


NAS100:
![image](https://github.com/user-attachments/assets/69913638-bb94-4f5a-91ac-df27ee5a5d03)


Feel free to tweak these — markets change, and different conditions call for different setups.
Risk Management

This bot includes a built-in feature to automatically calculate lot size based on how much of your balance you want to risk per trade. So even though I used leverage between 1:200 and 1:500, your actual risk stays consistent as long as that feature is enabled.

    Starting Balance: $500

    Leverage Used: 1:200 to 1:500

That said, having more than $500 in the account is better in general — especially since instruments like Gold and BTC can be expensive to trade.
Backtest Info

I ran all the backtests using 100% accurate tick data from 2025-02-05 to 2025-05-05, so the results should be extremely close to real-life performance.

⚠️ Just a heads-up:
The news filter doesn’t work during backtests (MetaTrader limitation), so it was disabled during these tests. I still recommend using it in live trading. 

Also, be careful trusting backtests using poor-quality data — I’ve seen bots that look amazing in long-term backtests but completely fall apart in real trading. Reliable tick data makes a huge difference.
Results

Here are the results for each symbol using the settings above:
GOLD Results:
    ![image](https://github.com/user-attachments/assets/43bea8d0-3bb8-460b-9f47-6e7eae6b6bf7)
BITCOIN Results:
    ![image](https://github.com/user-attachments/assets/c68ce220-5c94-44b6-a26a-9fbae5098cf7)
NAS100 Results:
    ![image](https://github.com/user-attachments/assets/bf329624-4d04-46cc-9c6c-f4f3779dd036)
