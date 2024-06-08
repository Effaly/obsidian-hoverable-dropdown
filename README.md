# Origin
Based on original design by FeikeB: https://forum.obsidian.md/t/want-a-multi-level-dropdown-menu-inside-your-notes-you-can-i-built-one/40501
Converted to callout by sailKite (https://github.com/sailKiteV) 
Customized by Effaly: https://github.com/Effaly 

# What it does
![](/example.gif)

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
Apart from a neutral white, grey, black palett for links and some pastel backgrounds, the colors were picked from the [extended](https://github.com/mgmeyers/obsidian-style-settings) [AnuPpuccin](https://github.com/AnubisNekhet/AnuPpuccin) themes. Colors from themes come with their base color and an accent color. 

## Link Colors
#### B/W
- White = `white`
- Light Grey = `light-grey`
- Dark Grey = `dark-grey`
- Black = `black`

#### Pastel
- Pastel Pink = `pastel-pink`
- Pastel Peach = `pastel-peach`
- Pastel Purple 1 = `pastel-purple1`
- Pastel Purple 2 = `pastel-purple2`
- Pastel Green = `pastel-green`
- Pastel Blue = `pastel-blue`
- Pastel Yellow = `pastel-yellow`

## Background Colors
#### Light Backgrounds
- 50% Transparent White = `semi-white`
- Atom 1 = `light-atom1`
- Atom 2 = `light-atom2`
- Everforest 1 = `light-everforest1`
- Everforest 2 = `light-everforest2`
- Gruvbox 1 = `light-gruv1`
- Gruvbox 2 = `light-gruv2`
- Sandy Beaches 1 = `sandy1`
- Sandy Beaches 2 = `sandy2`
- Material Mint 1 = `light-mint1`
- Material Mint 2 = `light-mint2`
- Nord 1 = `light-nord1`
- Nord 2 = `light-nord2`
- Notion 1 = `light-notion1`
- Notion 2 = `light-notion2`
- Luminescence 1 = `lumi1`
- Luminescence 2 = `lumi2`
- Solarized 1 = `light-solar1`
- Solarized 2 = `light-solar2`

#### Dark Backgrounds
- 50 % Transperant Black = `semi-back`
- Amoled Dark 1 = `amoled1`
- Amoled Dark 2 = `amoled2`
- Atom 1 = `dark-atom1`
- Atom 2 = `dark-atom2`
- Biscuit 1 = `biscuit1`
- Biscuit 2 = `biscuit2`
- Coffee 1 = `coffee1`
- Coffee 2 = `coffee2`
- Dark (Generic) 1 = `dark1`
- Dark (Generic) 2 = `dark2`
- Dracula 1 = `dracula1`
- Dracula 2 = `dracula2`
- Everforest 1 = `dark-everforest1`
- Everforest 2 = `dark-everforest2`
- Flexoki 1 = `flexoki1` 
- Flexoki 2 = `flexoki2`
- Gruvbox 1 = `dark-gruv1` 
- Gruvbox 2 = `dark-gruv2`
- Kanagawa 1 = `kana1`
- Kanagawa 2 = `kana2`
- Material Mint 1 = `dark-mint1`
- Material Mint 2 = `dark-mint2`
- Nord 1 = `dark-nord1` 
- Nord 2 = `dark-nord2`
- Notion 1 = `dark-notion1` 
- Notion 2 = `dark-notion2`
- Nord Dark (custom palette) 1 = `nord-dark1`
- Nord Dark (custom palette) 2 = `nord-dark2`
- Rosepine 1 = `rose1`
- Rosepine 2 = `rose2`
- Rosebox 1 = `rosebox1`
- Rosebox 2 = `rosebox2`
- Royal Valvet 1 = `royal1`
- Royal Valvet 2 = `royal2`
- Solarized 1 = `dark-solar1`
- Solarized 1 = `dark-solar2`
