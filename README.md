# A guide to install REPO with mods and make your own server (works for windows and linux)
1. This is an all in one guide to install REPO with preinstalled mods , 
REPO is a game made by semiwork https://store.steampowered.com/app/3241660/REPO and i do not claim any credit to it or the mods
2. I have used awc21 's method for the custom server, if u want more information read his guide:
https://github.com/awc21/BepInEx-PhotonRedir
3. The preinstalled mods are :
   - MoreHead https://thunderstore.io/c/repo/p/YMC_MHZ/MoreHead/
   - Wesleys Enemies https://thunderstore.io/c/repo/p/Magic_Wesley/Wesleys_Enemies/
   - MoreUpgrades https://thunderstore.io/c/repo/p/BULLETBOT/MoreUpgrades/
   - Mimic https://thunderstore.io/c/repo/p/eth9n/Mimic/
   - Wesleys Levels https://thunderstore.io/c/repo/p/Magic_Wesley/Wesleys_Levels/

## Instructions
1. Download and install:    
   - Go to https://github.com/dani-dot/Games-for-me/blob/main/repo.txt and open one of the links (doesnt matter which one)
   - Download and extract the "repo1.zip" file in the location u want the game to be
   - Install "r2modman" from the "repo1" folder ( this is a mod manager , .exe for windows and .AppImage for linux )
2. Setting up r2modman:
   - Open "r2modman", search for "REPO" and select it , at "Profile Selection" tab press "Import/Update" , press "From file" and select "moduri_1770737820333.r2z" (this is a modpack) from the "repo1" folder
3. Setting up photonengine:
   - Go to "https://www.photonengine.com" create an account/sign up (its free), go to "dashboard" , press "Create A New App", Select Application Type: "Multiplayer Game" , Select Photon SDK : "Realtime" . Application Name : "GAMESERVER" , press "CREATE"
   - Go to "dashboard" again, there you gonno see your "GAMESERVER", and under "Realtime" theres gonno be an "App ID" ( its gonno look somthing like this 1bdab6bf-5123-4327-98e9-8a4812f7ce10), copy it
     4.Edit photon-redirect.cfg file:
   - Now go to your "repo1" folder > REPO > BepInEx > config > photon-redirect.cfg open with any text editor , there you gonno see "PhotonAppID = PASTE_HERE" , replace PASTE_HERE with your App ID from photonengine.com (its gonno look somthing like this PhotonAppID = 1bdab6bf-5123-4327-98e9-8a4812f7ce10 ), save your file and close it
