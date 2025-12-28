# PlayerBots Addon - Russian Version 🇷🇺

> **Русская версия аддона PlayerBots с полной локализацией интерфейса**  
> **Russian version of PlayerBots addon with complete interface localization**

[![Russian](https://img.shields.io/badge/Language-Russian-red)](https://github.com/Belen007/wow-addon-playerbots)
[![Localization](https://img.shields.io/badge/Localization-ruRU-brightgreen)](https://github.com/Belen007/wow-addon-playerbots)
[![Fork](https://img.shields.io/badge/Fork-Original-blue)](https://github.com/whipowill/wow-addon-playerbots)

**Это форк оригинального аддона с добавленной русской локализацией.**  
**This is a fork of the original addon with added Russian localization.**

---

In the WoW private server community there was a guy named ike3 who wrote a bot script that would create robot players in the game.  You could have hundreds of them, and they would run around and fight and do quests, you could party w/ them, and even better you could bring your alts and play with them too.

Efforts are underway to port this bot code to [AzerothCore](http://www.azerothcore.org) via the [PlayerBots](https://github.com/ZhengPeiRu21/mod-playerbots) module.  This repository is an addon project that will facilitate managing the bots by the player ingame.  It begins as a fork of ike3's original addon package which he developed for the Mangos project.

## 🇷🇺 Русская локализация / Russian Localization

**Полностью переведённый интерфейс на русский язык!**  
**Fully translated interface to Russian!**

- ✅ Все кнопки и подсказки на русском
- ✅ Все сообщения и статусы на русском  
- ✅ Автоматическое определение языка игры
- ✅ 87+ переведённых строк интерфейса

**Автор локализации:** [@Belen007](https://github.com/Belen007)

**Оригинальный репозиторий:** [whipowill/wow-addon-playerbots](https://github.com/whipowill/wow-addon-playerbots)

## Install / Установка

**Для русской версии:**  
Download this repository as [zip](https://github.com/Belen007/wow-addon-playerbots/archive/main.zip) and extract into your ``C:\\Games\WoW\Interface\Addons\PlayerBots`` directory.

**For original version:**  
Download from [original repository](https://github.com/whipowill/wow-addon-playerbots/archive/master.zip).

## Manual

Be sure to consult the [Operator's Manual](https://github.com/whipowill/wow-addon-playerbots/blob/master/MANUAL.md) for detailed information about how to control the bots.

## Usage

Type `/bot` into the WoW chat bar to bring up the roster window.

![Screenshot](screenshots/bot_roster.png)

Click on the bot character, making him your target, to bring up the control window.

![Screenshot](screenshots/bot_controls.png)

## Supported Languages

The addon supports multiple languages:
- English (default)
- Chinese Simplified (zhCN)
- Chinese Traditional (zhTW)
- **Russian (ruRU)** - Added by [@Belen007](https://github.com/Belen007) 🇷🇺

The addon will automatically detect your game client's locale and use the appropriate language.

## Changelog

- Minor edits to original code to work w/ PlayerBots.
- SelectedBotPanel only shows if RosterPanel is already open.
- Added additional commands to the SelectedBotPanel.
- Strategy buttons issue positive commands, reset buttons issue negative commands.
- **Added Russian (ruRU) localization** - All interface elements and tooltips are now translated to Russian.

## Todo

- Attack by icon isn't on the panel atm.

## Credits

**Original Authors:**
- ike3 - Original addon creator
- whipowill - Fork maintainer

**Contributors:**
- [@Belen007](https://github.com/Belen007) - Russian (ruRU) localization

## References

- [ike3's Announcement](https://www.getmangos.eu/forums/topic/5401-ai-playerbot/)
- [ike3's Addon Package](https://github.com/ike3/mangosbot-addon)
- [ike3's Instructions](http://ike3.github.io/mangosbot-docs/)
- [Original Repository](https://github.com/whipowill/wow-addon-playerbots)
- [This Fork (Russian)](https://github.com/Belen007/wow-addon-playerbots)
