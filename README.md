# choppingboard-releases

Chopping Board Initialization Process, Beta Phase:

1. Log into choppingboard.app
2. Enter invite code when prompted
3. In the sidebar, under 'Settings', click 'CB Tokens'.
4. Each new machine requires a token to be created. To do this, in the new window, click the blue '+' symbol and create a new CB Token (Leave a note in there to indicate which machine the token is assigned to). You'll need this token later.
5. Install Chopping Board app, launch Chopping Board
6. This step is only necessary on your first machine. Enter your INVITE CODE, then click 'Save'. The input menu will clear.
7. Enter your CB Token, then click 'Save'.

These are only the required steps. This will NOT retrieve your earnings data or emeter data, but WILL track the machine's current status.

To add earnings data (OPTIONAL), note that these instructions assume a Chromium browser:
1. Log into salad.com
2. Enter your developer console (F12 on most browsers)
3. In the developer window, open the 'Application' tab
4. Under the Storage group within the Application tab, open Cookies -> https://salad.com
5. Within the Cookies window, you'll find a cookie labeled 'auth'. ***(DO NOT SHARE THIS TOKEN WITH ANYONE! ALL SALAD FUNCTIONALITY CAN BE ACCESSED THROUGH THIS TOKEN! The Chopping Board app only uses this token to retrieve your earnings, rewards, and profile info. The token is only stored locally. Please note that this functionality is completely optional; if you're not comfortable with the idea of the app holding this token, you do not need to enter it.)*** Copy the token. If the token is NOT present, refresh the page while the developer window is still open.
6. On the Chopping Board app, insert the auth token into the field labelled 'Salad Auth Token' within the Salad tab. Click 'Save' and you should begin receiving Salad earnings information shortly (within ten minutes).

To add emeter (OPTIONAL):
1. Currently, only TPLink emeters operating off of the KP115-type API are supported. If you have one, continue following these instructions.
2. The Chopping Board app can auto-detect TPLink emeters operating on the same network, but it's not a perfect system. Within the 'Emeter' tab on the app, you'll find the list of emeters within the dropdown for the 'Emeter IP' input field. If you're not able to find the emeter, you can have it perform the discovery process again by clicking 'Refresh' next to the input. By clicking an emeter, it will fill most of the fields in the Emeter tab, but it won't automatically set the 'Emeter Type' or the 'Emeter Name' fields. You'll need to fill those, although currently the only valid option for the former is 'TPLink'. The latter, though, is just what name you want to assign it in Chopping Board's webservice. After that, click 'Save' and you should be good to go.
