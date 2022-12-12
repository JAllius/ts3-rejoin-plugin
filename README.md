To modify, open ./code/src/test_plugin.vcxproj in Visual Studio. Make sure to have C++ with support for Windows XP installed and configured.
Currently only 32bit supported.

To create a new ts3_plugin file, replace .dll in ./RejoinPlugin/plugins, create a zip with the plugins folder and the package.ini containing the plugin version informations and use .ts3_plugin instead of .zip as file extension.