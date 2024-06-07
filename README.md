# remove3dfolder
A windows reg script to remove 3d objects folder

### Disclaimer
This script modifies the windows registry. I do NOT take responsibility for what may happen to your system. Run this script at your own risk.

### How to use
* Run the .reg file as admin
* You may need to restart your system for the changes to take effect

### How it works
This script simply removes two registry entries: 
*```HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}```
*```HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}```
