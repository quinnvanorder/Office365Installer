# Office365Installer
Installs any Office365 product silently

•	Windows only 
•	Silently installs Office, can be run against user workstations as they are logged in and using the device. 
•	Only end user visible if they have prior Office versions running, as the installation will terminate them. 
•	Can be used on top of Office 2013 products, will upgrade them in place assuming they were of the Office 365 variants. 
•	Can be set to x86 or x64, and to any supported language. 
•	Can remove previous Office installs with an optional flag 
•	No need to have user credentials, once the software installs, it will prompt the user for credentials on first run to activate. 
•	Requires Office 365 licensing. 


**If this procedure fails, check the procedure logs, found at Agent>Agent Logs>Agent Admin Logs>Procedure History.** 

This procedure is built around the Microsoft Office Click 2 Run toolkit, as documented here: https://support.microsoft.com/en-us/help/2842297/product-ids-that-are-supported-by-the-office-deployment-tool-for-click 

Should the procedure stop working suddenly, the Office C2R Deployment toolkit must be replaced with a newer version. Download here :https://www.microsoft.com/en-us/download/details.aspx?id=49117 Upload to the shared files directory as indicated in the install instructions, and update lines 23, 26 and 33 to reflect new EXE name. 

NOTE: There is an incompatibility between Office 2016 and Project / Visio 2013. There is no workaround other than switching to Project / Visio 2016. This is a Microsoft issue, not a failing with the script. 
