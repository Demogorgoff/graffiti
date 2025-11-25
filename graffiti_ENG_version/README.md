```
graffiti - Program for leaving messages between users of the same Linux system.

Author: Demogorgon
Inspired by or fork of mural in shellscript by slackjeff: slackjeff@riseup.net

Changelog:
03/04/2024 - Spelling correction - devnull (The POSIX Way Samurai)
13/11/2025 - ASCII banner, new menu, program renaming - Demogorgon
13/11/2025 - Protection against command injection / escape codes - Demogorgon

Suggested requirements (Run as root or superuser):
# Copy the graffiti shell script program for all users to use
# cp graffiti /usr/local/bin/
# chmod +x /usr/local/bin/graffiti
# As root, create the message file and add an "enter" before the first entry, for standardized reading.

# touch /var/log/graffiti_wall.log && printf '\n' > /var/log/graffiti_wall.log 
# chmod 666 /var/log/graffiti_wall.log
# Optional:
# chattr +a /var/log/graffiti_wall.log (append-only mode)
# To edit: chattr -a /var/log/graffiti_wall.log

Optional:
# chattr +a /var/log/graffiti_wall.log (append-only mode)
# To edit: chattr -a /var/log/graffiti_wall.log
```
