# Blackboard

Custom Markdown syntax highlighting theme for the Sublime Text [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing) Package, colors inspired by Textmate's [Blackboard theme](https://github.com/textmate/themes.tmbundle/blob/master/Themes/Blackboard.tmTheme) which i came across on [Haroopad](https://github.com/rhiokim/haroopad) and Monokai Bright theme.

Works with version 2.1.3 of MarkdownEditing.

Installation
---
You should have MardownEditing already installed.

a) Copy the file **MarkdownEditor-Blackboard.tmTheme** to the Packages folder. 

#### Mac OS
You can `Cmd+Shift+G` to quickly go to folder by entering the path. The path is:
    
    ~/Library/Application Support/Sublime Text 3/Packages/User

#### Linux
Download the file, go to Packages folder, create a new folder for MarkdownEditing if one doesn't already exist and copy the file there: 

    ~/.config/sublime-text-3/Packages/User    

b) Edit MarkdownEditing Settings to point to the custom theme.

Open MarkdownEditing settings from the `Preferences > Package Settings > Markdown Editing` menu.

    "color_scheme": "Packages/User/MarkdownEditing/MarkdownEditor-Blackboard.tmTheme",  

![Settings](https://github.com/aamnah/MarkdownEditing-BlackboardTheme/blob/master/screenshots/settings.png)

Alternatively, you can find the default settings files located at:

    Packages/MarkdownEditing/Markdown.sublime-settings         [GitHub flavored Markdown]
    Packages/MarkdownEditing/Markdown (Standard).sublime-settings
    Packages/MarkdownEditing/MultiMarkdown.sublime-settings
    
Screenshots
---
** Some colors (blockquotes) may vary after the latest update.
![Basics](https://github.com/aamnah/MarkdownEditing-BlackboardTheme/blob/master/screenshots/basics.png)
![Blackquotes & Code Blocks](https://github.com/aamnah/MarkdownEditing-BlackboardTheme/blob/master/screenshots/code-blocks.png)
![Image Links and URLs](https://github.com/aamnah/MarkdownEditing-BlackboardTheme/blob/master/screenshots/images-urls.png)
![Reference Links](https://github.com/aamnah/MarkdownEditing-BlackboardTheme/blob/master/screenshots/reference-links.png)
![HTML Syntax Highlighting](https://github.com/aamnah/MarkdownEditing-BlackboardTheme/blob/master/screenshots/html-js.png)

Basic Colors
---
Background #0c1021    
Foreground (text) #fff  
Headings #ff6400  
Code #ffff06  
Bold #fff  
Italic #fff  
Link #43c835  
Anchor Text #8da6ce  
Lists #ffc0c5  
Blockquote #533228  
Selection #253b76  
