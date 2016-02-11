# smartthings

How it functions now:
-Alarm will play a single alarm file ONCE (I wanted to repeat based on user input duration, but SONOS bug stopped it)
-User configurable (within App)
--Alarm File
--Alarm Volume

What you need to do:
-Log into IDE (graph.api.smartthings.com)
-Go to "My Device Handlers"
-Create New Device Handler
-From Code
-Copy and Paste my code from GitHub in there
-Save
-Publish for Me

The new device is now published. Next steps:
-Go to "My Devices"
-Find the SONOS' that you want to Alarm
-Click on Device
-Click Edit (On device page at bottom)
-Change Type to "Sonos Player with Alarm" (At bottom of list)

The SONOS is now setup to have Alarm capabilities. Not done yet...
-In the SmartThings App find the device(s) that you have changed to "Sonos Player with Alarm"
-Go into the device, you should see a new icon (Alarm Test)
-DON'T try testing it yet, need a few more steps.

If that is there, you were successful at changing the type, still more...

-Edit the device
-You should see two new options
--HTTP path for mp3 file
--Alarm Volume (1-100)
These will have defaults but you can change them to whatever you like. Personally, I took the default file, used Audacity and made a 15 minute loop and I host it locally so that if the internet goes down it can still play.

YOU MUST edit every device that you have changed, only if just to take the defaults. It will not work until you edit and save.

After you have completed these steps, you can select your SONOS as an alarm from SHM or other actions that use Alarm capability.

You can use the Alarm test icon/button under the device to test the functionality. Please note that there can be a delay, nothing I can do about that.
