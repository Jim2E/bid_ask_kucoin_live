# Market Data: Bid/Ask Data from KuCoin using WebSocket

https://docs.kucoin.com/futures/#get-real-time-symbol-ticker-v2

### Overview

- Use KuCoin SDK docs to connect to Websocket: https://github.com/Kucoin/kucoin-python-sdk
- Import and use asyncio to work around having to create a client server.
- Subscribe this topic: "/contractMarket/level2:{symbol}", to get Level 2 order book data.The websocket system will send the incremental feed to you.
- Plot bar chart of latest 50 bid/asks. Also, see average of 50 bids, ask, and other useful metrics such as spread. 
- You can use this for live trading or other lower time-frame trading strategies. 

<p align="center">
  <img src = 'https://github.com/Jim2E/bid_ask_kucoin_live/blob/main/bid_ask_visual.png' width = "780">
</p>

Next Steps: Connect to KuCoin sandbox to test live pairs trading or other strategies and create report on performance. 

