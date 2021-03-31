# How to dockerize your Telegram bot

Clone or fork this repo to use it as a base to create a dockerized  Telegram bot, using Python as programming language.

## Structure

* `bot.py`: your bot's codebase
* `Dockerfile`: the file to build the bot image.
* `docker-compose.yml`: used to start the bot.
* `requirements.txt`: used to specify your dependencies.

## How to deploy the bot

1. Clone or fork this repo.
2. Write your bot in `bot.py`.
3. Write an `.env` file with your `TELEGRAM_TOKEN` in it and other env vars.
4. Run `docker-compose up -d` and wait for the build to finish.

That's it. Enjoy your dockerized bot. 🚀
