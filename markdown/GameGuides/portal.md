![Portal](Images\portal_header.png "Shot by cHota gAbbar")

## Summary

Feature | Supported
--|--
Vanilla Photo Mode | No
Hotsampling | No
DSR | Yes
Custom Aspect Ratios | Yes
Reshade | Yes
Ansel | No
DirectX versions | DirectX 9

## Workflow

### Enable Console

Start the game, open `Settings` and then the `Keyboard` section. Click on `Advanced`, and in the new window, tick the select box that says `Enable Developer Console`. By default, the tilde key is used to toggle the console window.

### Console Commands

* **Server Cheats**: To allow you to use the next command, you need to enable cheats in the server (local). To do so, you can do either of the following:-
  * Open your console and type `sv_cheats 1` to enable cheats (and `sv_cheats 0` to disable them).
  * Open your console and type the following command. This will allow you to enable and disable server cheats by pressing `x`.\*
      `bind x "toggle sv_cheats 0 1"`
    <br/>
* **NoClip**: To freely move (rather levitate) through a level, you need to use the `noclip` command. Keep in mind, you need to have server cheats enabled for this to work. Do either of the following:-
  * Open your console and type `noclip` to toggle it on and off.
  * Open your console and type `bind v "noclip"`. Now, you can press `v` to toggle `noclip` on and off.
  * Using `sv_noclipspeed` you can change the character speed (default is 5.0)
    <br/>
* **HUD and Crosshair**: You can show (or hide) the HUD and crosshair by doing either of the following:-
  * Open your console and type `cl_drawhud 0` to hide the HUD and Crosshair (and `cl_drawhud 1` to show them).
  * Open your console and type the following command. This will allow you to show and hide the HUD and Crosshair by pressing `g`.\*
      `bind g "toggle cl_drawhud 0 1"`
    <br/>
* **ViewModel**: You can show and hide your gun viewmodel by doing either of the following:-
  * Open your console and type `r_drawviewmodel 0` to hide your viewmodel (and `r_drawviewmodel 1` to show it).
  * Open your console and type the following two command. This will allow you to show and hide the gun viewmodel by pressing `b`.\*
      `bind b "toggle r_drawviewmodel 0 1"`
     <br/>
* **TimeScale**: You can make the game speed slower or faster by doing the following:-
  * Open your console and type `host_timescale` followed by any number (default value is 1, anything between 0 and 1 will make the game speed slower and anything above 1 will make the game speed  faster).
  * * Open your console and type `bind n "toggle host_timescale 0.1 1` to toggle between slow or normal gane speeds.
\* *Keep in mind if you have other actions bound to these keys, you may experience unwanted behaviour. Feel free to replace these with keys of your choices.*

### Depth Buffer

To properly set up the Depth Buffer access, follow this [guide](https://framedsc.com/ReshadeGuides/setupreshade.htm#checking-depth-buffer-access). You will most probably need to check the `Copy depth buffer before clear operations` box. You may also have to disable MSAA. Go to `Options` -> `Video` -> `Advanced` and select `Antialiasing mode` as `None`.

## Useful links

* [Portal Wiki](https://theportalwiki.com/wiki/Help:Taking_Screenshots)
* [PC Gaming Wiki](https://www.pcgamingwiki.com/wiki/Portal)
* [Steam guide for Console commands and .cfg files](https://steamcommunity.com/sharedfiles/filedetails/?id=381795162)
