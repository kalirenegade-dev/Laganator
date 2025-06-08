Laganator Lagswitch by Kalirenegade
Thank you for trying Laganator, the lagswitch software created by Kalirenegade.

CONFIGURATION (servers.json)
The config file is called "servers.json".

You can add an unlimited number of servers.

Each server can have its own drop rate.

You can set a keybind at the top of the file.

A dropdown in the app lets you switch servers quickly.

Recommended Drop Rates:
90: Allows lagging without disconnecting.

100: Will force a disconnection.

TIMER FUNCTION
The timer can be set from 1 to 100 seconds.

Lagging stops when:

The timer runs out,

You press the Stop Lag button,

Or the keybind is pressed.

Tip: If you don't want to use the timer, uncheck the timer option and activate lag as normal.

SERVER DROPDOWN
Dropdown will show:

Server Name

Port Number

Selecting "ALL Servers (0)" will lag all connected devices.

LOCAL AND SHARED DEVICE LAGGING
You have the option to lag local traffic or lag only shared devices connected through internet sharing.

Lag local traffic: This means only your PC's internet is lagged, and it will leave any device connected via internet sharing unaffected.

Lag only shared devices: You can choose to only lag devices connected via internet sharing, leaving your local PC's internet unaffected.

Lag both local and shared devices: By configuring the local setting in the servers.json file to true (enabled), you can lag both your local internet and the connected shared devices.

You can control this by editing the local setting in the configuration file:

local = true: Enables lagging for both your PC's internet and connected shared devices.

local = false: Disables lagging for your local PC internet, affecting only shared devices.

NETWORK SETUP (RECOMMENDED)
For best results:

Use WiFi for internet.

Use Ethernet to connect to your console.

How to Share Your Internet Connection (Windows):
Press the Windows key and open the Control Panel.

Go to Network and Internet.

Click Network and Sharing Center.

On the left, click Change adapter settings.

Right-click your WiFi adapter (used for internet) and click Properties.

Click the Sharing tab.

Check Allow other network users to connect through this computer’s internet connection.

If available, select the Ethernet port connected to your console.

Click OK.

Note: If there’s no dropdown, Windows likely only sees one device and will auto-select it.

TROUBLESHOOTING WINDOWS BUG
Sometimes after restarting your computer, sharing breaks.

To fix:

Go back to Change adapter settings.

Right-click your WiFi adapter → Properties → Sharing tab.

Uncheck Allow other network users to connect... and press OK.

Recheck it again and set it back up.

Enjoy lagging responsibly :)
Additional Notes:
msvcr110.dll Error:
If you run into an error about msvcr110.dll not found, please install the Windows update file attached or download it from Microsoft.