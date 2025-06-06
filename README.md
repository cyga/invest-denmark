# What

This is an attempt to compare the performance of different investment tools in Denmark, specifically focusing on:
* funds (aka Udloddende investeringsforeninger - investments funds, those pay dividents);
* ETFs (Exchange Traded Funds);
* ASK (Aktiesparekonto - stock savings account, a special tax-advantaged account for stocks).

There is a comparison to the article with the similar topic: [How to Optimize Your Investments for SKAT](https://fesasdelli.medium.com/how-to-optimize-your-investments-for-skat-7ea0841900c9)

Current results are as following:

* ASK has to be used first. However, it is limited by the value.
* In the short-term, an ETF performs better than a fund for usual investment account (not specially taxed as aktiesparekonto (aka ASK)) especially with a low starting base. The main reason for that is that ETFs hit stock top tax after some time only.
* In the long-term, a fund performs better than an ETF for usual investment account (not specially taxed as aktiesparekonto (aka ASK)) especially with a higher (more realistic) base. The main reason is that we pay taxes on realization and all the years the delayed taxes start to grow significantly.

You can find my calculations and graphs in the [compare.ipynb](./compare.ipynb) Jupyter notebook.

My overall view of the investment plan for long-term investments in Denmark as an expat:

1. Buy ETFs for ratepension scheme annuarly for 65,500 DKK. It's tax-deductible and has special tax treatment.
2. Buy ETFs for børneopsparing (child savings account) and/or child pension account. They have special tax treatments and low annual limits.
3. Buy ETFs for aktiesparekonto (ASK) up to its limit (166,200 DKK). It has a special tax treatment (17% annuarly).
4. Buy passive index funds which pay dividents (and re-invest them, of course) for the rest of the money.

In case of leaving Denmark all these accounts can be left until the period you can use your money. Anyways, it's long-term investments and they still would work left as is.

# Install

You should have `python` and `virtualenv` tools already installed. Then you can create python's virtual environment to install dependencies and run server for Jupyter notebooks:

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
