# How to dockerize your Telegram bot

Clone or fork this repo to use it as a base to create a Telegram bot, dockerized and using Python as programming language.

## Structure:

* `bot.py`: your bot's codebase
* `Dockerfile`: the file to build the bot image.
* `docker-compose.yml`: used to start the bot.
* `requirements.txt`: used to specify your dependencies.

## How to deploy the bot

1. Clone your bot.
2. Write an `.env` file with your `TELEGRAM_TOKEN` in it.
3. Run `docker-compose up -d` and wait for the build to finish.

That's it. Enjoy your dockerized bot. 🚀
