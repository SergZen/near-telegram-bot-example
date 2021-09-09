# Blockchain Telegram Bot Example

Based on: 
- [NEAR Rust Counter Example](https://examples.near.org/rust-counter)
- [Node.js Telegram Bot](https://github.com/yagop/node-telegram-bot-api)

## Install Telegram Bot

```sh
npm i node-telegram-bot-api
```

---

Set TELEGRAM_TOKEN to your Telegram Bot Token you receive from @BotFather

```
export TELEGRAM_TOKEN=1931340563:AA2G35TA_KABVSY2Y124NO6SilA4E1PT31
````

## Deploy [NEAR Rust Counter](https://examples.near.org/rust-counter)

Set CONTRACT_ID to address of your NEAR Rust Counter contract

```
export CONTRACT_ID=dev-1631189149748-7868807
````

## Usage

Assuming you've already created an account on [NEAR Wallet], authorize NEAR CLI:

 ```near login```
 
 and follow instructions. Be sure your account key was stored in `.near-credentials/testnet/` in your home folder.

---

Set NEAR_ACCOUNT_ID to account you used: 

```sh
export NEAR_ACCOUNT_ID=your-name.testnet
```

--

Run the app

```node app```

---

Follow to the telegram bot you created and any method available by NEAR Rust Counter:

- get_num
- increment
- decrement
- reset

Every call will be performed on behalf of your own account `NEAR_ACCOUNT_ID` and will be visible in the [NEAR Block Explorer]

[NEAR Wallet]: https://wallet.testnet.near.org/
[NEAR Block Explorer]: https://explorer.testnet.near.org/
