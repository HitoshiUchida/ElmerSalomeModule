# ElmerSalome
Plugin for SALOME platform to access Elmer functionality 

##Requirements
* Elmer 8.2 with ElmerGui installed
* Salome 7.8

##Installation with custom plugin-directory
* create a plugin directory in the root path of SALOME or somewhere convenient, if not already using one
* copy ElmerSalome-directory into the plugin directory
* copy the salome_plugins.py-file in the plugin directory or modify the existing file 
* register the directory via the SALOME_PLUGIN_PATH system variable

##Installation with standard Salome-directories:
* put everything int (e.g on win64):
\SALOME-7.8.0-WIN64\MODULES\GUI\RELEASE\GUI_INSTALL\share\salome\plugins\gui\
* or use  ~/.config/salome/Plugins
  
##ToDo:
*  check whether registration via system variables can be bypassed by using the env.bat batch file that starts SALOME
