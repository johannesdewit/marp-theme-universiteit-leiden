# Universiteit Leiden theme for [Marp](https://github.com/marp-team/marp)
Unofficial Leiden University theme for making presentations with [Marp](https://github.com/marp-team/marp) || Officieus Universiteit Leiden thema om presentaties te maken met [Marp](https://github.com/marp-team/marp)

Based on the instructions and presentation templates hosted on the [Leiden University house style page](https://huisstijl.leidenuniv.nl/en/).

![title-slide](/media/title-slide.png)
![slide](/media/slide.png)

## Installing and using the theme
### Using a file download
1. Copy the content of the folder `css/` to your preferred themes folder for Marp.
2. Make sure Marp can find the theme files. If using [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) make sure to [modify the settings so Marp knows where to find your theme](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode#use-custom-theme-css).
3. Declare the theme in the yaml of your markdown file like so: `theme: universiteit_leiden_4:3
` / `theme: universiteit_leiden_16:9` or use the included markdown templates.

N.B. You can also use the included markdown files to preview the functions that are currently supported, to find the classes used for styling different slide types, or you could just use it as a basis to build your presentation from. There are two template files included, one in Dutch and one in English (as indicated by `_nl` or `_en` respectively).

### Using a direct link to this repository.
Another way to use the latest version of the themes is by specifying these paths in your [Marp settings in VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode#use-custom-theme-css):

`https://raw.githubusercontent.com/johannesdewit/marp-theme-universiteit-leiden/main/css/universiteit_leiden_16:9.css`

`https://raw.githubusercontent.com/johannesdewit/marp-theme-universiteit-leiden/main/css/universiteit_leiden_4:3.css`


__Attention:__ Because the 4:3 theme relies on an import of the 16:9 theme, both need to be added to the theme paths!

## License
[MIT License](LICENSE)

The Leiden University logo used in this template remains property of Leiden University and is only rendered by means of a link to [huisstijl.leidenuniv.nl](https://huisstijl.leidenuniv.nl).
