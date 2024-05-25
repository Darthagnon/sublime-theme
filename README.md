# sublime-theme
Sublime Text 3 theme for Cudatext.

Tested with **CudaText 1.214.6.6, win64-x86_64-win32, fpc 3.2.3**

## Usage
1. Download this repo as ZIP
2. Drag'n'drop or `File` >> `Open` from CudaText
3. Goto `Options` >> `Themes` >> `Select color theme` and select `sublime`
4. Your CudaText is now coloured like Sublime Text 3

### user.json
To make it look fully like Sublime Text 3, add the following to your `cudatext\settings\user.json`:

```
{
  "ui_tab_angled": true,
  "minimap_show": true,
  "minimap_sel_always": true,
  "minimap_sel_border": false,
  "ui_theme": "sublime",
  "ui_theme_syntax": "sublime"
}
```

## Credits
- [Spotlight: CudaText - A Hot Replacement for Sublime Text, Written in Lazarus](https://lazplanet.gitlab.io/2018/05/spotlight-cudatext-hot-replacement-for.html)
- Based off work by [liberodark](https://github.com/liberodark/sublime-theme)
