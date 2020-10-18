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
    
