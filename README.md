StarryPy3k_plugins
================

##This is a collection of plugins which can't be included in the core server for various reasons.  

#Plugins: 

## [mdeneen's Pushover plugin]
> This adds support for [Pushover](https://pushover.net) messages.  It supports the following features:

> - Send a notification when a player joins or leaves the server
> - Select a custom sound for when a player joins or leaves
> - ignore certain players

> ### Add the following block to your config file plugin section:
> ```
        "pushover": {
            "api_key": "API_KEY",
            "auto_activate": true,
            "ignored_players": [
                "CarrotsAreAnnoying",
                "Captain Unstable Network"
            ],
            "send_depart": true,
            "send_join": true,
            "sound_depart": "cosmic",
            "sound_join": "gamelan",
            "user_key": "USER_KEY"
        },
>```
