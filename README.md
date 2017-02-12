#### OmegleIRC (Python2.7) Forked from: https://github.com/rfw/omegleirc2
Bot that allows you to bridge between Omegle and IRC.

### -- Install requirements
You will need the following in other to start the Omegle bot:
- python2.7
- Pip2.7
- Run % pip2.7 -r requirements.txt --user (This list is incomplete, see below.)
In order to install all Python2.7 modules needed to run the bot.

### -- Configuration
You will find inside configuration.py similair information as mentioned below.
Make sure you'll edit the configuration.py in order to make the bot work.
Note that SSL is not supported.
- NICKNAME        = "Omegle" // Bots nickname.
- REALNAME        = "OmegleIRC - bigger, better, awesomer!" // Bots REALNAME.
- IDENT           = "Omegle" // The Bots IDENT.
- NICKSERV_PASS   = None // Authenticate with Anope's NickServ.
- SERVER          = "127.0.0.1" // Define the IRC server hostname/IP.
- PORT            = 6667 // Define the IRC server port.
- CHANNELS        = [ "#omegle", "#secondchannel" ] // Channel for the bot to join.
- PREFIX_CMD      = ";" // Define perfix or trigger.
- PREFIX_INVIS    = "-" // ?
- MAX_CLIENTS     = 5 // Max. connected Omegle users.
- OMEGLE_SERVERS  = [ "omegle.com" ] // Omegle Server.

### -- Start and run the bot.
Run the Omegle bot as follow:
- % python2.7 bot.py

This will make you launch the bot in foreground mode.
It is possible to run the bot in background mode.
#### We recommend you to use screen for this.
- % screen -S "python2.7 bot.py"

### -- Previous installed modules which where working with OmegleIRC
You can find a list with previous working pip2.7 modules in the "pip_modules_fbsd.txt" file.
