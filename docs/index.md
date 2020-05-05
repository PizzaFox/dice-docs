title: Dice Documentation
description: A general purpose utility bot, with an economy, video game stats, moderation tools, and lots of other features.

# Dice Documentation

[![Become a Patron](https://img.shields.io/badge/become%20a-patron-f86754.svg)](https://www.patreon.com/bePatron?u=6109069&redirect_uri=https%3A%2F%2Fdice.js.org%2F&utm_medium=widget)
![Status](https://discordbots.org/api/widget/status/388191157869477888.svg?noavatar=true)
![Servers](https://discordbots.org/api/widget/servers/388191157869477888.svg?noavatar=true)
![Library](https://discordbots.org/api/widget/lib/388191157869477888.svg?noavatar=true)
![Upvotes](https://discordbots.org/api/widget/upvotes/388191157869477888.svg?noavatar=true)
![Deploys by Netlify](https://img.shields.io/badge/deploys%20by-netlify-00c7b7.svg)

## [Connect to Discord](https://discord.com/oauth2/authorize?client_id=388191157869477888&permissions=8&scope=bot)

## About

### What is this

This is the documentation for Dice. It serves as a reference for all the commands and their usage as well as information about Dice.

### What is Dice

Dice is a [Discord](https://discord.com) bot. It has lots of features including moderation, game stats, games, an economy, and many others.

### Features

* Customizable prefix
* Moderators can disable commands on their server
* `99.9`% uptime
* Server notification system
* Game statistics
* Robust economy system

### Commands

| Name                                                                         | Description                                                                                           | Group           |
|------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|-----------------|
| [`prefix`](/commands/utility/prefix)                                         | Shows or sets the command prefix.                                                                     | Utility         |
| [`ping`](/commands/utility/ping)                                             | Checks the bot's ping to the Discord server.                                                          | Utility         |
| [`account-age`](/commands/utility/account-age)                               | Check when an account was created.                                                                    | Utility         |
| [`average-numbers`](/commands/utility/average-numbers)                       | Gets the average of several numbers.                                                                  | Utility         |
| [`bot-info`](/commands/utility/bot-info)                                     | Information about Dice.                                                                               | Utility         |
| [`choose`](/commands/utility/choose)                                         | Choose an item from a list you provide.                                                               | Utility         |
| [`feedback`](/commands/utility/feedback)                                     | Submit bugs and suggestions to the developer.                                                         | Utility         |
| [`help`](/commands/utility/help)                                             | Displays a list of available commands, or detailed information for a specified command.               | Utility         |
| [`list-roles`](/commands/utility/list-roles)                                 | List all roles on a server.                                                                           | Utility         |
| [`quote-message`](/commands/utility/quote-message)                           | Quote a message from a text channel.                                                                  | Utility         |
| [`role-info`](/commands/utility/role-info)                                   | Get information on a role                                                                             | Utility         |
| [`roman-numerals`](/commands/utility/roman-numerals)                         | Converts numbers to and from roman numerals.                                                          | Utility         |
| [`statistics`](/commands/utility/statistics)                                 | Get statistics on Dice.                                                                               | Utility         |
| [`ban-user`](/commands/moderation/ban-user)                                  | Ban any user from your server.                                                                        | Moderation      |
| [`bulk-delete-messages`](/commands/moderation/bulk-delete-messages)          | Bulk delete messages in a text channel.                                                               | Moderation      |
| [`delete-role`](/commands/moderation/delete-role)                            | Delete a role from this server.                                                                       | Moderation      |
| [`kick-member`](/commands/moderation/kick-member)                            | Kick a member from your server.                                                                       | Moderation      |
| [`notifications`](/commands/moderation/notifications)                        | Check or set what notifications for server events are sent to a channel.                              | Moderation      |
| [`unban-user`](/commands/moderation/unban-user)                              | Unban a user from a server.                                                                           | Moderation      |
| [`bible`](/commands/search/bible)                                            | Get any bible verse from the World English Bible                                                      | Search          |
| [`crypto-currency-look-up`](/commands/search/crypto-currency-look-up)        | Look up a crypto currency.                                                                            | Search          |
| [`lmgtfy`](/commands/search/lmgtfy)                                          | Generate a let-me-Google-that-for-you link.                                                           | Search          |
| [`npm-search`](/commands/search/npm-search)                                  | Get information about an NPM package                                                                  | Search          |
| [`look-up-stock`](/commands/search/look-up-stock)                            | Get the price of a stock.                                                                             | Search          |
| [`top-crypto-currencies`](/commands/search/top-crypto-currencies)            | Get prices for the top crypto currencies.                                                             | Search          |
| [`7-days-to-die-server-status`](/commands/games/7-days-to-die-server-status) | Get information about a 7 Days to Die server.                                                         | Games           |
| [`csgo-server-status`](/commands/games/csgo-server-status)                   | Get information about a Counter-Strike Global Offensive server.                                       | Games           |
| [`dice-game`](/commands/games/dice-game)                                     | Bet a wager on a multiplier.                                                                          | Games           |
| [`fortnite-statistics`](/commands/games/fortnite-statistics)                 | Get statistics of a Fortnite player.                                                                  | Games           |
| [`game-calculator`](/commands/games/game-calculator)                         | Calculate the odds of winning a round of the betting game.                                            | Games           |
| [`garrys-mod-server-status`](/commands/games/garrys-mod-server-status)       | Get information about a Garry's Mod server.                                                           | Games           |
| [`information`](/commands/games/information)                                 | Get information on a user.                                                                            | Games           |
| [`insurgency-server-status`](/commands/games/insurgency-server-status)       | Get information about a Insurgency server.                                                            | Games           |
| [`overwatch-statistics`](/commands/games/overwatch-statistics)               | Get statistics of an Overwatch player.                                                                | Games           |
| [`russian-roulette`](/commands/games/russian-roulette)                       | Play a game of Russian roulette.                                                                      | Games           |
| [`rust-server-status`](/commands/games/rust-server-status)                   | Get information about a Rust Server                                                                   | Games           |
| [`simulate-game`](/commands/games/simulate-game)                             | Simulate a round of the betting game.                                                                 | Games           |
| [`starbound-server-status`](/commands/games/starbound-server-status)         | Get information about a Starbound server.                                                             | Games           |
| [`date-facts`](/commands/fun/date-facts)                                     | Get a fact about a date.                                                                              | Fun             |
| [`day-facts`](/commands/fun/day-facts)                                       | Get a fact about a day.                                                                               | Fun             |
| [`number-facts`](/commands/fun/number-facts)                                 | Get a fact about a number.                                                                            | Fun             |
| [`oldest-member`](/commands/fun/oldest-member)                               | See who the oldest member on the server is.                                                           | Fun             |
| [`random-cat-image`](/commands/fun/random-cat-image)                         | Get a picture of a random cat.                                                                        | Fun             |
| [`random-dog-image`](/commands/fun/random-dog-image)                         | Get a picture of a random dog.                                                                        | Fun             |
| [`roll-die`](/commands/fun/roll-die)                                         | Roll a die.                                                                                           | Fun             |
| [`xkcd`](/commands/fun/xkcd)                                                 | Get an XKCD comic.                                                                                    | Fun             |
| [`year-facts`](/commands/fun/year-facts)                                     | Get a fact about a year.                                                                              | Fun             |
| [`invite`](/commands/single-response/invite)                                 | An invite link for Dice.                                                                              | Single response |
| [`nitro`](/commands/single-response/nitro)                                   | This message can only be viewed by users with Discord Nitro.                                          | Single response |
| [`support`](/commands/single-response/support)                               | An invite to the Dice server.                                                                         | Single response |
| [`vote`](/commands/single-response/vote)                                     | Vote once per day and get double your daily.                                                          | Single response |
| [`add-self-role`](/commands/selfroles/add-self-role)                         | Add a role to a server's self roles.                                                                  | Selfroles       |
| [`delete-self-role`](/commands/selfroles/delete-self-role)                   | Delete a self-assigned role from this server.                                                         | Selfroles       |
| [`get-self-role`](/commands/selfroles/get-self-role)                         | Get a self-assigned role from this server.                                                            | Selfroles       |
| [`list-self-roles`](/commands/selfroles/list-self-roles)                     | List all self-assigned roles from this server.                                                        | Selfroles       |
| [`remove-self-role`](/commands/selfroles/remove-self-role)                   | Remove a self-assigned role from yourself.                                                            | Selfroles       |
| [`get-minecraft-body`](/commands/minecraft/get-minecraft-body)               | Shows a Minecraft user's body.                                                                        | Minecraft       |
| [`get-minecraft-face`](/commands/minecraft/get-minecraft-face)               | Shows a front view of a Minecraft user's face.                                                        | Minecraft       |
| [`get-minecraft-head`](/commands/minecraft/get-minecraft-head)               | Shows an isometric view of a Minecraft user's head.                                                   | Minecraft       |
| [`get-minecraft-mini-me`](/commands/minecraft/get-minecraft-mini-me)         | Shows a 'mini-me' of a Minecraft user's body with an option for a transparent background or gradient. | Minecraft       |
| [`get-minecraft-skin`](/commands/minecraft/get-minecraft-skin)               | Get the skin of a Minecraft user.                                                                     | Minecraft       |
| [`minecraft-server-status`](/commands/minecraft/minecraft-server-status)     | Get information about a Minecraft server.                                                             | Minecraft       |
| [`balance`](/commands/economy/balance)                                       | Check a user's balance.                                                                               | Economy         |
| [`convert-oats`](/commands/economy/convert-oats)                             | Converts oats to another bot's currency.                                                              | Economy         |
| [`daily`](/commands/economy/daily)                                           | Collect your daily oats.                                                                              | Economy         |
| [`discoin-rates`](/commands/economy/discoin-rates)                           | Lists the conversion rates for Discoin currencies.                                                    | Economy         |
| [`leaderboard`](/commands/economy/leaderboard)                               | Shows a top ten leaderboard of who has the most oats.                                                 | Economy         |
| [`transfer`](/commands/economy/transfer)                                     | Transfer oats to another user.                                                                        | Economy         |
| [`base64`](/commands/developer/base64)                                       | Converts text to and from Base64 encoding.                                                            | Developer       |
| [`color`](/commands/developer/color)                                         | Display and convert a color.                                                                          | Developer       |
| [`database-ping`](/commands/developer/database-ping)                         | Checks the bot's ping to the Discord server and does a database request.                              | Developer       |
| [`shard`](/commands/developer/shard)                                         | Get info about this shard.                                                                            | Developer       |
| [`groups`](/commands/commands/groups)                                        | Lists all command groups.                                                                             | Commands        |
| [`enable`](/commands/commands/enable)                                        | Enables a command or command group.                                                                   | Commands        |
| [`disable`](/commands/commands/disable)                                      | Disables a command or command group.                                                                  | Commands        |

### Build Status

| Service name  | Latest build                                                                                                                                              | Deployment                                                                                                                                                       | Coverage                                                                                     |
|---------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| Bot           | [![Build Status](https://travis-ci.com/dice-discord/bot.svg?branch=master)](https://travis-ci.com/dice-discord/bot)                                       |                                                                                                                                                                  | ![Coverage](https://img.shields.io/codecov/c/github/dice-discord/bot.svg)                    |
| Docs          | [![Build Status](https://travis-ci.com/dice-discord/docs.svg?branch=master)](https://travis-ci.com/dice-discord/docs)                                     | [![Netlify Status](https://api.netlify.com/api/v1/badges/4b6e543a-c458-4b3d-83e8-d8018c1e79b3/deploy-status)](https://app.netlify.com/sites/dicediscord/deploys) |                                                                                              |
| Keyv Provider | [![Build Status](https://github.com/dice-discord/commando-provider-keyv/workflows/Node%20CI/badge.svg)](https://github.com/dice-discord/commando-provider-keyv/actions) |                                                                                                                                                                  | ![Coverage](https://img.shields.io/codecov/c/github/dice-discord/commando-provider-keyv.svg) |
| Reported      | [![Build Status](https://travis-ci.com/dice-discord/reported.svg?branch=master)](https://travis-ci.com/dice-discord/reported)                             |                                                                                                                                                                  | ![Coverage](https://img.shields.io/codecov/c/github/dice-discord/reported.svg)               |
| Status Page   | [![Build Status](https://travis-ci.com/dice-discord/status-page.svg?branch=master)](https://travis-ci.com/dice-discord/status-page)                       | [![Netlify Status](https://api.netlify.com/api/v1/badges/1c8af42c-0d7a-49f5-afaf-6b66b4597086/deploy-status)](https://app.netlify.com/sites/dice-status/deploys) |                                                                                              |
