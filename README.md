<p align="center">
  <img src="https://github.com/hirschan/Dark-Mode-Wikipedia/blob/master/dark_wiki_icon_large.png" width="150"/>
</p>

<h3 align="center">Quick search for Wikipedia on Firefox</h3>
<p align="center">
Highlight any text from any website, right-click and search on Wikipedia instantly!
<a href="https://addons.mozilla.org/firefox/addon/dark-mode-for-wikipedia/"><strong>Download »</strong></a>
</p>


<p align="center">
<img src="https://img.shields.io/amo/users/dark-mode-for-wikipedia"/> <img src="https://img.shields.io/amo/dw/dark-mode-for-wikipedia"/> <img src="https://img.shields.io/github/issues/hirschan/Dark-Mode-Wikipedia"/>
</p>

# About
Enables quick search - highlight text from any website, right-click and search on Wikipedia.t

## Installation
TBA.

Or:
1. Download the repository
2. Open Firefox and paste in the search field: **about:debugging#/runtime/this-firefox**
3. Press: **Load Temporary Add-on...**
4. Select **manifest.json**

## Accesses
This extension requires **two** accesses:

| Access | Description |
|---|---|
| _Access data for all websites_ | In order to use the [quick search](https://github.com/hirschan/Dark-Mode-Wikipedia/issues/18) function this extension needs to know what text you are highlighting on any given website. Highlighted text is being accessed from `contentScript.js` and sends it as a variable to `background.js` to process. |
| _Access browser tabs_ | `background.js` needs to access browser tabs in order to open a new Wikipedia tab when using the [quick search](https://github.com/hirschan/Dark-Mode-Wikipedia/issues/18) function. |

## Example
<img src ="https://github.com/hirschan/Dark-Mode-Wikipedia/blob/master/screenshots/quick_search.png" width="240">

## Buy me a coffee ☕
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/hirschan)
