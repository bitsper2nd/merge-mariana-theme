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

![cool](https://github.com/user-attachments/assets/4ed46338-60e5-4899-8ddf-6d565d1d6131 "Mariana Plus (Cool)")

Mariana Plus (Neutral)

![neutral](https://github.com/user-attachments/assets/51f2025e-3e8f-4529-8639-2154554ffbb2 "Mariana Plus (Neutral)")

Mariana Plus (Warm)

![warm](https://github.com/user-attachments/assets/e444b49d-6ba9-405d-9f08-d92c4a7fc98c "Mariana Plus (Warm)")

## Quick tip

Quickly switch between themes on Sublime Merge with the command palette:
- Open a new file
- Paste the following code:
```
// Change Theme
    [
        {
            "caption": "Change Theme: Mariana",
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
    ]
```

- Save the file as `Default.sublime-commands` in `Sublime Merge/Packages/User` folder.
- Open the command palette and type **Change**.

## Extra

Here is the repo of the [color scheme](https://github.com/bitsper2nd/sublime-mariana-scheme) for Sublime Text. Also checkout my [other theme](https://github.com/bitsper2nd/merge-monokai-theme) based on the Monokai color palette.
