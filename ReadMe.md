# ExtendedEmotes
This addon allows access to additional emotes supported by [Wallcraft](wallcraft.org). Feel free to read the lua file for a full emote list.

# Installation:
1. Click the Code button to the upper right hand corner and select download or click [here](https://github.com/tubtubs/ExtendedEmotes/archive/refs/heads/master.zip).
2. Unzip the download into your Interface/Addons folder in your WoW directory. Eg: *C:\Games\WoW\Interface\Addons*
3. Rename the folder from *ExtendedEmotes-master* to *ExtendedEmotes*
4. Restart WoW and enable the addon from the character selection screen. Ensure your addon memory cap is set to 0 (no limit) or a high number like 256.

You can also use the [GitAddonsManager](https://gitlab.com/woblight/GitAddonsManager) to install this addon, but it will not install the icon patch.

* If there are any further issues with installation, ensure that *ExtendedEmotes.toc* is in the root folder. There should be no subdirectories. Eg: *C:\Games\WoW\Interface\Addons\ExtendedEmotes\ExtendedEmotes.toc*

# Dev Notes
This list of emotes and their relevant slash commands is from the original ui files for Wrath of the Lich King. All I've done is re-order their indexes so theres no gaps, allowing them to function properly in the default chat handler. Doesn't need to modify the default UI to work. Left out the default vanilla emotes, as theres no need to include those.