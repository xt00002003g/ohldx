# python-zeit-serverless-telegram-bot
Example of Python Serverless Telegram bot to be used with Zeit.co (Now.sh)

# Step-by-step

## Add env variable to now sh

``` bash
now secrets add telegram-token <TELEGRAM_TOKEN>
```

## Register webhook
``` bash
curl "https://api.telegram.org/bot<TELEGRAM_TOKEN>/setWebhook?url=https://your-now-sh-project.now.sh/api"
```


# Literature
* https://dev.to/jolvera/deploy-a-python-serverless-function-on-zeit-now-22cf
* https://seminar.io/2018/09/03/building-serverless-telegram-bot/

------
Author: [@ohld](https://github.com/ohld)