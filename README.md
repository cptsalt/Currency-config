# Configurable Currency

This is a mod that adds a basic tracker for money, useful for RP servers. You can view your funds and send them to other players, and admins can add or remove funds via chat commands. The currencies used are entirely configurable, and therefore require some setup.

For a more in depth explanation of the client mod, you can find the steam page for the mod [here](https://steamcommunity.com/sharedfiles/filedetails/?id=3820038816).

# Server config
A sister mod for servers to use with the currency mod I made. Acts as a patch for configuring currencies. Not required for clients.

## How to use
This page is mainly meant for servers, but it includes a .pak for the mod anyway. For server owners looking to use this mod, here are some loose instructions on how to set up the files.

1. Download this mod as a zip file
2. Open and extract the zip into a workspace (it doesn't really matter where)
3. Open up the "currencyServer" folder and navigate to "currency_config.json"
4. Edit the config as needed. Reference "config_help.txt" to understand how different aspects of the config work
5. Once you're done editing, move the "currencyServer" folder to your server's mod folder
6. If you manually install mods to your server, move the .pak file as well
7. **BEFORE LOADING**, open your server's "starbound.config" file (usually in storage)
8. In starbound.config, add the following code:
`"CUR::adminCharacters" : {
  "[YOUR CHARACTER UUID]" : true
}`
9. Add UUID's for any other admin characters needed
10. If done correctly, your config should be loaded. You can test this with /money config while using a character added to the admin config

PLEASE read the license before using this mod on your server.

Additionally, please do not monetize your server with my mod. I'm pretty sure that's not allowed, and I am not responsible for any loss or damages which might occur from using this mod.
