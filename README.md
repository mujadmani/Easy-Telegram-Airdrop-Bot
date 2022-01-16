# Easy Telegram Airdrop Bot

This bot has all you need, very simple to use and easy to deploy!


### Some of the great futures

- Ask user to follow twitter and join telegram groups, multiple groups and twitter links are supported.
- Check if a correct wallet address has been provided
- Very easy to use.
- Persistance, the chat will remain persistant even if you restart the bot.
- Blocks duplicate wallets & twitter usernames
- Referral support
- Start, stop, pause airdrop anytime.
- Captcha support


### More added features [Updated]

- Ask user to join Discord server, multiple links are supported.
- Gives errors when irrelevant commands are used
- Checks and verifies if user is in the group/channel before proceeding
- Validates and gives error messages for Twitter user link, Discord username, and Wallet address
- Gives error when duplicate Twitter usernames, Discord usernames or Wallet addresses are input
- /restart command to start over the process if user inputs incorrect details. Referrals aren't lost, they are still safe.
- 2 more object names for /list .json file, i.e. Total balance and Referral count of the user


### Admin Commands

- `/list` Returns the list of all participants in json format.
- `/stats` Returns number of participants, referrals, distribution amounts
- `/bot stop|pause|start` Manage airdrop status; stop, pause or start.


## Deploy and Host to Heroku

<p><a href="https://heroku.com/deploy?template=https://github.com/mujadmani/Easy-Telegram-Airdrop-Bot"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-red?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

The easiest way to deploy this bot is using Heroku. 
Don't forget to switch on the bot under "Resources" panel. See example below:<br>
<p align="center"><img align="center" src="./images/on.png" width="60%" height="60%"></p>


## Env Variables

- `COIN_SYMBOL` Is the coin symbol
    - Example: `BNB, ETH`
- `COIN_NAME` Is the coin name
    - Example: `Bitcoin, Ethereum`
- `AIRDROP_AMOUNT` How many tokens are you going to give
    - Example: `10000` *do not* include "," must be float number
- `AIRDROP_DATE` Date of reward distrubition
    - Example: `20 July 2021`
- `AIRDROP_NETWORK` In which network/chain are you going to give?
    - Example: `Binance Smart Chain`
- `BOT_TOKEN` The token you get from @BotFather (https://telegram.me/BotFather)
    - Example: `1313552295:AAFxDGKhlco-FoWw-uyxInotlKvalidNEz-Q`
- `COIN_PRICE` Current price of coin
    - Example: `$0.01`
- `REFERRAL_REWARD` Extra reward participants will get for each referral
    - Example: `1000`
- `WEBSITE_URL` Your website URL
    - Example: `https://bitcoin.com`
- `EXPLORER_URL` Blockchain explorer URL
    - Example: `https://bscscan.com/address/0x0000000000000000000000000000000000000000`
- `ADMIN_USERNAME` Your telegram username
    - Example: `johndoe`
- `MAX_USERS` Maximum number of participants
    - Example: `1000` *do not* include "," must be float number
- `MAX_REFS` Maximum number of referrals per participant
    - Example: `5`
- `CAPTCHA_ENABLED` Enable or disable captcha at start
    - Example: `YES` or `NO`
- `TWITTER_LINKS` Twitter page links seperated by comma
    - Example: `https://twitter.com/bitcoin,`
    - Example: `https://twitter.com/bitcoin,https://twitter.com/ethereum`
- `TELEGRAM_LINKS` Telegram group links seperated by comma
    - Example: `https://t.me/single,`
    - Example: `https://t.me/multi,https://t.me/ple`
- `DISCORD_LINKS` Discord server links seperated by comma
    - Example: `https://discord.gg/example,`
    - Example: `https://discord.gg/multi,https://discord.gg/ple`
- `DB_URI` Get one from https://cloud.mongodb.com/. Replace `<username>` and `<password>`
    - Example: `mongodb+srv://<username>:<password>@cluster0.abcde.mongodb.net/myFirstDatabase?retryWrites=true&w=majority`


## MongoDB Easy Tutorial

Watch: https://www.youtube.com/watch?v=Ej05tq1220A


## Convert JSON to CSV or XLS

Go: https://www.convertcsv.com/json-to-csv.htm


## Some Screenshots

<img src="./images/1.jpg" width="40%" height="40%">  <img src="./images/2.jpg" width="40%" height="40%">


## Tips and Airdrops are appreciated

### 0x373e8228cb85d2bf80f5d948620d6192ecc33889
