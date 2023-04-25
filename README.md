# Discord Voice Channel C2 aka DCVC2
![image](https://user-images.githubusercontent.com/34954477/234415119-662ecfb1-b38e-4a58-839b-3718f9017333.png).

This Multi-OS compatible tool was created to leverage Discord's voice channels for command and control operations. This tool operates entirely over the Real-Time Protocol (RTP) primarily leveraging <a href ="https://stealthbits.com/stealthaudit-for-active-directory-product/(https://github.com/bwmarrin/discordgo)">DiscordGo</a> and leaves no pesky traces behind in text channels. It is a command line based tool meaning all operations will occur strictly from the terminal on either Windows/Linux/OSX. Please use responsibly but have fun! ;)

## Requirements:
1. <a href ="https://discordpy.readthedocs.io/en/stable/discord.html">Read About DCVC2</a>
2. You need a Discord account.
3. You need a Discord server.
4. You need 2 Discord bots. I found it easiest to give both bots admin perms over the discord server but you can fine tune them to only need voice permissions. The best guide to create bots is <a href ="https://discordpy.readthedocs.io/en/stable/discord.html">here</a>.

## Build:
```
go mod download
go build server.go
go build agent.go
```
## Usage:
Shell commands:
```
cmd> whoami

desktop-3kjj3kj\sm00v
```
I added 2 hardcoded additions besides basic shell usage:
```
cmd> screenshot
screenshotting..............................................

&

cmd> download
download file path>C:\Users\sm00v\Downloads\34954477.jpg
............................................................
```
## Credits
<a href ="https://twitter.com/sm00v">Twitter: @sm00v</a>
