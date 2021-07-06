devjunk
=======

Small collection of dev junk I find useful and tend to setup on each of my dev machines. Color themes, scripts, config files, etc. Everything requiring a file is grouped into different folders, and some basic info about what's there is listed below. Honestly, this is more of a reference for me than anything else.


## Xcode
Customizations to Xcode, including color themes and key bindings. Currently using the `_Gotham.xccolortheme`

### Installing

1. Copy the contents of the `UserData` folder to `~/Library/Developer/Xcode/UserData/FontAndColorThemes/`. Take care not to overwrite anything you don't plan to.
2. Restart Xcode.
3. Enjoy.


## Terminal
Themes that I like and use on a regular basis. Currently using "The Grid", a theme I created inspired by Tron Legacy.

### Installing themes
1. Open the "Profiles" tab in Terminal Preferences
2. Use the gear icon at the bottom of the profile selector, and select "Import…".
3. Import the theme you'd like, and select it.
4. Done.


## Sublime Text

### Key Bindings
Custom key bindings. Copy to `~/Library/Application Support/Sublime Text 3/Packages/User`

You'll also want to setup the command-line tool: https://www.sublimetext.com/docs/command_line.html#mac

### Packages
Install Package Control: https://packagecontrol.io/

Currently installed packages are included in this repo, but they should be updated after being installed. They should be installed to `~/Library/Application Support/Sublime Text 3/Installed Packages/`


## Git
A basic gitconfig file I use. Copy this file to `~/.gitconfig`, or copy/paste what you want from here into your existing `.gitconfig` file. Basically, it adds:

* Color coding
* A few shortcut aliases
* Setup for using [P4Merge][p4] as your mergetool
* [Sublime Text][subl] as your default editor

[subl]:https://www.sublimetext.com/
[p4]:http://www.perforce.com/product/components/perforce-visual-merge-and-diff-tools


## Finder
QuickLook is pretty handy, but it can be pretty dumb at times, and isn't that useful if it doesn't recognize a file's extension, or if a file doesn't have one. The [QLStephen plugin][ql_1] is great for cases like this. If the file you're trying to take a look at is a plaintext file, you'll get a preview you can actually look at in Finder.

[ql_1]:https://github.com/whomwah/qlstephen
