# Fork Description

A fork of ZeroBrane that adds some cosmetic "OS-X-iness".

What has been changed:

- different toolbar, debug, and watch icons
- tabs without gradients
- larger tabs
- panes' background is no longer white

These changes rely on a number of changes in your user.lua config.

Without the fork changes:

![ZeroBrane OS X screenshot before](https://raw.githubusercontent.com/poke1024/ZeroBraneStudio/master/docs/before.png)

With the fork changes:

![ZeroBrane OS X screenshot](https://raw.githubusercontent.com/poke1024/ZeroBraneStudio/master/docs/zerobrane-mac-1.png)

The config changes for the appearance as seen above are as follows:

>bordersize = 8
>
>theme.simpletabart = true
>theme.tabartsize = 20
>theme.panebgcols = {default = {222, 225, 231}}
>
>theme.customicons = {
>	["24/FILE-NEW"] = "theme-osx/material-design-icons/action/1x_ios/ic_note_add_black_24dp",
>	["24/FILE-OPEN"] = "theme-osx/material-design-icons/editor/1x_ios/ic_insert_drive_file_black_24dp",
>	["24/BOOKMARK-TOGGLE"] = "theme-osx/material-design-icons/action/1x_ios/ic_bookmark_outline_black_24dp",
>	["24/FILE-SAVE-ALL"] = "theme-osx/material-design-icons/action/1x_ios/ic_done_all_black_24dp",
>	["24/FILE-SAVE"] = "theme-osx/material-design-icons/action/1x_ios/ic_done_black_24dp",
>	["24/FIND-IN-FILES"] = "theme-osx/material-design-icons/action/1x_ios/ic_find_in_page_black_24dp",
>	["24/FIND-AND-REPLACE"] = "theme-osx/material-design-icons/action/1x_ios/ic_find_replace_black_24dp",
>	["24/FIND"] = "theme-osx/material-design-icons/action/1x_ios/ic_search_black_24dp",
>	["24/DEBUG-CALLSTACK"] = "theme-osx/material-design-icons/editor/1x_ios/ic_format_list_numbered_black_24dp",
>	["24/DIR-SETUP-FILE"] = "theme-osx/material-design-icons/action/1x_ios/ic_tab_unselected_black_24dp",
>	["24/DIR-SETUP"] = "theme-osx/material-design-icons/action/1x_ios/ic_tab_black_24dp",
>	["24/DEBUG-BREAKPOINT-TOGGLE"] = "theme-osx/material-design-icons/av/1x_ios/ic_album_black_24dp",
>	["24/DEBUG-WATCH"] = "theme-osx/material-design-icons/action/1x_ios/ic_receipt_black_24dp",
>	["24/RUN-NOW"] = "theme-osx/material-design-icons/editor/1x_ios/ic_format_indent_increase_black_24dp",
>	
>	["24/DEBUG-START"] = "theme-osx/sekkyumu/PNG/Play Green Button",
>	["24/DEBUG-STOP"] = "theme-osx/sekkyumu/PNG/Stop Red Button",
>	["24/DEBUG-BREAK"] = "theme-osx/sekkyumu/PNG/Pause Blue Button",
>	["24/DEBUG-DETACH"] = "theme-osx/sekkyumu/PNG/Eject Blue Button",
>	["24/RUN"] = "theme-osx/sekkyumu/PNG/Play All",
>	
>	["16/VALUE-CALL"] = "theme-osx/material-design-icons/action/1x_ios/ic_input_black_24dp",
>	["16/VALUE-LOCAL"] = "theme-osx/material-design-icons/action/1x_ios/ic_view_quilt_black_24dp",
>	["16/VALUE-UP"] = "theme-osx/material-design-icons/communication/1x_ios/ic_call_made_black_24dp"
>}

For the icons, the following packages were used:

- https://github.com/google/material-design-icons
- http://sekkyumu.deviantart.com/art/Developpers-Icons-63052312

They should be located inside ZeroBraneStudio/zbstudio/res/theme-mac as "material-design-icons" and "sekkyumu" respectively (see the paths in theme.customicons above).
