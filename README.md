# Theme - Mariana Plus

Mariana theme for Sublime Merge 2.

Requires [related color](https://github.com/bitsper2nd/sublime-mariana-scheme) scheme. This implementation of Monokai uses the Sublime Merge Dark Theme as a template with the Monokai color palette.

## Install

Assuming the required color scheme is installed, git clone the project or download it into your Sublime Merge `Packages`
folder as `Mariana Theme`. Edit your merge `Preferences.sublime-settings` file to use the Monokai theme:

```
    "theme": "Mariana Plus (Cool).sublime-theme"
```

## Screenshots

Mariana Plus (Cool)

![cool](screenshots/cool.png "Mariana Plus (Cool)")

Mariana Plus (Neutral)

![neutral](screenshots/neutral.png "Mariana Plus (Neutral)")

Mariana Plus (Warm)

![warm](screenshots/warm.png "Mariana Plus (Warm)")

## Extra

Quickly switch between themes on Sublime Merge with the command palette:
- Open a new file
- Paste the following code:
```
// Change Theme
    {
        "caption": "Change Theme: Cool",
        "command": "set_preference",
        "args": {
            "setting": "theme",
            "value": "Mariana Plus (Cool).sublime-theme"
        },
    },
    {
        "caption": "Change Theme: Neutral",
        "command": "set_preference",
        "args": {
            "setting": "theme",
            "value": "Mariana Plus (Neutral).sublime-theme"
        },
    },
    {
        "caption": "Change Theme: Warm",
        "command": "set_preference",
        "args": {
            "setting": "theme",
            "value": "Mariana Plus (Warm).sublime-theme"
        },
    },
```
- Save the file as `Default.sublime-commands` in `Sublime Merge/Packages/User` folder.
- Open the command palette and type **Change**.
