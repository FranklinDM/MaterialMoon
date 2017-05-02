# Changelog

### 2.8.0
- Partially use CSS variables for parts of the theme
- Fix duplicate learn more link
- Cleaner looking layout for add-ons page and tabs from other devices page
- Use and change the references to SVG for some files
- Restore old prefpane styling (removes the excessive margins and paddings)
- Style about:config
- Materialize most of the controls (button, radio, checkbox, textbox)
- Remove userstyles from tree
- Reduction in theme package file size (-80.5kb)

### 2.7.5
- Findbar styling
- Workaround for private browsing mode tab icons (ex. dark error icon on dark tab)
- Material media controls
- Fix for scrollbar focused state
- Minor adjustments to header search on add-ons and sync tabs pages
- Feed material style
- Resize notification icons on urlbar to 16px
- Minor improvements to new tab page
- Sync dev tools styling with default
- Fix folder icon appearing as a "file" on private browsing mode
- Style image document page proxy favicon
- Toolbar button radius and transition no longer applies to titlebar buttons

- Fixes that applies only for non-composited windows
	- Improve menubar styling (no longer uses ugly text shadow)
	- Address the titlebar -> nav toolbar overlapping when toolbarizer addon is enabled (tradeoff: larger gap when app menu is available)
	- Titlebar border appearance improved
	- (these changes may not apply to other platforms)
	
### 2.7.0
- Support for Home Styler
- Scrollbar styling
- Auto-complete styling
- Add small margin to tabs-toolbar
- Remove white line when tabs are not on top while on private browsing mode
- Remove timing function on toolbar buttons (not really needed)
- Remove communicator/communicator.css
- Materialize some parts of about:newtab
- Fixes for Toolbarize menu button
- Add abouthome to chrome manifest

### 2.6.5
- Fix for invisible forward button
- Removed large margin on tab browser
- Added transition timing function

### 2.6.4
- New icon (again)
- Reworked toolbar icons (much smoother now)
- Browser DevTools styling separated
- Material click animation no lonoger bleeds through tabs
- Preferences are now themed
- Urlbar icons now have the material click animation
- AppMenu popup's margines were adjusted

### 2.6.3
- Ported commits from PMChrome
  - improve menubar appearance on Linux
  - Size caption buttons on Win10 correctly
  - Remove redundant windows-xp queries
  - Remove redundant download indicator styling
- Add light version of the tab close button downloads.css
- New icons (for plugins, feed icons, media, etc.)
- Style the context menu to be more Chrome-like (Windows only)
- Improved lightweight themes appearance

### 2.6.2
- fixes for the "jumpy" toolbar icons on private browsing mode
- minor tweaks to some icons

### 2.6.1
- id change again (you need to uninstall prev. version first)
- material click animation (nav-bar, the circular one)
- fully implemented dark private browsing
- minor tweaks to some icons

### 2.6.0
- changed icon and preview
- material icons, ui, and animations (half-implemented)
- few tweaks and adjustments
- integrated assets from Lootyhoof's unfinished material theme for PMC

### 2.5.0 (continue prev. versioning)
- changed a lot of resources
- id change and name change (the material and the non-material version are different packages)
- added new icon and preview image
- material icons, ui, and many more were put into place

# PMChrome
### 2.4.0
- support PM27's devtools
- drop PM26 support

### 2.3.0
- PM27: add statusbar styling
- PM27: add styling for downloads panel components
- PM27: style devtools
- improve appearance of about:

### 2.2.0
- titlebar colorisation for Windows 10
- use dark window frame detection on Windows 8/10
- refactor media controls for Pale Moon 26.3
- use unified close button icons
- use dark toolbar detection in Pale Moon 26.3 to detect dark system themes
- introduce OS-specific global styling

### 2.1.1
- (PM26) add download location styling

### 2.1.0
- (PM26) add history menu button
- show more icons in history/bookmarks menus

### 2.0.2
- increase favicon padding to ensure favicons are correctly sized

### 2.0.1
- (Win10) round corner removal on certain UI elements
- (Win10) shade window background on Pale Moon 26 builds later than b2

### 2.0.0
- make network error page more closely resemble Chrome
- make invalid SSL error page more closely resemble Chrome
- make private browsing information page more closely resemble Chrome
- replace icon appmenu with caption button-style appmenu
- provide different appmenu styles for Aero, Windows 8+ and non-compositor Windows (e.g. WinXP, Classic, Aero Basic)
- use newer connecting/loading tab icons (uplifted from FXChrome)
- fix floating notification popup
- improve window style for non-compositor Windows to match Chrome
- use new caption buttons on non-compositor Windows to match Chrome
- add new privacy icons (uplifted from FXChrome)

### 1.1.2
- fix vertical toolbar borders

### 1.1.1
- fix toolbar margins when viewing fullscreen video
- change tab bar margin on Windows 10

### 1.1.0
- Pale Moon v26 compatibility
- fix window borders on Windows 10
- use more modern popup style (fixes Linux issues)
- ensure Linux doesn't receive WinXP/WinClassic styles
- Linux: style appmenu
- make about:addons look more like Chrome

### 1.0.6
- fix tab titles when using personas
- fix titlebar spacing (again)

### 1.0.5
- fix newtab quickdial titles

### 1.0.4
- shade verifiedDomain domains

### 1.0.3
- bug fixes

### 1.0.2
- replace appmenu icon with built-in Pale Moon icon

### 1.0.1
- add mixed padlock state
- remove titlebar on tabs-on-top
- fix titlebar spacing

### 1.0.0
- initial release
- add full Pale Moon compatibility