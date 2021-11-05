# ZombieMud-Plugins

## Chat and Channel Pluggings:

### Installation
* Copy plugin files (.xml files) to the plugin directory under mushclient, typically "C:\Program Files (x86)\MUSHclient\worlds\plugins"
* Copy world files (.MCL files) to the worlds directory
* In mushclient add the plugins: File->Plugins or Shift+Ctrl+P click add and locate the added plugins

### Default Settings
In the plugin there are some variables at the begining of the script tag:
* chat_world = "channels|tells" -- this must match the name of the world the text will be redirected to
* bell = 1 -- This will make a bell sound when you recevie a tell
* log_directory = "ZombieMush\\Logs\\" -- this is <Mushclient Install Location>\worlds\zombieMush\Logs
* logit = 1 -- This will control logging
  
Additionally the triggers will omit the text from the main world, if you don't want that change the omit_from_output="y" to "n"
