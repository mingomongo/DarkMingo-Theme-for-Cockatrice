# MingoMongo's "DarkMingo" Theme for Cockatrice
Hi! I'm MingoMongo. Here's a theme I made for Cockatrice born from my love for "Dark Modes", modern graphic design, and my disbelief that Cockatrice's default theme was so... default. I made a lot of compromises making this but I think you'll enjoy it just the same! Thanks to Artemis' MTGO Theme and Ahzmund's Tabletop Theme for giving me a great place to start and lending some resources! I would also like to apologise and let you know that this theme isn't entirely dark. Unfortunately, the chat, hyperlinks, and some other sections have non-adjustable font colours meaning any dark coloured background obscures important text. :(

Screenshots: https://imgur.com/a/bTXrSui

## Download
**BEFORE DOWNLOADING**: Mac users will experience a pattern of 3 lines over the right of the deck editor (https://imgur.com/a/Xus6zi2), this is a known issue and seems to happen with all mac themes. Additionally, all platforms will experience some alignment issues with lists and their headers, this is unfortunately not fixable with the theme due to Cockatrice's code.
There is also one button I cannot change. *sigh.* I've done all I can to minimize these glitches, but they should be expected.

[Download, read above first!](https://github.com/mingomongo/DarkMingo-Theme-for-Cockatrice/releases)

Also, if you're interested in editing this theme, [here](https://drive.google.com/open?id=1I2JmUKKwJwR0RJyn8lmG499Te9ulrAyH) are the Illustrator and Photoshop files which I made the graphics on.

## Installation
* Download the Source Code zip from above and drag it to the correct directory below. If you haven't installed a theme before the "themes" folder won't exist, so create it!.<br>
  * Windows: C:\Users\USERNAME\AppData\Local\Cockatrice\Cockatrice\themes<br>(if you've never tried to get to AppData before, learn how [here](https://answersdrive.com/where-do-i-find-appdata-in-windows-10-493170))
  * Linux: ~/.local/share/Cockatrice/Cockatrice/themes
  * MacOS: ~/Users/username/Library (this is a hidden folder)/Application Support/Cockatrice/Cockatrice/themes
* After, unzip the folder then drag the first folder out. Essentially, you want the folder order to be: /themes/DarkMingo-Theme-for-Cockatrice-X.X/ then all the contents. If there's another folder inbetween the theme won't work.
* Then go to Settings > Appearance on Cockatrice, then select the theme from the dropdown, then restart Cockatrice to get everything showing how it should.

## Bugs and stuff for future themers

### Bugs
* Mac: 3 lines appear on top of the deck editor when QWidget's color property is changed
* There's a space at the bottom of the theme combobox dropdown and only on that dropdown, it's linked to font size and I haven't figured out how to change QAbstractItemView::item size.
* Headers in shortcut menu change when hovered
* Headers in server replay storage don't color the empty header that should fit the rest of the way
* Mac: QMainWindow::separator images do not appear (the elipses showing you can resize different sections)
* Middle-click card info has the ugly QFrame style with sharp edges, not sure how to change it.

### Unchangeable by CSS
* The glow on active phase buttons and battlefields
* ChatView's alternating row colors
* QTreeView's "has:children" items are locked for font weight and font size
* QHeaderView's single-side borders and :selected are broken, icons customisation is very limited (???)
* Hyperlink colors
* Scaling the Cockatrice logo with the QTreeView
* Server online icon
* Any icon that isn't saved locally
* If two buttons are after the same file you can't make one of them have a different icon.
* The list of "settings" icon container height
* QLineEdit clear button has no property to change it.
* More detailed list: https://github.com/Cockatrice/Cockatrice/issues/3948
