A Discord Bot to announce SpigotMC plugin updates on your Discord server. It's meant for plugin developers but can of course also be used by server admins to get notified about new updates.

It uses Spiget.org to fetch version information.

## Usage

Run the bot using Java 8 or higher: 

```shell
java -jar discord-spigot-update-bot.jar [arguments]
```

On first startup, the bot will generate three config files and shutdown again.
Adjust at least your `bot-token` and `channel-id` in the discord.yml file.
You can now add plugins to the plugins.yml file, then start the bot again.

Available arguments:

| Parameter | Description          |
|-----------|----------------------|
| --debug   | Raises the log level |

## Screenshots
![](https://static.jeff-media.com/img/discord-spigot-update-bot/discord-spigot-update-bot-screenshot1.png)

## Support

Feel free to join my Discord for help.

<a href="https://discord.jeff-media.com"><img src="https://api.jeff-media.com/img/discord1.png"></a>