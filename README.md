devjunk
=======

Small collection of dev junk I find useful and tend to setup on each of my dev machines. Color themes, scripts, config files, etc. Everything requiring a file is grouped into different folders, and some basic info about what's there is listed below. Honestly, this is more of a reference for me than anything else.

## Bash
Small little additions to a `.bash_profile` file. Pretty sparse since I just cleaned a lot of old stuff out of it.

### tabname
A small command called `tabname` that allows you to name your tabs in Terminal. Usage is pretty simple:

    tabname "The Name of this tab"

## ColorThemes

### Xcode
Themes that I like and use on a regular basis. Currently using the `_Gotham.xccolortheme`

#### Installing themes
1. Themes should be installed in Xcode's `FontAndColorThemes` folder (`~/Library/Developer/Xcode/UserData/FontAndColorThemes/`).
2. Restart Xcode.
3. Enjoy.


### Terminal
Themes that I like and use on a regular basis. Currently using "The Grid", a theme I created inspired by Tron Legacy.

#### Installing themes
1. Open the "Profiles" tab in Terminal Preferences
2. Use the gear icon at the bottom of the profile selector, and select "Import…".
3. Import the theme you'd like, and select it.
4. Done.

## Git
A basic gitconfig file I use. Copy this file to `~/.gitconfig`, or copy/paste what you want from here into your existing `.gitconfig` file. Basically, it adds:

* Color coding
* A few shortcut aliases
* Setup for using [P4Merge][p4] as your mergetool
* [Atom][atom] as your default editor

[atom]:http://atom.io
[p4]:http://www.perforce.com/product/components/perforce-visual-merge-and-diff-tools


## Finder
QuickLook is pretty handy, but it can be pretty dumb at times, and isn't that useful if it doesn't recognize a file's extension, or if a file doesn't have one. The [QLStephen plugin][ql_1] is great for cases like this. If the file you're trying to take a look at is a plaintext file, you'll get a preview you can actually look at in Finder.

[ql_1]:https://github.com/whomwah/qlstephen


## Xcode Tools

Xcode Snippets are awesome. NSHipster has a [great article][xcode_1] on installing and using them, as well as a repo of useful snippets.

### Plugins
Xcode also has a relatively unknown plugin mechanism. [Alcatraz][xcode_2] exists to make using these plugins easier and more common. Currently I use the following plugins:

* BBUDebuggerTuckAway
* CocoaPods
* DerivedData Exterminator
* OpenInTerminal
* SCXcodeSwitchExpander
* VVDocumenter-Xcode

These plugins can all be found using Alcatraz from within Xcode.

[xcode_1]:http://nshipster.com/xcode-snippets/
[xcode_2]:http://alcatraz.io/
