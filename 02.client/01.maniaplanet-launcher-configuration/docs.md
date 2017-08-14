---
title: 'Maniaplanet launcher configuration'
process:
    markdown: true
    twig: true
taxonomy:
    category:
        - docs
---

[TOC]

When it is started for the first time, the game automatically detects your computer’s configuration and applies the correct settings. You are, however, able to apply the game’s settings yourself by clicking on the 'Configure' tab of the launcher.

Simple configuration allows you to modify certain settings, including notably the language, the screen resolution and the connection options. In order to access the advanced configuration, click on 'Advanced' at the bottom right of the window (cf. 'Advanced configuration' section).

!!! If you wish to improve the game’s performance, it is advisable to reduce the different graphics settings.


## Simple configuration

![](./En_configuration.png)


**Language:** You are able to choose the language of the Mania<span style="color:#00A8FF">**Planet**</span> client from the languages offered to you.

**Full-screen:** You are able to choose to play in full-screen mode (ticked) or in window mode (not ticked). Full-screen mode displays the game over the whole of your screen, whereas window mode allows you to resize the game’s window at your convenience and access the desktop or other applications.

**3D glasses:** This option allows you to apply the display of the game in stereoscopic 3D, known as 'anaglyphic' 3D, that is to say a display of two superimposed images (with a slight shift), generally red and cyan in colour, each image corresponding to a different eye. In order to benefit from this display, you must have special glasses, with red and cyan filters.

**Profile:** Enables you to specify whether you wish to allow the possibility of hosting several profiles on your Mania<span style="color:#00A8FF">**Planet**</span> client. The different profiles, thus hosted, are displayed when ManiaPlanet is started. The options are the following: Use one single profile / Use several profiles.

**Parental lock:** Require a password in order to play the game.
In order to save your changes, click on the 'Save' button. If you wish to delete your changes, click on the 'Delete' button. This button will close the configuration window.

In order to access the advanced options, click on the 'Advanced' button.

## Advanced configuration

### Display

![](./En_configuration_display.png)

**Customise:** Allows you to apply your own settings to the game’s graphics options instead of the settings automatically chosen based on your graphics card, from the list of settings proposed below and in the different tabs from the 'Advanced settings' window.

**Pre-settings:** Allows you to choose graphics presets from a selection of profiles:

**Any:** Allows you to independently specify the settings that you wish to apply.

**VeryFast:** Select if you wish to have the smoothest and fastest possible gameplay, at the expense of the quality of the graphics.

**Fast:** Select if you wish to have a smooth game, whilst having a higher graphics quality than the **'VeryFast**' mode.

**Nice:** A balanced profile between the game’s performance and graphics quality.

**VeryNice:** Select if you wish to have a high graphics quality, at the expense of the game’s performance.

**Ultra:** Select if you wish to have the highest possible graphics quality, at higher expense of the game’s performance.

**Anti-aliasing:** Allows you to smooth out the aliasing present in the contours of a 3D object (in other words, make the game less pixelated). The higher the anti-aliasing is, the more important the smoothing out of the contours is, and the more attractive the graphics rendering is. Available settings: Any / 2 samples / 4 samples / 6 samples / 8 samples / 16 samples.


>>>>> If you select a high graphics quality, the game will require more resources in order to function (processor, random access memory, graphics card).
>>>>> The custom settings are all available if the 'Any' option is selected in the 'Pre-settings'.


**Shadows:** Allows you to adjust the quality of the shadows of 3D models.

**Shader Quality:** Allows you to adjust the quality of the diffusion of lights, reflections, refractions and shadows.

**Texture Quality:** Allows you to adjust the quality of the textures.

**Max. Filtering:** Allows you to improve the sharpness of distant objects. The higher the value is, the greater the sharpness is.

**Water reflects:** Allows you to adjust the quality of the reflection of the water.

**Car reflects:** Allows you to adjust the quality of the reflections on vehicles and characters.

**PostProcess FXs:** Allows you to adjust the following effects:

***Motion Blur:** Allows you to activate motion blur, the apparent streaking of rapidly moving objects.

***Bloom:** Allows you to activate bloom effects, the scattering of colours from bright and shiny objects.


### Audio

![](./En_configuration_audio.png)

**Activate the sound:** Allows you to activate the sound in the game.

**Audio Device:** Allows you to select the audio device for the game to play sounds through: sound card integrated into the motherboard, internal sound card, external sound card, etc. 

***Settings:** Default / Depending on the device.

**Quality:** Allows you to adjust the quality of the sound.

***Settings:** Low / Normal / High

**Speakers:** Allows you to choose the Windows default configuration.

**Activate EAX:** The EAX, or 'Environmental Audio eXtensions', is an application programming interface which allows you to have a realistic 3D sound reproduction. Activating the EAX allows you to have a better reproduction of the sound in a 3D environment.

**Enable doppler:** Allows you to activate the Doppler effect; sounds in the distance coming toward you will sound higher, while sounds moving away from you will sound lower.
**Allow music to change while racing:** Allows you to download the music offered by an online gaming server which you are playing on and to listen to it.

**Dynamic mix:** Allows the game adjust its sound level dynamically. 


### Network

![](./En_configuration_network.png)


**Server Port:** When a server is created, it allows you to specify the open port on your local machine on which clients are able to log.

**P2P Server Port:** Allows you to specify the open port on the local machine onto which other clients are able to log in order to share data.

**Client Port:** Allows you to specify the open port on the local machine as a client in order to interact with a server. If the value is specified at zero (default value), then the client will itself determine which port to open.

**Number of ports to scan:** Allows you to adjust the number of ports to scan in order to detect the servers present in the LAN (local area network).

**Use Local Address:** When a server is created, it allows you to use the local IP address of the machine as an IP address of the server.

*When the option is ticked, the server which is created will be published with the local IP address of the machine instead of its public IP address.

**Force Server Address:** When a server is created, it allows you to force the IP address of the server into the value specified.

**Blacklist URL:** Allows you to block unwanted URLs.

**Disable Advertising:** Allows you to disable the in-game advertising.

**Send error reports to NADEO:** If this box is ticked, on each occasion that your game shuts down unexpectedly, an error report, also called a 'log', is sent to NADEO's developers so that they are able to correct the problem. It is therefore very important to leave this box ticked so that **NADEO** is able to improve Mania<span style="color:#00A8FF">**Planet**</span>. Error reports are sent automatically thanks to the email sending software installed on your computer (Outlook, Thunderbird, etc.).

**Check internet connection:** Allows you to check whether your Internet connection is active and functional.

**Use Proxy:** Allows you to use a proxy, a server (a computer system or an application) that acts as an intermediary for requests from clients seeking resources from other servers.

**Proxy Login:** Enter the username for the proxy here.

**Proxy Password:** Enter the password for the proxy here.


### Peer to Peer

![](./En_configuration_p2p.png)


**Enable download:** Allows you to download content (skins, horns, avatars, etc.) shared by other players present on the server of which you are playing

**Enable upload:** Allows you to send your content to the other players present on the server of which you are playing.

**Maximum cache size:** Maximum size allocated for the hosting of third-party content on your computer. Click on 'Clean the cache' in order to empty the cache and free up space.

**Enable locators:** Allows you to authorise the downloading and updating of content created by players, directly from a remote server, and not from peer to peer.

**Auto-update at internet connect:** Allows you to check, each time the game is started, whether your version of the game is up-to-date. If this is not enabled, the latest version will be offered to you as a direct download.

**Update locators from url:** Allows you to provide an update of the locators’ content.

**Auto-update from locators:** Allows you to update downloaded content automatically.


### Game

![](./En_configuration_game.png)


**Ignore Player Skins:** If ticked, it allows you to ignore the skins of the other players’ cars/characters in LAN and online servers.

**Skip Rolling Demo:** Allows you to disable the demo mode after a short period of inactivity.

**Cars Quality:** Allows you to adjust the graphical quality of your car/character and the cars/characters of your opponents.

**Cars Particles Quality:** Allows you to adjust the quality of the particles projected by a car/character (sparks, dust, etc.).

**Player shadows:** Allows you to display the shadows that the cars/characters project on the environment.

**Player occlusion:** Allows you to display the shadows projected under your car/character.

**Opponents (Hide Too Close / Always Visible):** The former hides the vehicles that are too close to your car, as the latter displays the vehicles, even those close to your car.

**Opponents Limit Count:** Limits the number of opponents displayed in sight

**Background Quality:** Allows you to adjust the quality of the background (scenery).

**Disable scan cache:** Allows you to disable the scanning of the cache when the game is started.


### Inputs


![](./En_configuration_inputs.png)

**Activate rumble:** Allows you to activate the force feedback on steering wheels with this option, or to activate the vibration feature on gamepads and controllers.

**Freeze Unused Axis:** Allows you to lock the unused axis in order to avoid pressing a wrong button by mistake.

**Exclusive keyboard capture:** Allows you to restrict the use of the Windows® keyboard to the sole use of the game, whilst excluding other applications.


### Others

![](./En_defaults.png)


**Default Values:** Allows you for each tab, or for the window, to restore the default values if you have made a change.

**OK:** Allows you to validate changes made to the 'Advanced settings'. Do not forget to click on 'Save' in the 'Configuration' parent window.

**Delete:** Deletes the changes and closes the 'Advanced settings' window.
