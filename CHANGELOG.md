# Changelog

## 0.8.0 (2018-09-06)

* Fix broken selectors in diagnostic mode - fixes a selector sent form Webtestit app in diagnostic mode 
* Debug mode - selocity indicates debugging mode test run from Webtestit
* Send element screenshots - sending elements now provides them with screenshots

## 0.7.0 (2018-08-09)

* Send custom selectors anyway - Selocity did not allow to send custom selectors to Webtestit, that matched no or more than one element. You will now get the option to bypass this recommendation, and send the selector anyway.
* CSS selectors now use single quotes instead of double quotes
* Send a selector via context-menu
* Element sent feedback - After sending an element, a feedback is shown providing info about send element action outcome
* Fixed - Selocity tab does not show a scrollbar when hinght is too small.
* Fixed - disconnect bar overlaps selectors


## 0.6.0 (2018-06-21

* Hint for chrome internal pages - show hint when trying to track an element on a page without a content script
* Playground for selector evaluation - Selocity now provides a possibility to test generated selectors and to see the matching    elements
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
