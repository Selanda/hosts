# Readme

A heavily modified version of the HOSTS file used by Microsoft TCP/IP for Windows which includes modifications for:
- NHLGames & Lazyman
- RoviEPG for WMC
- Acronis True Image
- Microsoft ad servers
- Malwarebytes
- Adobe Acrobat 10.x
- Adobe Acrobat 11.x
- Adobe CS6
- Adobe LR6.6
- Adobe Acrobat DC
- Adobe Photoshop 2025
- Blocking of known botnet addresses

Note: If you are seeing a "This unlicensed Adobe app will be disabled soon" error after launching Photoshop, also block "Photoshop.exe" using Windows Firewall rules.



# Instructions for use

Navigate to `C:\Windows\System32\Drivers\etc\` and save a backup copy of your hosts file either as `hosts.bak` or save a copy of the `hosts` file to a different folder.

Either copy the provided `hosts` file into that folder which will overwrite the existing version.
Or
Open the `hosts` file in the GitHub and copy only the sections you want/need. *You will need to open the file in an editor in Admin mode to make any changes to the file contents.*
