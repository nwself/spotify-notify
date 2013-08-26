spotify-notify
==============

Notifications for Spotify now playing.

This is a modification of a script that can be found in various places but originally (or so it seems) here:

[https://code.google.com/p/spotify-notify/](https://code.google.com/p/spotify-notify/)

This might be a little less friendly than that one but it has two improvements:

1. Reposts notifications if spotify-notify.py gets a USR1 signal. This means you hit a key command to fire a shortcut that runs `pkill -SIGUSR1 spotify-notify`.

2. Mutes any song whose album name looks like a URL.
