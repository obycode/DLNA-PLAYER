# DLNA-PLAYER 
Generic DLNA Player to Smartthings v 1.9.0

Its necessary to update MediaRenderer Connect and Dlna-Player
You must uninstall all your MediaRenderes and install again after update.


**Installing The MediaRenderer Connect**



Open SmartThings IDE in your web browser and log into your account.

Click on the "My Smart Apps" section in the navigation bar.

On your SmartApps page, click on the "+ New SmartApp" button on the right.

On the "New SmartApp" page, Select the Tab "From Code" , Copy the MediaRenderer_Connect source code from GitHub and paste it into the IDE editor window.

Click the blue "Create" button at the bottom of the page. An IDE editor window containing device handler template should now open.

Click the blue "Save" button above the editor window.

Click the "Publish" button next to it and select "For Me". You have now self-published your SmartApp.



**Installing The Device Type**


Open SmartThings IDE in your web browser and log into your account.

Click on the "My Device Types" section in the navigation bar.

On your Device Types page, click on the "+ New Device Type" button on the right.

On the "New Device Type" page, Select the Tab "From Code" , Copy the MediaRenderer_Player source code from GitHub and paste it into the IDE editor window.

Click the blue "Create" button at the bottom of the page. An IDE editor window containing device handler template should now open.

Click the blue "Save" button above the editor window.

Click the "Publish" button next to it and select "For Me". You have now self-published your SmartApp.


**Searching the Media Renderers**


Open the SmartThings app in your smartphone.

Select the (+) icon to install new things

Go to My Apps section and select MediaRenderer Connect

The MediaRenderer Connect will start to search Your players.

Once the app will show the quantity of media renderers found, activate all the media renderers found and finish the proccess pressing the "Done Button" in both pages.

Get back to main window and you should have the new players in your things section, refresh the page if no players appears.

Revision History
----------------
**Version 1.9.0
* No device present detection
* Its necesary to update the conecctor too and uninstall,reinstall the players, if you do not have software devices its not necesary to update, but recommended.

**Version 1.8.0
excluded by bugs

**Version 1.7.0
* Foobar and Software device autocorrect added
* Its necesary to update the conecctor too and uninstall,reinstall the players, if you do not have software devices its not necesary to update, but recommended.

**Version 1.6.0
* Speech Synthesis Capability added

**Version 1.5.6 
* Fix TTS delay 
* Implemented Msg only when playing and Msg only when no playing
* Several minor fixes
* Fix Resume in control point list (No container)
* Fix Volume Refresh in software MediaRenderers
* Better play event
* Prefix P.L. in container when last song list is display in music apps 
* Prefix Unavailable in control point manage song when last song list is display in music apps 

**Version 1.5.0 
* Improved Track resume and Container resume

**Version 1.4.0 
* Implemented message in progress

**Version 1.3.0 
* Implemented new Delay before message (Some slow MR need more time to load an external http file)

**Version 1.2.0 
* Implemented new Delay between actions (Some slow MR need more time between actions)

**Version 1.1.0 
* Implemented new Do not Disturb state to avoid messages 

**Version 1.0.1 
* Removed Play test button

**Version 1.0.0. Released 2015-02-13**
* First public release.

