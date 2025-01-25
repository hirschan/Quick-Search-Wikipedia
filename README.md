<p align="center">
  <img src="https://github.com/hirschan/Quick-Search-Wikipedia/blob/master/quick_search_icon_large.png" width="150"/>
</p>

<h3 align="center">Quick search for Wikipedia on Firefox</h3>
<p align="center">
Makes your life easier - highlight text, right-click and search on Wikipedia.
  <a href="https://addons.mozilla.org/en-US/firefox/addon/quick-search-for-wikipedia/"><strong>Download »</strong></a>
</p>


<p align="center">
<img src="https://img.shields.io/amo/users/quick-search-for-wikipedia"/>
<img src="https://img.shields.io/amo/dw/quick-search-for-wikipedia"/>
<img src="https://img.shields.io/github/issues/hirschan/Quick-Search-Wikipedia"/>
</p>

# About
Highlight text from any website, right-click and search on Wikipedia instantly.

## Installation
Can be added as an extension on [Firefox here](https://addons.mozilla.org/en-US/firefox/addon/quick-search-for-wikipedia/).

Or:
1. Download the repository
2. Open Firefox and paste in the search field: **about:debugging#/runtime/this-firefox**
3. Press: **Load Temporary Add-on...**
4. Select **manifest.json**

## Example
<img src ="https://github.com/hirschan/Quick-Search-Wikipedia/blob/master/screenshots/quick_search.png" width="350">

## Accesses
This extension requires **two** accesses:

| Access | Description |
|---|---|
| _Access data for all websites_ | In order to use the quick search function this extension needs to know what text you are highlighting on any given website. Highlighted text is being accessed from `contentScript.js` and sends it as a variable to `background.js` to process. |
| _Access browser tabs_ | `background.js` needs to access browser tabs in order to open a new Wikipedia tab when using the quick search function. |

## Buy me a coffee ☕
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/hirschan)
