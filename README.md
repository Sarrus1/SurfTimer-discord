# SurfTimer-discord

![Downloads](https://img.shields.io/github/downloads/ilyasafr/SurfTimer-discord/total?style=flat-square) ![Last commit](https://img.shields.io/github/last-commit/ilyasafr/SurfTimer-discord?style=flat-square) ![Open issues](https://img.shields.io/github/issues/ilyasafr/SurfTimer-discord?style=flat-square) ![Closed issues](https://img.shields.io/github/issues-closed/ilyasafr/SurfTimer-discord?style=flat-square) ![Size](https://img.shields.io/github/repo-size/ilyasafr/SurfTimer-discord?style=flat-square) ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ilyasafr/SurfTimer-discord/Compile%20with%20SourceMod?style=flat-square)

## Description

Sends nice Discord embeded messages when a new map record is set.
The messages will look like this:

![Preview](https://raw.githubusercontent.com/ilyasafr/SurfTimer-discord/master/img/desc.png)

## Requirements

- Sourcemod and Metamod
- [SurfTimer-Official (Sad's Fork)](https://github.com/qawery-just-sad/Surftimer-Official)
- [SMJansson](https://forums.alliedmods.net/showthread.php?t=184604)
- [SteamWorks](https://forums.alliedmods.net/showthread.php?t=229556)

## Installation

1. Grab the latest release from the release page and unzip it in your sourcemod folder.
2. Restart the server or type `sm plugins load SurfTimer-discord` in the console to load the plugin.
3. The config file will be automatically generated at `cfg/sourcemod/SurfTimer-discord.cfg`
4. In the config file, configure your Discord Webhook and your Steam API key (optional, you can get it [here](https://steamcommunity.com/dev/apikey)).

## Configuration

- You can modify the phrases in addons/sourcemod/translations/SurfTimer-discord.phrases.txt.
- Once the plugin has been loaded, you can modify the cvars in cfg/sourcemod/SurfTimer-discord.cfg.

## Usage

 - You can use the `sm_ck_discordtest` command to test the messages.