# Origin
Based on original design by FeikeB: https://forum.obsidian.md/t/want-a-multi-level-dropdown-menu-inside-your-notes-you-can-i-built-one/40501
Converted to callout by sailKite (https://github.com/sailKiteV) 
Customized by Effaly: https://github.com/Effaly 

# What it does
[](/example.gif)

# How to install 
1. Download the Hoverable Dropdown.css file 
2. Open the Obsidian Vault folder in which you want to use this
3. Open the `.obsidian` folder 
4. Open the `snippets` folder and paste the file in there. If you don't have a `snippets` folder, create it. 
5. Open the Vault in Obsidian. If you have it already open, press `Ctrl + P` and look for `Reload app without saving`
6. Once done, go to Setting -> Appearance and scroll down
7. Toggle Hoverable Dropdown on 

# How to Use 
This is the code from the example above: 
```
>[!navmenu|white|coffee2]
>- Hover
>- Over 
>	- More menus
>- Me
>	- Another menu
>		- Even more menus
>- !!!
>	- As many as you need
```

The line `[!navmenu|white|coffee2]` can be modified.

Instead of `white`, you can add all available **LINK COLORS**. 
Instead of `coffee2` you can use any available **BACKGROUND COLOR**

# Color scheme 
Apart from a neutral white, grey, black palett for links and some pastel backgrounds, the colors were picked from the [extended](https://github.com/mgmeyers/obsidian-style-settings) [AnuPpuccin](https://github.com/AnubisNekhet/AnuPpuccin) themes. 

To find all color options, open the Hoverable Dropdown.css with an editor of your choice. All colors are at the top of the code and documented. 