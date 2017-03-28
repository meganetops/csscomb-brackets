# CSScomb Brackets plugin

## NOTICE
Currently I have no time to maintain this repository. Feel free to fork. If you want to become the owner just contact me.

Implementation of [CSScomp](https://github.com/csscomb/csscomb.js) for [Brackets](https://github.com/adobe/brackets). Credits to [CSScomb](https://github.com/csscomb) - thanks for the great work.

## Usage
You can use the plugin in three different ways:

1. Contextmenu on the Sidebar

	Using the CSScomb from the sidebar will update the selected file or folder directly

2. File->CSScomb on the Sidebar

	If there is a text selection, only the text selection will be updated. If there is no text selection the selected file or folder gets updated.

3. Editor Contextmenu or `CMD+ALT+c`

	If there is a text selection, only the text selection will be updated. If there is no text selection the selected file or folder gets updated.
	
## Error handling
The statusbar will update the tooltip if something happens. Just hold you mouse a while over the icon in the statusbar.

 
## Installation

In Brackets -> File -> Extension Manager... search for `CSScomb Brackets plugin`

```
// mac
cd /Users/you/Library/Application Support/Brackets/extensions/user/
git clone https://github.com/hano/csscomb-brackets.git
cd csscomb-brackets
npm install
```

## Version

20.03.2014 Version 0.0.1

## Changelog

- 0.0.1
    - First release

## Compatibility

This plugin is developed with [Brackets Sprint 37](https://github.com/adobe/brackets/releases/tag/sprint-37).
