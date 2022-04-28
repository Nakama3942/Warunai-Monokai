[![template](https://img.shields.io/badge/Repository-template-darkred)](https://github.com/Nakama3942/template_rep)
[![GitHub license](https://img.shields.io/github/license/Nakama3942/Warunai-Monokai?color=silver&style=flat-square)](https://github.com/Nakama3942/Warunai-Monokai/blob/main/LICENSE)

[![CHANGELOG](https://img.shields.io/badge/here-CHANGELOG-yellow)](https://github.com/Nakama3942/Warunai-Monokai/blob/main/CHANGELOG.md)
[![CONTRIBUTING](https://img.shields.io/badge/here-CONTRIBUTING-indigo)](https://github.com/Nakama3942/Warunai-Monokai/blob/main/CONTRIBUTING.md)
[![CODE_OF_CONDUCT](https://img.shields.io/badge/here-CODE_OF_CONDUCT-darkgreen)](https://github.com/Nakama3942/Warunai-Monokai/blob/main/CODE_OF_CONDUCT.md)
[![PULL_REQUEST_TEMPLATE](https://img.shields.io/badge/here-PULL_REQUEST_TEMPLATE-orange)](https://github.com/Nakama3942/Warunai-Monokai/blob/main/.github/PULL_REQUEST_TEMPLATE.md)

# 悪ないものかい
## Overview
"Isn't it bad?" (jp.: 悪ないものかい [warunai monokai]) - I wanted to invent my own name so that the second word would remain "Monokai". I do not know where the original author got this word (from Japanese or not), but I think the name came out not bad :D.

<p align="center">
	<image
	       src="https://github.com/Nakama3942/Warunai-Monokai/blob/main/image/WarunaiMonokai_Inheritance.png"
	       alt="Family tree"
	       caption="Monokai & One Dark -> One Monokai -> Warunai Monokai">
</p>

## Originals
[Monokai](https://github.com/bfrg/qtcreator-monokai)
[One Dark](https://gitlab.com/iohanaan/qtcreator-onedark)
[One Monokai](https://github.com/jakoch/one_monokai_theme_for_qtcreator)

## Installation

### Theme
- Find your QT Creator installation folder. That's were you install the application theme, because it's a non-configurable application ressource. If you installed Creator together with Qt it's: `~/Qt/Tools/QtCreator/share/qtcreator/`

- Install the application color-theme (`*.creatortheme`) to `QtCreator/share/qtcreator/themes/`
	- Windows: `xcopy -Y one-monokai.creatortheme C:\Qt\Tools\QtCreator\share\qtcreator\themes\`
	- Linux | Mac: `cp one-monokai.creatortheme ~/Qt/Tools/QtCreator/share/qtcreator/themes`

### Syntax-Highlighting Color-Scheme
- Find your Qt Creator config folder. That's were you install the syntax color-scheme, because you want it to be editable.
- Install the syntax-highlighting color-scheme (`*.xml`) to `qtcreator\styles`
	- Windows: `xcopy -Y one-monokai.xml "%APPDATA%\QtProject\qtcreator\styles\"`
	- Linux | Mac: `cp one-monokai.xml ~/.config/QtProject/qtcreator/styles/`

### IDE Configuration > Select Theme
- Go to `Qt Creator -> Tools -> Options > Environment`, then in the Tab `Interface` select `Theme`: `One Monokai`

## Screenshots
<p align="center">
	<image
	       src="https://github.com/Nakama3942/Warunai-Monokai/blob/main/image/Screenshot_2.png"
	       alt="Display ad file"
	       caption="Header">
	<image
	       src="https://github.com/Nakama3942/Warunai-Monokai/blob/main/image/Screenshot_3.png"
	       alt="Display the definition file"
	       caption="Source">
</p>

## Troubleshooting
If you have problems using the theme or there are suggestions for setting colors - I invite you [here](https://github.com/Nakama3942/Warunai-Monokai/blob/main/CONTRIBUTING.md).

## Authors
<table align="center">
	<tr>
		<td align="center"><a href="https://github.com/Nakama3942"><img src="https://avatars.githubusercontent.com/u/73797846?s=400&u=a9b7688ac521d739825d7003a5bd599aab74cb76&v=4" width="350px;" alt=""/><br /><b>Kalynovsky Valentin</b></a><br />"Ideological inspirer and Author"</td>
		<!--<td></td>-->
	</tr>
	<!--
	<tr>
		<td></td>
		<td></td>
	</tr>
	-->
</table>
