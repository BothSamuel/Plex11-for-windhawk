# Plex11-for-windhawk-start-menu-and-taskbar
Theme based on the Plex style of Windows Longhorn and the concept by /Mann53 on reddit

Theme for the Windhawk Windows 11 Start Menu Styler and Windows 11 Start Menu Styler mods.

Original concept : <a href="https://www.reddit.com/r/Windows11/comments/1i7khdf/windows_11_start_menu_longhornplex_style/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button">Mann53 on Windows 11 Reddit</a>\

<img width="1920" height="1080" alt="Captura de pantalla (3)" src="https://github.com/user-attachments/assets/2d33b245-f3b0-4eb6-9a08-d7661e0152cf" />

# Software Needed
Windhawk : <a href="https://windhawk.net/">Link</a>\

## Windhawk
### Mods needed:
- Windows 11 Start Menu Styler
- Windows 11 Taskbar Styler

## Install theme 
- Copy the contents of the Start menu mod to the "Advanced" tab in the Windows 11 Start menu styler mod.
- Create a folder called Start in the root directory (C:\Start)
- Copy the files start_bg and start_bt into this folder. start_bg is the background file used for the start menu (tested at 1080p resolution at 100% scaling, I don't guarantee it will work well at other resolutions or scaling).
- Copy the content of tge taskbar mod to the "Advanced" tab in the Windows 11 Taskbar styler mod.

## Atention
  If you use resolutions other than 1080p and 100% scaling, the folder shortcuts/power button and the recommended section may not display correctly. In this case, you can adjust the margin of the following elements:
  
  ### Target
  - `StartDocked.PowerOptionsView` (To adjust the position of the power button)
  - `StartDocked.SearchBoxToggleButton#StartMenuSearchBox` (To adjust the position of the search bar)
  - `StartDocked.UserTileView` (To adjust the position of the photo and username)
  - `StartDocked.AppListView#NavigationPanePlacesListView` (To adjust the position of Start menu shortcuts (File Explorer, Downloads, Videos, etc.), keep in mind that you need to modify two `margin` values ​​with the exact same value, one positive and one negative. If you're using a touchscreen device, you might experience problems with Start menu gestures if you only modify one value.)
  - `Windows.UI.Xaml.Controls.Grid#UndockedRoot`(To adjust the position of the applications pinned to the start menu and show the recommended section, since in some scales this may disappear.)
  
Wallpaper : <a href="https://wallpapersden.com/hd-desert-photography-2022-wallpaper/">Link</a>\
