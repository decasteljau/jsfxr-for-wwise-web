# jsfxr-for-wwise-web

## Overview

jsfxr is a sound effect generator, which uses presets to generate randomized sounds. Generated sound can be imported directory to Wwise without the need to manually save files on hard disk. jsfxr-for-wwise-web runs directly in the web browser.

## To Install and Run

To run, download or clone the complete repository and double-click index.html.

## Importing sounds to Wwise

*Important Note**: jsfxr-for-wwise-web works with Wwise 2017.2.x and up. It uses WAAPI functionality not available in 2017.1.x.

First, ensure WAAPI is enabled in Wwise:
 - menu **Project/Preferences**
 - Check **Enable Wwise Authoring API**
 - Click **OK**
 - Restart Wwise

Then, open a Wwise Project. Note that every imported sound will be in the **Default Work Unit**.

To import sound to Wwise:
 - Start jsfxr
 - Generate a sound
 - Click the **Send to Wwise** button OR press **W**

## About jsfxr

Quick 'n' easy game sound effects generator.
A port of sfxr: http://www.drpetter.se/project_sfxr.html to HTML5.


### Links

Application:  http://github.grumdrig.com/jsfxr/
Source code:  https://github.com/grumdrig/jsfxr/


### Thanks

riffwave.js: http://www.codebase.es/riffwave/
jquery-ui:   http://jqueryui.com/
