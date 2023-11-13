# SkriptLib

A small library providing some scripts for PaperMC-Servers using [SkriptLang](https://github.com/SkriptLang).

## Installing Skript

1. You can download the latest version [here](https://skunity.com/downloads).
2. Copy the file into your **plugins** folder
3. Restart the server

## Using the Library

The plugin stores the scripts under **SERVER/plugins/Skript/scripts**. New folders and scripts can be added here.
To use the library, just clone this project into your **scripts** folder and reload the plugin by using the command **/skript reload all**.
You can also just download the files and copy them to the folder manually.

## Scripts provided by the Library

### World Edit

Adding commands to make WorldEdit workflows easier.

#### age.sk

This script provides commands to randomly replace **stone bricks** in a selected area with **mossy- and broken stone bricks**.
Also working for slaps without changing the blocks orientation.

##### Featured Commands

###### /age_all

Replaces stone blocks of types: x, y, z.
