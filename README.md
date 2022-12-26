# Hypixel Eye

Hypixel Eye is a project I made mostly because I was bored yesterday. This scrapes all online members, and includes these data points

- **Username**: Self explanatory, the username of whoever we are looking at.
- **Status**: The 'title' of a member. Some, for example, are 'Forum Expert', 'Forum Nerd', and 'Dedicated Member'.
- **Action**: What the user is doing. This can be, but is not limited to, viewing profiles, threads, or user settings.
- **Time**: This is the time since it has been updated. The forums show what offline people has done in the last 20 minutes, so we can grab those aswell.

# Installation

1. Download the repository.
2. Download all depenecies. You can do this with `pip install -r requirements.txt`.
3. Open online.py in a text editor, and go to line 14 of the file . change `browser_cookie3.firefox` to your main browser. Ex: `browser_cookie3.chrome` or `browser_cookie3.safari`.
4. Log into hypixel.net on the browser specified above.
5. Run the script and wait.
