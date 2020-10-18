Minimalistic mod / addon manager that can be used to create sets of addons that will be loaded for specific scenarios.  For example, you can load different sets for different types of gameplay.  This can help to minimize confict, minimize memory use, and minimize UI clutter, each tailored to your current gaming session.  Example variants;

    * Questing
    * PvP
    * Speed Leveling
    * M+
    * Raiding
    * Rares Farming
    * Herb Farming
    * Auctioning

This is a fork of abandoned TooManyAddons addon, initially updated to work with breaking Shadowlands UI background changes.

Directions:

    * There is a new 'addon' button in the game menu that opens up the TooManyAddonsContinued interface.
    * '/tma', '/TMA', '/tmac' or '/TMAC' will also open up the interface, and may be used for any slash command.
    * Create a profile by typing in the profile name and hitting enter, or you can use the Default profile.
    * Select which addons you want to load as part of the profile.
    * When it is time to change addons, select the profile, then click 'Load Profile'


Features that aren't instantly obvious:

    * '/TMAC aProfile' will instantly load that profile. Handy for you macrophiles. Spelling must be exact.
    * The interface can be moved by dragging the 'profile' frame. You have to click on the edge of the frame or a clear spot. 
    * A profile called 'Default' is created at the very first use of TooManyAddons, for your convenience. Feel free to delete it.
    * A profile called 'Always Load These Addons' will always exist. Anything checked in this profile will always load, no matter what. The checked items will appear grey or shiny in other profiles. By default, TooManyAddons will be checked in this profile.
    * Tooltips show you the description, author and status of the addon.
    * Clicking an addon will automatically click all of its dependencies.
    * Profiles from other characters can be added to the current profiles using the 'import profiles' dropdown.
    * The addon can be closed with the 'esc' key.
    * Hold down the Ctrl key to select multiple profiles.  Changes made to addons will affect all selected profiles.
    * Hold down the Shift key when selecting two profiles to select all profiles inbetween.
    * Clicking a sort method that is already clicked will reverse the list.  Eg. Alphabetical from A-Z or, if you click it again, Z-A.
    * The most recently loaded profile(s) appear green.
    * The Reset Position button will return the frames to their default position.  Helpful for multiboxers using mouse broadcasts to synchronize addon sets between accounts.
    
    
*** Previous users of TooManyAddons ***
If you previously used the TooManyAddons addon and you don't want to rebuild your addon configuration, you can follow the instructions below to copy over your settings.  There's a relatively easy way, and a relatively hard way.
 
There's also something to be said about just rebuilding from scratch, only better this time.
 
Remember, if you choose one of the options below, always make a backup up your WTF\ folders, or at least the files you're modifying, when doing things manually in these directories
 
The Easy Way (Recommended)
This saves you a lot of aggravating browsing around for files, but assumes you know how to search folders for a file. Which, isn't hard, if you use the search function in Windows Explorer when you browse to the indicated directory
 
1) Find your install directory. Usually this is; C:\Program Files (x86)\World of Warcraft\_retail_
2) Browse down into WTF\Account from there
Your path is now something like C:\Program Files (x86)\World of Warcraft\_retail_\WTF\Account
3) Search all subdirectories for files named toomanyaddons.lua
4) Rename (or copy) the all of these files to TooManyAddonsContinued.lua
You can ignore toomanyaddons.lua.bak files. Really, save yourself the trouble.
 
(Pro tip; Highlight the file in Windows Explorer, hit F2, paste in TooManyAddonsContinued (using ctrl+v), and hit enter. It should preserve the .lua extension and you'll end up with a file named TooManyAddonsContinued.lua)
 
The Hard Way
1) Find your install directory. Usually this is; C:\Program Files (x86)\World of Warcraft\_retail_
2) Browse down into WTF\Account from there
Your path is now something like C:\Program Files (x86)\World of Warcraft\_retail_\WTF\Account
3) For each account you want to copy;
  A) Browse into that account directory, and into SavedVariables from there
       Your path is now something like; C:\Program Files (x86)\World of Warcraft\_retail_\WTF\Account\<account>\SavedVariables
  B) Rename (or copy) the toomanyaddons.lua file to TooManyAddonsContinued.lua
  C) Go back up one directory
        Your path is now something like; C:\Program Files (x86)\World of Warcraft\_retail_\WTF\Account\<account>
  D) For each realm you want to copy;
        i) Browse into that realm's folder
            Your path is now something like ; C:\Program Files (x86)\World of Warcraft\_retail_\WTF\Account\<account>\<realm>
        ii) For each character you want to copy;
            a) Browse into that character's folder, and then into the SavedVariables subdirectory
                Your path is now something like ; C:\Program Files (x86)\World of Warcraft\_retail_\WTF\Account\<account>\<realm>\<character>\SavedVariables
            b) Rename (or copy) the toomanyaddons.lua file to TooManyAddonsContinued.lua

From <https://www.curseforge.com/wow/addons/toomanyaddonscontinued/pages/tmac-faq> 
