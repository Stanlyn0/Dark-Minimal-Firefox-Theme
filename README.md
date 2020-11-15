# Dark-Minimal-Firefox-Theme
## A simple minimal css theme for Firefox

![alt text](https://raw.githubusercontent.com/Stanlyn0/Dark-Minimal-Firefox-Theme/main/Images/Full.png)

![alt text](https://raw.githubusercontent.com/Stanlyn0/Dark-Minimal-Firefox-Theme/main/Images/URL%20bar.png)


# Installation

## Open about:config page.

A dialog will warn you, but ignore it, just do it press the I accept the risk! button.

## Search for this:
toolkit.legacyUserProfileCustomizations.stylesheets


Then make sure to enable.

## Go to your Firefox profile.
Linux - $HOME/.mozilla/firefox/XXXXXXX.default-XXXXXX/.
Windows 10 - C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX.
macOS - Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX.

Create a folder and name it chrome, then just copy the userChrome.css to chrome folder.

# Other stuff

## Pinned tabs

### Get a clean layout with pinned tabs 

Imporant:
If you pin a tab that automatically refreshes like some page do then this will happen regardless if the tab is pinned or not. If the title of a pinned tab changes because of a refresh then that tab gets some glowing to notify you.

Note that you can disable pinned tabs from loading automatically when you start Firefox by setting the related pref to true on the about:config page.

    browser.sessionstore.restore_pinned_tabs_on_demand (pinned tabs)(false)
    browser.sessionstore.restore_on_demand (default as set in Options/Preferences -> General)(true)
    browser.sessionstore.restore_hidden_tabs (tabs in other tab groups)(false) 

Note that Tab groups will be gone in Firefox 45.

You can open the about:config page via the location/address bar. You can accept the warning and click "I'll be careful" to continue. 

# Shortcuts

🤖 Cool shortcuts you can use with this theme for a better experience

* Alt You can access to the global menu for an extended options you need
* Alt + Left Arrow You can go Back
* Alt + Right Arrow You can go Forward
* Ctrl + L focuses the URLBar, which is very useful for quick searches and bookmarks usage
* Ctrl + B shows you the Bookmarks
* Ctrl + H shows you the History Bar
* Ctrl + T Opens a new Tab
* Ctrl + W Closes a Tab
* Ctrl + Shift + T Re-opens a tab that you just closed
* Ctrl + R Refresh the page you're on
* Ctrl + Shift + A Quick open for Add-Ons
