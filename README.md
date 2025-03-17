# Portals for Office 365

This project was created to make using multiple accounts with Office 365 easier. There is more details of on how the application works on my website [MyTeamsLab](https://www.myteamslab.com). There is also a video on [YouTube](https://youtu.be/fNosmBF-fzg) that you can check out. 

Go to the [Releases](https://github.com/jamescussen/PortalsReleases/releases) page to download the installer (PortalsInstall-win32-x64.exe).

<p align="center">
  <img src="https://1.bp.blogspot.com/--FKm8g4M_7I/YSd628ym6uI/AAAAAAAABdU/BYyIKi_2Kv0OGLpRtoxoxSnffUXIsZsdQCLcBGAsYHQ/s800/Portals1.20-Light-Dark.png" alt="Portals Image"/>
</p>

## License

Copyright: Copyright (c) 2024, James Cussen All rights reserved.
This is currently a private project.

## Change Log
Version 1.43

- Export and import config file for moving your configs between machines.
- Alphabetized Portals in "Add Portals Page".
- Added button to alphabetically sort buttons on accounts in edit mode.
- Added 'teams rooms pro' button for the Teams Rooms Pro Management Portal (the same as the Managed Rooms button but with a new name)
- Added Copilot Studio portal.
- Added Microsoft Designer portal.
- Added eCDN portal.

Version 1.42: Now with AI!

- Added the Copilot portal
- Added Purview portal
- Updated the Compliance portal to have the new Purview icon
- Added the Purview governance portal
- Added CDX Portal
- Added a dialog when deleting user accounts.
- Reduced button wiggle in edit mode.
  
Version 1.41:
- Upgraded to Electron 24.6.2 / Chromium 112.0.5615.204
- Improvements to passcode - now when a browser window is locked you can click anywhere on the window and it will bring the launcher window to the front of screen.
- Fixed issue with pop up authentication windows
- Added option to auto fullscreen new portal windows - "Open browser windows fullscreen"
- Fixed overflow rendering issue when Teams toast notifications has too many chars in the heading

New Portals:
- Developer Portal for Teams
- Microsoft Fabric
- Microsoft Loop
  

Version 1.40:
- Passcode Feature - The new passcode feature gives you the ability to further secure Portals by allowing you to lock the app (on initial open, when manually locked, when Windows is locked and/or after a specified idle time). The passcode adds an additional layer of security to Portals when you're away from your PC as well as additional encryption on the saved session data. Demo here: https://www.youtube.com/embed/7DTgx2SQC68
- Added Apps Admin portal
- Added Viva insights portal
- Added Microsoft Partner portal


Version 1.3.2:

- Updated to Electron 18.3.15 and Chromium 100.0.4896.160.
- Fixed white screen issue with Outlook portal.
- Moved the sort order setting to the General settings section.
- Other bug fixes and improvements.

Version 1.3.1:
- Added account order sorting - Supports alphabetical order for username/friendly name and domain name based sort order. Sort order by default is not saved, however, the "Save sort order" setting in the Global Preferences allows you to save the sort order across reboots.
- Fixed session expiry error bug that happens in the Azure portals. (After upgrading the error will be seen once more until cookies are saved again).
- Fixed issue with calling toast not popping in Teams.
- Added Entra Portal.
- Added Azure Preview Portal.
- Removed deprecated Protection Portal.
- Other bug fixes and improvements.

Version 1.3.0:
- Upgraded to Electron 17.4.7 and Chromium 98.0.4758.141
- Fixed popup windows in both old and new Exchange Admin Centres!
- Fixed issues with some popup auth windows (e.g Data Source credential auth window in Power Bi).
- Added Portals for Data Explorer, Resource Explorer and Azure Synapse Analytics.
- Easter Egg: Choose your Portals logo :)

Version 1.2.0:
- Added Dark Mode!
- Added search to the Add Portals dialog to make finding portals quicker.
- Added a coloured title bar to the launcher and browser windows to remove ugly window chrome.
- Changed the look of the Add Portal, Preferences and Delete Portal buttons.
- Set a minimum browser window size (400x400).

Version 1.1.2:
  - Only one copy of the app can be running at once. If you reopen it will restore the running app rather than open a second copy.

Version 1.1.1:
  - Added a search function so you can easily filter the accounts list by typing a portion of the email address or friendly name into the search box.
  - Added accordion open and closed state being saved so if you close portals the state will be retained on next load.
  - Fixed issue with accordion open/closed state when moving accounts up and down when in edit state.
  - Fixed issue with Teams notifications not working immediately after the user was added to Portals. Reboot of Portals was previously required but this has now been fixed.
  - Fixed issue with deleting a user that was currently selected as the default template. This caused the template setting to continue reference the deleted user and potentially stop new users from being added. This has been corrected in this version by returning the default user setting back to "None" when the current default user is deleted.


Version 1.1.0:
 - Updated to Electron 8.5.5 and Chromium 80.0.3987.163.
  - Optimisation of cookie handling - Should increase speed of browser window load and stability of sessions.
  - Added the option for selecting an existing user as the portal template for any new users that you add (Global Settings: Default Portal Template). This way you can use your own personal favourite portal layout for new users that you add!
  - Added option to monitor the clipboard for Teams meeting links. If a meeting link is found then Teams windows display a meeting join (video camera) icon. If you click the icon it will join the meeting from that particular window and user.
  - Added a global setting for toast popup timeout so you have more control over how long toasts pop up for (1-60 seconds).
  - Improved speed of closing portal windows. Feels much more snappy now.
  - Fixed issue where typing text into the new user dialog got really slow due to some expensive re-rendering that was happening.
  - Added Friendly Name to the Add User dialog.
  - Added security and compliance portals - Note that the "security" portal will now take you to the new portal and the "protection" portal will take you to the old one. These names have been aligned with Microsoft's naming convention. 
  - Power apps icons have been updated to the pretty new ones.
  - Added new exchange portal to replace the old one which didn't work very well due to it's multi-window UI - The old portal is now called "exchange old" if you still want to access it.
  - Fixed issue with calling and meeting toasts names pushing the close button off the edge of the window.
  - Fixed issue with downloads being shown in the download list multiple times.
  - Fixed issue with using enter key when adding new user causing full reload of app and would not allow you to see error dialogs.
  - Removed power automate admin because it's the same as power platform Admin.
  - Changed the name of device management to endpoint manager to align correctly with Microsoft's latest naming.
  - Added myapps portal.
  - Added cloud app security portal.
  - Added defender for endpoint portal.
  - Added defender for identity portal.
  - Added Teams rooms portal for access to the premium teams rooms portal.
  - Added project portal.
  - Updated Yammer URL to the new site.
  - Added azure status portal.
  - Added connectivity analyzer portal.
  - Improved load speed on Teams portal windows.
  - Optimisations and bug fixes...
  
Version 1.0.5:
  - Global and per account notification sounds have been added! Take your pick from the list of 25 hand crafted notification sounds. If you want all accounts to use the same notification sound then set it in Global Preferences. If you want to have specific sounds for certain accounts you can configure these in Account Preferences. Account preferences are more specific so they will take precedence over the Global Preference setting.
  - Added Friendly Names for accounts. In the account preferences you can now change the name displayed in the launcher window (and in the title bar of browser windows) from the default email address to another name of your choice (ie. a more friendly name).
  - Fixed a bug when closing a browser window that still has a notification toast associated with it.
  
Version 1.0.4:
  - Fixed crashing bug introduced on v1.0.3 for inbound calls.

Version 1.0.3:
  - Fixed an issue where the notifications toast window would steal focus from another window.
  
Version 1.0.2:

  - Changed new window link clicking behavior. If you click on a link that requests a new window or tab it will get opened in a new window. This makes Exchange Admin Centre's window popping addiction workable.
  - Added "Open link in this window" option to right click in browser.

Version 1.0.1: 
  - Added the ability to zoom in and out on web pages in the browser window using the menu and hotkeys.
  

