# RPG Database

RPG database for [Godot Engine](https://godotengine.org) inspired on RPG Maker's database editor made in C#
Forked and actively updating to modern Godot versions 4.4.1+.
Currently only the GD version is being worked on. C# version once GD version is fully working.

## How to use

- Copy the folder rpg_database from the project in "res://addons/".
- Create a new folder in the root of your project called "databases" (without the quotes).
- If you are using the C# version, build the project.
- Go to your project's Settings and enable the plugin.
- A button should show above the inspector. Press it to open the database

Feel free to open an issue if you find bugs or have a feature request

# Version 1.2a
- assume all previous features are broken
- updated all GD scripts to be compliant with changes up to engine version 4.4.1
- UI elements are completely broken and non-functional
- changed all "WindowDialog" elements due to deprecation of that Node type.
- altered layouts to move away from Container restrictions, only to discover that they're meant to be laid out programatically; will revert next update

You can also find the ORIGINAL project by user "sdtv9507" at [itch.io](https://sdtv9507.itch.io/godot-rpg-database-manager)
