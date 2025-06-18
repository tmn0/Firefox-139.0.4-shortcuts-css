\~ Firefox 139.0.4 shortcuts edit  
Step 1: In Firefox address bar go to about:config  
Step 2: Set toolkit.legacyUserProfileCustomizations.stylesheets = true  
Step 3: For Windows, go to C:\Users\<User>\AppData\Roaming\Mozilla\Firefox\Profiles\xxxxxx.default-releasexxxxxx\chrome  
Step 4: In that folder, create or edit userContent.css  
Step 5: Restart Firefox to apply styles  

I wasn't so pleased with the recent changes for the homepage shortcuts css so I edited it myself.  

Bonus: disable auto-update feature in Windows (10) Regedit  
Go under HKEY\_LOCAL\_MACHINE\SOFTWARE\Policies\Mozilla\Firefox  
Add the following Dword (32bits): DisableAppUpdate   
Value of 1 will effectively disable updates while a value of 0 will revert it to normal  
