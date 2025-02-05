# Custom themes for SAS Studio 3

SAS Studio version 3 has a bright white theme with no built-in options to customize it. E.g., there is no dark theme. This repository provides CSS (Cascading Style Sheets) files to change the theme, including colors and the font of the code editor. These themes have been tested in SAS Studio 3.8 and 3.82.

## Installation

To use, first install the **Stylus** browser extension, available for [Chrome, Edge (via Chrome)](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), and [Firefox](https://addons.mozilla.org/firefox/addon/styl-us/). Then click a link below to install one of the themes. You can install more than one theme and toggle between them as desired.

📦 [Install *Ignite Dark*](themes/ignite-dark.user.css?raw=true) : a dark theme inspired by the theme of the same name from SAS Enterprise Guide.

📦 [Install *Beach Light*](themes/beach-light.user.css?raw=true) : a light theme that's not as glaringly bright as SAS Studio's default theme.

## Changing the font of the code editor

To change the font for SAS code, load up SAS Studio. In your browser's toolbar, click the extension icon, then click the "Stylus" extension. A little pop-up window should appear with a list of the themes you have installed. Click the gear icon next to a theme, and a new window will pop up:

  <img src="screenshots/font-customize.png?raw=true" alt="Font pop-up" width="400px" />

In the text box, type the name of any font available on your computer. If you leave the text box blank, SAS Studio will use its default font. Note that the custom CSS disables ligatures, so ligatures will not be used even if your font has them. After specifying your font, either click "Close" or just click somewhere outside of the pop-up.

Regarding font *size*, SAS Studio has a built-in method to change it: In SAS Studio, go to Preferences -> Code and Log, then find the "Font size" drop-down menu.

## Screenshots

* Ignite Dark
  
  ![Ignite Dark screenshot](screenshots/ignite-dark.png?raw=true)

* Beach Light
  
  ![Beach Light screenshot](screenshots/beach-light.png?raw=true)
