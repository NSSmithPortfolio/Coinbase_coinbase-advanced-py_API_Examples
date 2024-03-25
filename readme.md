
Basic examples of using the official python coinbase API.  I found it annoying to look up syntax every time I needed the 
code so created this repository for easy copy pasting.

Steps to use:
1) Clone respository
2) Create a Trading Key here: https://docs.cloud.coinbase.com/advanced-trade-api/docs/auth#cloud-api-keys.  Note, coinbase 
allows you to create API keys in 2 locations.  This one has to be here for the code to work
3) Fill in the API trading key information on lines 4 and 5 of main.py 
4) Run this within your IDE: pip3 install coinbase-advanced-py
5) Run code.  You'll need to have enough USD/USDC currency for buys and enough of the cryptocurrency for sells, otherwise
will error out without helpful messages from coinbase.

EACH CLIENT ORDER NUMBER MUST BE UNIQUE.  Orders will fail without helpful messages from coinbase if you do not.  If using this at scale, I would recommend adding in a random integer generator for your client order numbers.

