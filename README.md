<h1 align="center">
  <br>





     _____    __   ______   ______   ______   ______   _____      
    /\  __-. /\ \ /\  ___\ /\  ___\ /\  __ \ /\  == \ /\  __-.   
    \ \ \/\ \\ \ \\ \___  \\ \ \____\ \ \/\ \\ \  __< \ \ \/\ \  
     \ \____- \ \_\\/\_____\\ \_____\\ \_____\\ \_\ \_\\ \____-   
      \/____/  \/_/ \/_____/ \/_____/ \/_____/ \/_/ /_/ \/____/    
                                                                                         
                                   
                                  
                                  
                                  
                                  
                           
  <br>
 DiscordTicketSystem
  <br>
</h1>

<h4 align="center">A Free Discord ticket system bot
.</h4>


<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://www.trendingus.com/wp-content/uploads/2021/09/Trending-Discord-Bots-to-Game-Up-Your-Server-1920x768.jpg)

## Key Features

* Users of your Discord Server can create a support ticket with one click
* Customize your ticket system with emoji. 
* Only the Staff and the user that create the ticket can read it (You need to set discord permissions).


## How To Use

You can build the project using Pycharm, then you need to insert your discord bot token inside the code

```
bot.run("Your Discord Developer Token")

```

Change the discord channel ID  in the config file with this path

```
972259027276922920 973011782069260359 973005437639200818 972259028476526622
968628680089808936 973018083667087430 973016856485056643 973016680022310962

```
Change the message text if you want

```python
await ticket_channel.send(
                f"{payload.member.mention} Thank you for creating a ticket! Use **'-close'** to close your ticket.")


```
Commands:

```
Add a reaction to open a ticket

Send "-close'" to close the ticket

General bot commands trigger: "£"

```
If you need to change the bot trigger edit:

```python
bot = commands.Bot(command_prefix="£")
bot.ticket_configs = {}

```
If you need to use a custom emoji for reactions:

```python
if payload.member.id != bot.user.id and str(payload.emoji) == u"\U0001F3AB":
.
.
.
await msg.add_reaction(u"\U0001F3AB")
```
Host the boot on a server! you need also a discord developer account.

> **Note**
> Add the bot to your discord server with admin permissions


## Credits

Russo Giovanni M.


## License

MIT

---

