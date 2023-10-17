# Hummus Websocket Bot
Raw basic websocket connections specifically built for Hummus and similar sites (ig it can be used on discord too but why not just use [Discord.py?](https://github.com/Rapptz/discord.py)), can be used in old discord revivals like Hummus and Oldground.

# Massive Important:
If you want to create a bot on Hummus, use my [newer Hummus.py package!](https://github.com/LG125YT/Hummus.py) It is still very much in development but it makes code a lot cleaner and easier to use! This repository is still up for archive purposes or something ig.

## Other Notices:
- If you are working with a website like Fosscord/Spacebar, please use [Fossbotpy](https://gitlab.com/arandomnewaccount/fossbotpy) instead.
- On Oldground the bot may show as online, even if the host file is not running. This is most likely a server error.
- If you run into a 403 error when sending a request, you are likely not including either the token or the user agent within the headers.

## About:
This project is made for Hummus, it provides a working bot to function on it. Hummus is a Discord 2016 revival.

This project is very basic, its made for the people who are too lazy to go figure out websocket connections themselves.

In the project's `check` function, all messages are checked and this is where you add new commands. The only command in this example is a simple response to a test command. Having your bot perform actions has to be done so through raw POST, GET, and PATCH requests to the API, since no wrapper is involved in this project. For information on Discord/Hummus's v6 API, read through [the documentation.](https://hummus.sys42.net/developers/docs/intro)
