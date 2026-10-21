# Documentació del Bot de Discord
![Logotip de Discord](https://static.vecteezy.com/system/resources/thumbnails/023/741/066/small/discord-logo-icon-social-media-icon-free-png.png)

Pots registrar la teva aplicació al [Portal de Desenvolupadors de
Discord](https://discord.com/developers/applications.)

Per fer que el bot respongui, escoltem l'esdeveniment `messageCreate` i utilitzem el mètode `message.reply()`.

``` JavaScript
client.on('messageCreate', message => {
if (message.content === 'ping') {
message.reply('pong!');
}
});
```