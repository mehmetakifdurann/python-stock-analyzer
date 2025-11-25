
🚀 Features
A python program to analyze the user input stocks. 
For the best user experience, you can change the following line for what you want : 
 " stocks=[i + ".IS" for i in user_stock] " --> Example : if you are going to check BTC, ETH, SOL you have to change ".IS" to "-USD" and enter your inputs as BTC SOL ETH..
This program gives you: 
  1. Statistical analysis : Calculates mean, min, max and standart derivation for given stocks.
  2. Interactive visualization : Generates dynamic bar chart using plotly.
  3. Automated Interpretion : Compares individual stock prices against the portfolio average and generates automated status tags (`HIGH`/`LOW`) and comments.

🛠️ Built with: ![Uploading showing the status and apps comment for user stocks.png…]()

1. Python 3.0
2. Pandas
3. Yfinance
4. Plotly Express

Prerequisites
Make sure you have Python installed. You can install the required libraries using pip:

```bash
pip install pandas yfinance plotly cufflinks
```
Example interpretion output: 

 GENERAL MEAN VALUE: 110.46 TL
=====================================================================================
 ASELS.IS   :   195.13 TL  |  Status: HIGH  |  Comment: INCREASES THE AVERAGE
 EREGL.IS   :    27.65 TL  |  Status: LOW   |  Comment: DECREASES THE AVERAGE
 ...
