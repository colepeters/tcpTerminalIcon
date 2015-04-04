# tcpTerminalIcon

<img src="./512.png" width="256px" alt="Terminal icon">

## About
A custom icon for any terminal application. Draws influences from Yosemite’s own Terminal.app icon, but uses Solarized colours and a `$_` instead of a `>_` for the prompt. 

The `icns` file includes optimised icons for 512, 256, 128, and 32-pixel, including 2x sizes for Retina displays.

## Installation
1. Clone or download this repository’s master branch to your computer.
2. In a new Finder window, navigate to your `/Applications` directory, click on your Terminal/iTerm/other app, and type `ctrl-i` (or right-click and choose Get Info).
4. Drag the `.icns` file overtop of the application’s icon in the Info panel. You will see the icon change. Close the Info panel.
5. Right-click on your terminal application in Finder and choose `Show Package Contents`.
6. Navigate to `/Contents/Resources`. Locate the application’s existing `.icns` file (there may be several, so be sure to find the one being used for the app’s icon; Terminal.app’s is named `Terminal.icns`, iTerm’s is named `iTerm.icns`, etc); rename `tcpTerminalIcon.icns` to this name, then copy it to this directory (choose Replace when Finder asks).
7. You're done! Open iTerm to see the icon update.
