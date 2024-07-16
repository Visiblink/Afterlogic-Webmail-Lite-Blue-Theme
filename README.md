# Afterlogic-Webmail-Lite-Blue-Theme
An unofficial blue theme for Afterlogic Webmail Lite.

To install, you have a couple of choices.

1. You can just drop the styles.css file into static/styles/themes/Default to change the default look. It would probably be a good idea to create a backup of the existing default file before doing that in case you don't like the change.

Or:

2. Create a new directory and add your style to the data/settings/modules/CoreWebclient.config.json:

A. Create a new directory called "Blue" in static/styles/themes/ (which would be static/styles/themes/Blue).

B. Drop the styles.css file into that directory.

C. Edit data/settings/modules/CoreWebclient.config.json to add a new entry menu for the Blue theme:

Find this section:

    "ThemeList": [
        [
            "Default",
            "DefaultDark",
            "DeepForest",
            "Funny",
            "Sand"
        ],
        "array",
        null,
        "List of themes available"
    ],

Change it to look like this:

    "ThemeList": [
        [
            "Blue",
            "Default",
            "DefaultDark",
            "DeepForest",
            "Funny",
            "Sand"
        ],
        "array",
        null,
        "List of themes available"
    ],

Thanks to d3rdav3 for the info on the config file. You can find his dark theme for Afterlogic Webmail at https://github.com/d3rdav3/DK-Afterlogic-Webmail-Dark-Theme.
