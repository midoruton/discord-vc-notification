# discord-vc-notification

Authorise the bot from the following URL.

https://discordapp.com/oauth2/authorize?client_id=418329413860458496&scope=bot&permissions=53484608

Then add a line to the topic of the channel you want notifications:

```
discord-vc-notification: [CHANNEL]
```

Specify a space-delimited list of channel names to monitor.

## Example

```
discord-vc-notification: General
```

When someone joins the Voice Channel _General_, the bot posts a message to the
text channel.
