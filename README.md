# flyingwalrus-Map-Expansions
flyingwalrus' Map Expansions - Kavala City Ruins, Therisa Riverlands &amp; Altis Desert 


This composition for Altis was made by flyingwalrus. Thanks to flyingwalrus for sharing this huge work.

Check out the compositions here:

Kavala City Ruins https://steamcommunity.com/sharedfiles/filedetails/?id=3663559026

Therisa Riverlands https://steamcommunity.com/sharedfiles/filedetails/?id=3664043824

Altis Desert https://steamcommunity.com/sharedfiles/filedetails/?id=3624238793

I have just grabbed the code from editor & placed it in initServer.sqf for it to spawn in missions.

# initServer.sqf has all three compositions, ready to go.

Change notes: 

+ Lowered the time the composition takes to load to 0. Change it to 3 or 5 seconds if your server struggles with the loading.
+ Change the timing by doing a copy & replace in notepad++   [0, "Loading simple objects... 0%"] call HYPER_fnc_loadWait; 

5 seconds would be:
```
[5, "Loading simple objects... 0%"] call HYPER_fnc_loadWait; 
```
+ Lowered a couple of floating wrecks in Kavala city.
+ Fixed a minor error in the loading screen text (caused by making this into a script).

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a011d782-ede6-4867-ae62-158e47f24172" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/452ab10c-8a3a-4252-b781-0efb6c1c4b86" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/86f936d6-84f7-4b3e-9163-d8493bc27c12" />
