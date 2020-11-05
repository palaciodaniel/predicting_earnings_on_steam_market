[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/palaciodaniel/predicting_earnings_on_steam_market/main?filepath=steam_market_valve_commissions.ipynb)

# Predicting Earnings on the Steam Market

I already mentioned the [Steam Market](https://steamcommunity.com/market/) on [another repository](https://github.com/palaciodaniel/steam_summer_sale_cards), however I mostly focused on the Trading Cards there. On this project I will focus on your earnings after subtracting Valve's commissions (to clarify, Valve is the company behind the immensely popular [Steam](https://store.steampowered.com/) platform) when you put any asset to sell on the Market, and for that I determined that Linear Regression was the most appropriate Machine Learning model for the case, as you will be able to see on the Jupyter Notebook file.

For those people who do not play games, here it is a bit of context: when you buy and play certain games on Steam, you will get different assets (Trading Cards, backgrounds, emoticons, etc.) that you can either showcase on your profile or sell on the Steam Market. If you choose the second option, once you successfully sell them you will get your account balance increased, which allows you to eventually be able to buy more games.

<p align="center"> 
<img src="https://images.unsplash.com/photo-1534951009808-766178b47a4f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80" width="500">
</p>

This becomes more feasible if your account is set to operate on Argentine pesos (ARS), given that several titles are cheaper to accommodate this currency, but also every time you put an asset on the Steam Market -and this apply for all currencies-, a part of your earnings will go to Valve and the developers of that game. In the case of US Dollars (USD), this deduction will only consist on a few cents, but in the case of the Argentine peso, it becomes incredibly sensitive to the price you select for the asset. Selling something for 3 ARS will imply a very different amount of commissions than 5 ARS, for example.

Even worse, given the Steam Market's layout, you will need to enter every price manually to see how much your actual earnings will be. Doing this repeteadly can become a bit tiresome, and in this sense, by simply -and quickly- inputting your price on the attached Jupyter Notebook file the task can become not only more manageable, but also it will surely allow for more experimentation. This was the purpose behind this project, and of course it also had the added benefit of being an excellent opportunity to showcase another practical application of Machine Learning, but this time using a regression model instead of a [classification](https://github.com/palaciodaniel/predicting_psychotherapy_success_with_ml) one.

## Instructions

You can experiment with your own inputs either by entering the [following link](https://mybinder.org/v2/gh/palaciodaniel/predicting_earnings_on_steam_market/main?filepath=steam_market_valve_commissions.ipynb) or by clicking the **Launch Binder** icon at the beginning of this *readme*. 

If by any chance this is your first time using a Jupyter Notebook, immediately after it loads go to the **Cell** tab and click **Run All**, then read the document while every cell is executed and when you reach the last one, just enter your desired number. To try another value, re-select this very last cell and press **Run** (just below the Cell tab). Repeat this process for every new value you want to try.

## Credits

Code written from scratch by **Daniel Palacio**.

Coins image by **Ibrahim Rifath** - *Unsplash.com* - (https://unsplash.com/photos/OApHds2yEGQ)
