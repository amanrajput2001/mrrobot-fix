# MR.ROBOT Userbot
![Python Version](https://img.shields.io/badge/Python-v3.9-blue)
[![Join Group](https://img.shields.io/badge/Telegram-Join%20Group-informational)](https://t.me/program4hack)
[![HitCount](http://hits.dwyl.com/AKHACKER-program4hack/mrrobot.svg)](http://hits.dwyl.com/AKHACKER-program4hack/mrrobot)
[![Contributors](https://img.shields.io/github/contributors/AKHACKER-program4hack/mrrobot)](https://github.com/AKHACKER-program4hack/mrrobot/graphs/contributors)
![Last Commit](https://img.shields.io/github/last-commit/AKHACKER-program4hack/mrrobot/main)
![Issues](https://img.shields.io/github/issues/AKHACKER-program4hack/mrrobot)
![Pull Requests](https://img.shields.io/github/issues-pr/AKHACKER-program4hack/mrrobot)

<img src="https://telegra.ph/file/0549cdcecfadeab0dfd40.jpg" width="160" align="right">

> A Telegram Userbot based on [Pyrogram](https://github.com/pyrogram/pyrogram)

This repository contains the source code of a Telegram Userbot and the instructions for running a
copy yourself. Beside its main purpose, the bot is featuring [**Pyrogram Asyncio**](https:////github.com/pyrogram/pyrogram/issues/181) and
[**Smart Plugins**](https://docs.pyrogram.org/topics/smart-plugins); feel free to explore the source code to
learn more about these topics.
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/amanrajput2001/mrrobot-fix)

I assume you will read this whole README.md file before continuing.

> Development in progress.

## Developing
To add extra modules to the bot, simply add the code into [userbot/plugins](userbot/plugins).I have made to functions for it first is ```.download``` which download media you can see in general in help menu and other is ```.load_plugin``` which load_plugin from download directory to plugin directory
.Each file
that is added to the plugins directory should have the following code at a minimum.
```python
from pyrogram import filters

from userbot import UserBot

@UserBot.on_message(filters.command('sample', ['.']))
async def module_name(client, message):
    await message.edit(
        "This is a sample module"
    )
```

This example is only for Pyrogram on_message events. 

# For New Plugins visit :

[![Plugins](https://img.shields.io/badge/Mrrobot-plugins-informational)](https://github.com/AKHACKER-program4hack/mrrobot-plugins)


## Credits, and Thanks to

*  [AKHACKER](https://github.com/AKHACKER-program4hack) Owner Of the Userbot. 

---




