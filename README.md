# TS3 Channel Rejoin Plugin

This plugin is used to automatically reconnect to the previous channel when a hotkey is pressed or when kicked from the channel. Helpful to avoid friendly mod right abuse, but keep in mind if you keep annoying others you'll probably just get banned instead.

Currently only supported for 32bit client.

## Getting Started
Double-click the /RejoinPlugin/RejoinPlugin.ts3_plugin to open installer. 
If this doesn't work, instead copy the .dll from the plugins subfolder to your TS3 installation's plugin folder.

Set a hotkey for the plugin channel switch as well as create a hotkey for reconnecting to your ts3 server to rejoin to last channel you visited after getting kicked from the server.

## Modifying

To modify, open ./src/test_plugin.vcxproj in Visual Studio. Make sure to have C++ with support for Windows XP installed and configured.
Currently only 32bit supported.

To create a new ts3_plugin file, replace .dll in ./RejoinPlugin/plugins, create a zip with the plugins folder and the package.ini containing the plugin version informations and use .ts3_plugin instead of .zip as file extension.

## Copyright
Based on [TeamSpeak 3 Client Plugin SDK](https://github.com/TeamSpeak-Systems/ts3client-pluginsdk)