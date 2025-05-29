# What

This is an attempt to compare the performance of different investment tools in Denmark, specifically focusing on:
* funds (aka Udloddende investeringsforeninger - investments funds, those pay dividents);
* ETFs (Exchange Traded Funds);
* ASK (Aktiesparekonto - stock savings account, a special tax-advantaged account for stocks).

There is a comparison to the article with the similar topic: [How to Optimize Your Investments for SKAT](https://fesasdelli.medium.com/how-to-optimize-your-investments-for-skat-7ea0841900c9)

Current results are as following:

* ASK has to be used first. However, it is limited by the value.
* In the short-term, a fund performs better than an ETF for usual investment account (not specially taxed as aktiesparekonto (aka ASK)) especially with a low starting base. The main reason for that is that ETFs hit stock top tax after some time only.
* In the long-term, a fund performs better than an ETF for usual investment account (not specially taxed as aktiesparekonto (aka ASK)) especially with a higher (more realistic) base. The main reason is that we pay taxes on realization and all the years the delayed taxes start to grow significantly.

# Install

```
virtualenv venv
# later:
pip install -r requirements.txt
jupyter lab
# open the link from the output
# open compare.ipynb jupyter notebook
```

Once virtual environment created you need to re-use it:

```
source venv/bin/activate
pip install -r requirements.txt
jupyter lab
# open the link from the output
# open compare.ipynb jupyter notebook
```
