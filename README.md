# XIGNCODE3-Heartbeat-Bypass
About:
This code can execute your own code without detection since XIGNCODE hasn't yet loaded. I only tested it on one game with heartbeat and it worked, looking forward to seeing other people's results on other games.

Instructions:
- Go into the XIGNCODE root folder.
- Rename "x3.xem" to "x3.dummy".
- Enter the code you want under the DllMain.
- Compile the DLL with the code provided down bellow under the name "x3.dll".
- Rename "x3.dll" to "x3.xem" and put it into the XIGNCODE root folder.
- Start your game and the code should be executed and not be detected.

Credits:
- K1raCoxx