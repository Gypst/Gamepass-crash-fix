# Gamepass-crash-fix
This script was created to solve the problem of applications crashing when running through the Xbox app, particularly games with Gamepass.

## How to use
Using this script is very simple. Just run the script and follow the commands in the console:
- Press key "1" to kill `explorer.exe` after 5 minutes (you can edit the time in the .bat file).
- Press key "2" to restart `explorer.exe`.

### How to change timeout for explorer kill
To change the delay before shutting down explorer.exe, simply locate the line `TIMEOUT /T 300 /NOBREAK` in the script and replace the value after `/T` with your preferred delay in seconds.
