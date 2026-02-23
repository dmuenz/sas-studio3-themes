# Custom themes for SAS Studio 3

SAS Studio version 3 has a bright white theme with no built-in options to customize it. E.g., there is no dark theme, and you can't change the font of the code editor. This repository provides two custom themes, one dark and one light, than can be easily installed. The themes enhance the appearance of SAS Studio, let you choose any font for the code editor, and provide a few other bonus features. The two themes have been tested in SAS Studio 3.8 and 3.82.

## Installation

To use, first install the **Stylus** browser extension, available for [Chrome, Edge (via Chrome)](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), and [Firefox](https://addons.mozilla.org/firefox/addon/styl-us/). The extension is necessary to load the custom CSS that makes the themes work.

Once the extension is installed, click a link below to install one of the themes. You can install both themes and toggle between them as desired.

📦 [Install *Ignite Dark*](themes/ignite-dark.user.css?raw=true) : a dark theme inspired by the Ignite theme from the SAS Viya versions of SAS Studio.

📦 [Install *Beach Light*](themes/beach-light.user.css?raw=true) : a light theme that's not as glaringly bright as SAS Studio's default theme.

After clicking one of the above links, click the "Install style" button on the top left of your page. You may see a pop-up message saying "Failed to install userstyle", but this message can be safely ignored, and the "Install style" button should now instead say "Style is installed".

## Changing the font of the code editor

To change the font for SAS code, load up SAS Studio. In your browser's toolbar, click the extension icon, then click the "Stylus" extension. A little pop-up window should appear with a list of the themes you have installed. Click the gear icon next to a theme, and a new window will pop up:

  <img src="screenshots/font-customize.png?raw=true" alt="Font pop-up" width="400px" />

In the text box, type the name of any font available on your computer. If you leave the text box blank, SAS Studio will use its default font. (Note that the custom CSS disables ligatures, so ligatures will not be used even if your font has them.) After specifying your font, either click "Close" or just click somewhere outside of the pop-up.

Regarding font *size*, SAS Studio has a built-in method to change it: In SAS Studio, go to Preferences -> Code and Log, then find the "Font size" drop-down menu.

## Screenshots

* Ignite Dark
  
  ![Ignite Dark screenshot](screenshots/ignite-dark.png?raw=true)

* Beach Light
  
  ![Beach Light screenshot](screenshots/beach-light.png?raw=true)

## Bonus features

Both themes provide a few extra features that enhance the functionality of SAS Studio:

1. In the dataset viewer, rows will have alternating background colors (light gray and dark gray), making it easier to visually scan across a row.

2. In several tables throughout SAS Studio, the contents of the tables will become user-selectable and can thus be copied to the clipboard. For example, in the dataset viewer, there is a table that lists the properties of a variable, i.e., label, name, length, etc. SAS Studio blocks you from copying this table, so you could not, e.g., highlight a variable name, copy it to the clipboard, and then paste it into the source code editor. These custom themes let you do exactly that.

3. In the Results tab, when a plot is selected by the user (e.g. when you click-drag your mouse across it) the plot will show that it's highlighted. This makes it more obvious that you can then press Ctrl + C (or Cmd + C) to copy the plot to your clipboard.
