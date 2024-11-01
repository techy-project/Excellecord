# Excellecord
Excellecord (a portmanteau of the names "Excellent" and "Discord") is a Discord bot template written in Python.

# Installation
Excellecord requires these libraries:
- discord.py (Discord library)
- requests (HTTP request library)

Install them before running the Excellecord code:
```
pip install discord.py
pip install requests
```
Arch Linux users might get an error that they need to use pacman to install the libraries.

If you are an Arch Linux user, use virtual environment or `pipx` instead.

# Balance saving
Excellecord includes a balance save file called `balance_save.json`. It goes like this:
```
{"userid": number_of_balance}
```
It also supports multiple user IDs:
```
{"userid1": number_of_balance1, "userid2": number_of_balance2}
```
The balance save file is made of JSON.
