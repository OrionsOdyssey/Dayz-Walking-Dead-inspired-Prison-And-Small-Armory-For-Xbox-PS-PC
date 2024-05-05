This custom object spawner json file will spawn in a The Walking Dead Style Prison Build with Armory in Chernarus (West of Stary, in the middle of the map coordinates 5746.03 / 7382.83).
Please Note Buildings Are lopsided so that the whole of the inside of the building is usable. This may change in future updates ...

Limited Testing on PC Chernarus Local Server DAYZ Version 1.24 May 2024.
Extended Testing on Xbox Nitrdo Server DAYZ Version 1.24 May 2014.

Created by @OrionCoding. Please report bugs & errors to Orioncodingdayz@gmail.com with screenshots.

TERMS OF USE

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded json files and instructions could break the functioning of your DAYZ server, requiring a reinstall that would wipe all player progress.

If You Are Using these modded files increase regular restarts to prevent server crashing. Hourly recommend if using for long periods of time...

Please thoroughly test your server after applying these files to ensure proper functioning of your server.

I recommend you read all the instructions before proceeding.
✅️✅️✅️✅️✅️✅️✅️✅️

 
Instructions To Spawn Prison.

Click the "Code" button and "Download Zip" on the Github Repository and extract the files on your local PC for access.

(Optional: For More Experienced users I have included the original DayZ Editor Mod file "TWDPRISON.dze" which can be imported into DayZ Editor Mod on PC for customisation.)

GETTING FILE ON TO SERVER CONSOLE...

Step 1 .. Now You Have The File Ensure your DayZ Server has activated the cfggameplay.json.

Step 2.. Go To "General Settings" on your server and tick "Enable cfggameplay.json".

Step 3 .. Now Go To Tools on left side of screen.
Click on File Browser..
Click dayzxb_missions 
Click dayzoffline.chernarusplus

Step 3.. Upload "TWDPRISON.json" from the extracted files to inside the "custom" folder of the mission directory on your server. This file places the Prison and items on your map.

Step 4 ... Go Back to the dayzoffline.chernarusplus
Find the cfggameplay.json file and look for the "objectSpawnersArr" line.

This file tells your server to access your custom file.
Edit it to look like this: 

 "objectSpawnersArr": ["custom/TWDPRISON.json"],

If you already are using custom jsons to spawn items, seperate the files like this:

 "objectSpawnersArr": ["custom/TWDPRISON.json","custom/file1.json","custom/file2.json"].


PC SET UP...

For PC Servers add the following line to your serverDZ.cfg:

 enableCfgGameplayFile = 1;

Note ...On some PC servers, including Nitrado, the serverDZ.cfg is "hidden", so you need to enable "expert mode" in settings,

then go to "expert settings", which is the serverDZ.cfg. Stop the server before making changes this way.)

Upload "TWDPRISON.json" from the extracted files to inside the "custom" folder of the mission directory on your server. This file places the prison and items on your map.

(If you haven't got a "custom" folder, create one.)

Find And Open cfggameplay.json file in the correct mission file for your server and look for the "objectSpawnersArr" line.

 This file tells your server to access your custom file.
 Edit it to look like this: 
"objectSpawnersArr": ["custom/TWDPRISON.json"],

If you already are calling custom jsons to spawn items, seperate the files like this:
"objectSpawnersArr": ["custom/TWDPRISON.json","custom/file1.json","custom/file2.json"],

Save your changes & upload if you need to.

Restart your server and the "Prison" will appear immediatly. Lastly Enjoy..
