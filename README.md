# cpiTermIcon

![cpiTermIcon](512.png)

## About
A custom icon for iTerm (or any terminal application, for that matter). A simplified version of the [original iTerm icon](http://www.iterm2.com/images/logo.png), I made this to better match the aesthetic of my [SublimeText icon](http://github.com/colepeters/cpSublimeTextIcon] since they sit side by side in my Dock.

The <code>icns</code> file includes optimised icons for 512, 256, 128, 32 and 16-pixel sizes, including 2x sizes for Retina displays.

## Installation
1. Clone or download this repository's master branch to your computer.
2. In a new Finder window, navigate to your <code>/Applications</code> directory, click on iTerm, and type <code>ctrl-i</code> (or right-click and choose Get Info).
4. Drag the <code>.icns</code> file overtop of the iTerm icon in the Info panel. You will see the icon change. Close the Info panel.
5. Right-click on your iTerm application and choose Show Package Contents.
6. Navigate to <code>/Contents/Resources</code>, and copy the <code>.icns</code> file to this directory (choose Replace when Finder asks).
7. You're done! Open iTerm to see the icon update.

## Notes
This repository includes the following:
- Master <code>.sketch</code> file with each icon size on its own artboard.
- <code>.icns</code> and <code>.png</code> files
- Icon Slate project file (for converting <code>.png</code> files to <code>.icns</code> files

You will need the [Sketch beta](http://www.bohemiancoding.com/sketch/beta/) (v2.3.2 build 5137 or later) to edit the master file. Icon Slate is available for [download on the App Store](https://itunes.apple.com/gb/app/icon-slate/id439697913?mt=12), or you can use another converter of your choice (preferably one that includes options for including 2x assets for Retina displays).