> [<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/roddyfred)

# Use Node.Js 18 or later

## Functionality

| Functional                            | Supported |
| ------------------------------------- | :-------: |
| Claiming tasks                        |    ✅     |
| Claiming daily rewards                |    ✅     |
| Palying games                         |    ✅     |
| Multithreading                        |    ✅     |
| Data caching                          |    ✅     |
| Creating sessions with qrcode         |    ✅     |
| Using a session/query_id              |    ✅     |
| Binding a proxy to a session/query_id |    ✅     |
| Random sleep time between clicks      |    ✅     |

### [How to add query id](https://github.com/Freddywhest/RockyRabbitBot/blob/main/AddQueryId.md)

### [How to use python sessions with this bot](https://github.com/Freddywhest/SessionConvertor)

## [Settings]

| Settings                       | Description                                                                |
| ------------------------------ | -------------------------------------------------------------------------- |
| **API_ID / API_HASH**          | Telegram API ID and Hash obtained from my.telegram.org                     |
| **AUTO_PLAY_GAME**             | Whether the bot should play games (True / False)                           |
| **AUTO_CLAIM_TASKS**           | Whether the bot should claim tasks (True / False)                          |
| **DELAY_BETWEEN_STARTING_BOT** | Delay between bot starts (eg. [20, 30])                                    |
| **DELAY_BETWEEN_PLAYING_GAME** | Delay between starting/playing games (eg. [20, 30])                        |
| **DELAY_BETWEEN_TASKS**        | Delay between completing tasks (eg. [20, 30])                              |
| **SLEEP_BETWEEN_REQUESTS**     | Delay between taps in seconds (eg. [500, 1200])                            |
| **USE_PROXY_FROM_JS_FILE**     | Whether to use proxy from the `bot/config/proxies.js` file (True / False)  |
| **USE_PROXY_FROM_TXT_FILE**    | Whether to use proxy from the `bot/config/proxies.txt` file (True / False) |

## Installation

You can download [**Repository**](https://github.com/skhassandx/Moonbix) by cloning it to your system and installing the necessary dependencies:

```shell
~ >>> git clone https://github.com/skhassandx/Moonbix.git
~ >>> cd Moonbix
~ >>> cd 4

#Linux and MocOS
~/Moonbix/4 >>> chmod +x check_node.sh
~/Moonbix/4 >>> ./check_node.sh

OR

~/Moonbix/4 >>> npm install
~/Moonbix/4 >>> cp .env-example .env
~/Moonbix/4 >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/Moonbix/4 >>> node index.js

#Windows
1. Double click on INSTALL.bat in Moonbix/4 directory to install the dependencies
2. Double click on START.bat in Moonbix/4 directory to start the bot

OR

~/Moonbix/4 >>> npm install
~/Moonbix/4 >>> cp .env-example .env
~/Moonbix/4 >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/Moonbix/4 >>> node index.js
```

Also for quick launch you can use arguments, for example:

```shell
~/Moonbix/4 >>> node index.js --action=1

OR

~/Moonbix/4 >>> node index.js --action=2 #For sessions

OR

~/Moonbix/4 >>> node index.js --action=3 #For query ids

#1 - Create session
#2 - Run bot with sessions
#3 - Run bot with query ids
```
