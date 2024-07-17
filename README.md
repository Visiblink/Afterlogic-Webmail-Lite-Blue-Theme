# Afterlogic-Webmail-Lite-Blue-Theme
An unofficial blue theme for Afterlogic Webmail Lite. I'm still finding the occasional element that needs to be rethemed, so check back for updates.

# Screenshots

![Afterlogic-Blue-Theme-Screenshot1](https://github.com/user-attachments/assets/406fba70-0bec-43e3-a044-2b3c9d676d25)

![Afterlogic-Blue-Theme-Screenshot2](https://github.com/user-attachments/assets/c9df00b1-b9d5-4776-a2d9-33e1c5f4b113)

# Installation

To install, you have a couple of choices.

1. You can just drop the styles.css file into static/styles/themes/Default to change the default look. It would probably be a good idea to create a backup of the existing default file before doing that in case you don't like the change.

The main benefits of this method are that it is easier to implement and it styles the login page as well.

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

Change it to look like this by adding the "Blue" line:

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
