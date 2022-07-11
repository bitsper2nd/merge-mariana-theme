# Theme - Mariana Plus

[Mariana](https://github.com/n0rmand0/Mariana-Pro-color-theme) theme for Sublime Merge 2.

This implementation of Monokai uses the Sublime Merge Theme as a template with the Mariana color palette.

## Install

Assuming the required color scheme is installed, git clone the project or download it into your Sublime Merge `Packages`
folder as `Mariana Theme`. Edit your merge `Preferences.sublime-settings` file to use the Mariana theme:

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

## Quick tip

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

## Extra

Here is the repo of the [color scheme](https://github.com/bitsper2nd/sublime-mariana-scheme) for Sublime Text. Also checkout my [other theme](https://github.com/bitsper2nd/merge-monokai-theme) based on the Monokai color palette.
