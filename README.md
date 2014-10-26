# Zhongwen-cangjie

Zhongwen-cangjie is a fork of the popular
[Zhongwen Chrome Extension](https://chrome.google.com/webstore/detail/zhongwen-a-chinese-englis/kkmlkkjojmombglmlpbpapmhcaljjkde)
that adds [Cangjie input
method](https://en.wikipedia.org/wiki/Cangjie_input_method) lookup
functionality, letting you know the Cangjie5 code for the Chinese
characters under your cursor.

This extension uses Cangjie5 codes from the
[libcangjie](https://github.com/Cangjians/libcangjie) table.

## Notes

Codes are displayed in sequences separated by a comma (","). For
example, "倉頡" will be shown as "OIAR,GRMBC".

Codes that have multiple input possibilities will have the codes
separated with a forward slash ("/"). For example, "曰" will be shown
as "A/XA".

Codes can be displayed either with the English key (e.g. "ABC") or the Chinese key (e.g. "日月金"). This setting is available in the "Options" page.

## Installation

To install, first clone this repository using `git clone https://github.com/mm--/zhongwen-cangjie`.
Then use the "Load unpacked extension..." option in `chrome://extensions` and select the `zhongwen-cangjie`.
