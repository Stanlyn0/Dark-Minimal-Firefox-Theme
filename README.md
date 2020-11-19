# Dark-Minimal-Firefox-Theme
## A simple minimal theme for Firefox

![](https://raw.githubusercontent.com/Stanlyn0/Dark-Minimal-Firefox-Theme/main/Images/Full.png)

### Transparent dropdown
![](https://raw.githubusercontent.com/Stanlyn0/Dark-Minimal-Firefox-Theme/main/Images/Dropdown.png)

### Hide/Show bookmarks
![](https://raw.githubusercontent.com/Stanlyn0/Dark-Minimal-Firefox-Theme/main/Images/Bookmarks.gif)

### Greyscale tabs when not active
![](https://raw.githubusercontent.com/Stanlyn0/Dark-Minimal-Firefox-Theme/main/Images/Tabs.png)

# Installation

### Open about:config page.

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for:

    toolkit.legacyUserProfileCustomizations.stylesheets
    layers.acceleration.force-enabled
    gfx.webrender.all
    gfx.webrender.enabled
    layout.css.backdrop-filter.enabled
    svg.context-properties.content.enabled

Then make sure to *enable* them all!

3. Go to your Firefox profile:
    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 
4. Create a folder and name it **`chrome`** (with lowercase).

5. Then just copy the userChrome.css to chrome folder.

# Other stuff

### Pinned tabs

#### Get a clean layout with pinned tabs 

![](https://raw.githubusercontent.com/Stanlyn0/Dark-Minimal-Firefox-Theme/main/Images/Pinned%20tabs.png)

Imporant:
If you pin a tab that automatically refreshes like some page do then this will happen regardless if the tab is pinned or not. If the title of a pinned tab changes because of a refresh then that tab gets some glowing to notify you.

Note that you can disable pinned tabs from loading automatically when you start Firefox by setting the related pref to true on the about:config page.

    browser.sessionstore.restore_pinned_tabs_on_demand (pinned tabs)(false)
    browser.sessionstore.restore_on_demand (default as set in Options/Preferences -> General)(true)
    browser.sessionstore.restore_hidden_tabs (tabs in other tab groups)(false) 

Note that Tab groups will be gone in Firefox 45.

You can open the about:config page via the location/address bar. You can accept the warning and click "I'll be careful" to continue. 

### Highlight searched text 



Makes the search similar to Opera's where the screen is dim and search results animate.
    
    findbar.modalHighlight -> (true) makes the entire page dim except for highlighted. Seems to use more resources.
    findbar.highlightAll -> (true) just highlights each instance in yellow. Without it, you just find next, and see one at a time.


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
