# MingoMongo's "DarkMingo" Theme for Cockatrice
Hi! I'm MingoMongo. Here's a theme I made for Cockatrice born from my love for "Dark Modes", modern graphic design, and my disbelief that Cockatrice's default theme was so... default. I made a lot of compromises making this but I think you'll enjoy it just the same! Thanks to Artemis' MTGO Theme and Ahzmund's Tabletop Theme for giving me a great place to start and lending some resources!

Screenshots: https://imgur.com/a/iOopO1R

## Download
BEFORE DOWNLOADING: Mac users will experience a pattern of 3 lines over the right of the deck editor (https://imgur.com/a/Xus6zi2), this is a known issue and seems to happen with all mac themes. Additionally, all platforms will experience some alignment issues with lists and their headers, this is unfortunately not fixable with the theme due to Cockatrice's code.
There is also one button I cannot change. *sigh.*


I've done all I can to minimize these glitches, but they should be expected.

https://github.com/mingomongo/DarkMingo-Theme-for-Cockatrice/releases

## Installation
Create the directory if it doesn't exist.<br>
* Windows: C:\Users\USERNAME\AppData\Local\Cockatrice\Cockatrice\themes
* Linux: ~/.local/share/Cockatrice/Cockatrice/themes
* Mac OSX: ~/Library/Application Support/Cockatrice/Cockatrice/themes
<br>

## Bugs and stuff for future themers

### Bugs
* Mac: 3 lines appear on top of the deck editor when QWidget's color property is changed
* Space at bottom of theme combobox dropdown and only on that dropdown, doesn't matter
unless you change theme a lot. Seems to be linked to QWidget?
* Headers in shortcut menu change when hovered
* Headers in server replay storage don't color the empty header that should fit the rest of the way
* Mac: QMainWindow::separator images do not appear
* Middle-click card info has the ugly QFrame style with sharp edges, not sure how to change it.

### Unchangeable by CSS
* ChatView's alternating row colors
* QTreeView's "has:children" items are locked for font weight and font size
* QHeaderView's single-side borders and :selected are broken, icons customisation is very limited (???)
* Hyperlink colors
* Scaling the Cockatrice logo with the QTreeView
* UserList's black text
* Server online icon
* Any icon that isn't saved locally
* If two buttons are after the same file you can't make one of them have a different icon.
* The list of "settings" icon container height
* QLineEdit clear button has no property to change it.
* More detailed list: https://github.com/Cockatrice/Cockatrice/issues/3948
