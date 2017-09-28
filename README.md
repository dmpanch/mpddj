mpddj
================================

This is a telegram bot that can make use of mpd as a dj. As for how to use it,
see /help from bot.

You'll need to set up config.py to configure it.
This bot depends on python-musicpd and python-telegram-bot.
Tested on Python 3.4.2 and 3.5.

'SUPER_USER' in config.py should be filled with your telegram username.

Setcommands list example for BotFather:

add - Add song by full path
sample - Randomly list some songs
status - Now playing
stats - Songs quantity
order - Order a song
searchorder - Search and order first match song
next - Skip current song
history - Order history
search - Search song
searchadd - Search and add first match song
playlist - Show current playlist
list - List files (don't do this!)
stream - Get stream address
help - Show this help


Feature:
* Quota for normal user.
* Search and order song easily.
* persistent history via pickle.
