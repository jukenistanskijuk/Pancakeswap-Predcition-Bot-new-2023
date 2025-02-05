  
# 🔮🚀 PancakeSwap-Prediction v5.0 

![PancakeSwap-Logo](/img/logo.jpg?raw=true)

The bot that uses signals from TradingView to predict the price of BNB for Up or Down in PancakeSwap.

## ⭐Please consider giving a **star**.

## Contact Us: Support@Assaempire.eu 

## 🐰⚡ Installation

Download and Install Node here:
https://nodejs.org/en/download/

Then run the following commands in terminal:

1. ``git clone https://github.com/EmpireAssatoken/Pancakeswap-Predcition-Bot-new-2023`` 
2. ``cd Pancakeswap-Predcition-Bot-new-2023``
3. ``npm i``

![enter image description here](/img/setup.jpg?raw=true)




## ⚙️ Setup

1. Open the **.env** file with any code/text editor and add your private key like so:
```
PRIVATE_KEY=YOUR_PRIVATE_KEY_HERE
```
3. Open the **bot.js** file and setup the following variables:
```
BET_AMOUNT: 5, // Amount of each bet (In USD)
DAILY_GOAL: 20, // Total profit you are aiming to earn (In USD)
```
4. Start the bot using `npm start` or `yarn start`
5. 🔮 Enjoy!

### 🔓 How to convert seed phrase to Private Key
A lot of wallets don't provide you the private key, but just the **seed phrase** ( 12 words ). So here you will learn how to convert that to a private key:
1. Enter [Here](https://youtu.be/eAXdLEZFbiw) and follow the instructions. Website used is [this one](https://iancoleman.io/bip39/).

![Winning rate](/img/rate.jpg?raw=true)


## 🤖📈 Strategy
- The bot take a series of recomendations given by Trading View and proccess them together with the tendency of the rest of people betting. After the algorithm have complete, it choose to bet **🟢UP** or **🔴DOWN**.
- After all my testings in aprox 300 rounds I was able to achieve a **~70% Win rate**. Of course it depends of a lot of variables, so I can't ensure that you will reproduce the same behavior. But I can tell that I make $20 - $70 daily with $3 Bets.
- Before every round the bot will check if you have enough balance in your wallet and if you have reached the daily goal.
- Also it will save the daily history in the **/history** directory.
- Be aware that after consecutive losses, statistically you have more chances to win in the next one.
- Inside **bot.js** in the ``THRESHOLD`` property of ``GLOBAL_CONFIG`` variable, you can configure the minimum certainty with which the bot will bet. For default it's set to 50, which means that from 50% certainty the bot will bet. You can raise it (50-100) to bet only when the bot is more sure about its prediction.
- Its recomendable to have x10 - x50 the amount of bet to have an average of rounds.


💰You can check the history of rounds and claim rewards here: https://pancakeswap.finance/prediction

## ✔️ To Do 

 - [x] USD Based bet 
 - [x] Show real time profit 
 - [x] Show real time win rate 
 - [x] Daily goal profit 
 - [x] Improved algorithm v1.1 🔥
 - [x] AI Driven bot 🔥
 - [x] Stop Loss
 - [ ] Simplify settings 
 - [ ] Auto collect winnings 


## 👁️ Disclaimers

**Please be aware of clones**

 👷**Use it at your own risk.** 
 If you are going to bet, please do it with money that you are willing to lose. And please try to bet with a low amount to gradually generate profit.
