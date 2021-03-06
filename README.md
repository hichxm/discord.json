![discord.json](https://nsa39.casimages.com/img/2018/11/04/181104041539518569.png)
[![Build Status](https://travis-ci.org/dotOverflow/discord.json.svg?branch=master)](https://travis-ci.org/dotOverflow/discord.json)

- Discord.json | Make your own discord bot with json !
[Join our Discord server !](https://discord.gg/X5ccPhr)

![Sample configuration](https://nsa39.casimages.com/img/2018/11/04/181104042118770870.png)

```json
{
    "general": {
        "token": ""
    },
    "welcome": {
        "enabled": true,
        "type": "channel",
        "channel_id": "508650923447287812",
        "message": "Welcome {user} to {guild} ! Your id is {id} !"
    },
    "commands": [{
            "command": "!hey",
            "action": "send_message",
            "message": "Hey!"
        },
        {
            "command": "!heymp",
            "action": "send_dm",
            "message": "Hey!"
        },
        {
            "command": "!givemyskill",
            "action": "add_role",
            "role_id": ""
        },
        {
            "command": "!removemyskill",
            "action": "remove_role",
            "role_id": ""
        },
        {
            "command": "!switchmyskill",
            "action": "switch_role",
            "role_id": ""
        }
    ],
    "reaction_messages": [{
        "channel_id": "",
        "message_id": "",
        "action": "role",
        "role_id": "",
        "reaction": "🌠"
    }],
    "presence": {
        "enabled": true,
        "type": "watching",
        "text": "discord.json <3",
        "streaming_url": "https://www.twitch.tv/thomasbysfr"
    }
}
```

![Advancement](https://nsa39.casimages.com/img/2018/11/04/181104042331851103.png)

- [x] Welcome
    - [x] Types (channel/dm)
    - [x] Message variable ({user})
- [ ] Leave message
- [ ] Command & actions
    - [x] send_message
    - [x] send_dm
    - [x] switch_role
    - [x] add_role
    - [x] remove_role
    - [x] purge
    - [ ] send_embed
    - [ ] create_invite
- [x] Reaction messages
    - [x] Role switch
- [ ] Embed support
- [ ] Utils classes

![Useful links](https://nsa39.casimages.com/img/2018/11/04/181104042331933180.png)

- Used libraries :
[discord.js](https://github.com/discordjs/discord.js/)

- Useful websites :
[copy and paste emoji](https://www.copyandpasteemoji.com/)
