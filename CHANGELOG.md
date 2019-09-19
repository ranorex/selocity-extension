# Changelog

### 1.3.0 (2019-09-18)
* Added Connect to Ranorex Webtestit option in the context menu of the Ranorex Selocity extension
* Updated instructions on how to connect and use Ranorex Selocity with Ranorex Webtestit
* Added animated gifs on how to connect with Ranorex Webtestit

## 1.2.0 (2019-08-28)
* Fixed Ranorex Selocity banner hight on smaller sizes
* Send selector to Ranorex Webtestit button - the buttons are not disabled if not connected to Ranorex Webtestit, instead, a popup is shown, informing the user about the steps necessary for this action to be completed

## 1.1.1 (2019-05-21)
* Fixed Create New Page Object button and playground input box misalignment when settings button is clicked

## 1.0.1 (2019-04-01)

* Bugfix: page object screenshots could not be created thanks to a bundling oversight

## 1.0.0 (2019-04-01)

* Improved iframe support - Ranorex Selocity can now build and evaluate selectors for elements within iframes, both same-origin and cross-origin, with an indicator that the currently inspected element is in an iframe, and a the possibility to jump to it directly.
* Create Page Object files from Ranorex Selocity - now you can create a new Page Object file in your active Ranorex Webtestit project directly from the Ranorex Selocity extension!

## 0.8.6 (2019-02-26)

* Fixed Send selector from context menu not working issue
* Send selector from the context menu and from Selector Playground sometimes generating the wrong screenshot issue is fixed
* Fixed selector strategy not getting updated in the element panel of Ranorex Webtestit, when the selector is edited and sent back to the application with a different selector strategy


## 0.8.0 (2018-09-06)

* Fix broken selectors in diagnostic mode - fixes a selector sent from Ranorex Webtestit in diagnostic mode 
* Debug mode - Ranorex Selocity indicates debugging mode test run from Ranorex Webtestit
* Send element screenshots - sending elements now sends screenshots of the element to Ranorex Webtestit

## 0.7.0 (2018-08-09)

* Send custom selectors anyway - Ranorex Selocity did not allow to send custom selectors to Ranorex Webtestit, that matched no or more than one element. You will now get the option to bypass this recommendation, and send the selector anyway.
* CSS selectors now use single quotes instead of double quotes
* Send a selector via context-menu to Ranorex Webtestit
* Element sent feedback - After sending an element, a feedback is shown providing info about send element action outcome
* Fixed - Ranorex Selocity tab does not show a scrollbar when height is too small.
* Fixed - disconnect bar overlaps selectors


## 0.6.0 (2018-06-21)

* Hint for chrome internal pages - show hint when trying to track an element on a page without a content script
* Playground for selector evaluation - Selocity now provides a possibility to test generated selectors and to see the matching elements
* Rank selector list after matched elements count - selectors with the lowest number of matches are ranked first
* Option to use LinkText selector(s)

## 0.5.0 (2017-10-23)

* Context menu on selector list to modify and copy a selector
* Custom element tag support in selector generation
* Option to reduce the selector to a minimum nodes, as long as the selector has a unique match (RxPath)
* Option to use partial class name matches on selector (RxPath)

## 0.4.0 (2017-10-16)

* Ignore unsupported pages, like `chrome://` URLs
* Fix element highlighting
