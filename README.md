tmLilyPond
==========

Enhanced LilyPond syntax highlighter for the [TextMate](http://macromates.com) editor.

**NOTE:** tmLilyPond is a TextMate port of my [SubLilyPond](https://www.github.com/yrammos/SubLilyPond) highlighter for Sublime Text. For screenshots, release history, and other pertinent information, please follow the link above.

### Motivation

TextMate currently ships with Jacob Rus's `LilyPond.tmbundle`, which provides a rather basic LilyPond grammar definition for syntax highlighting. `tmLilyPond` is intended as a substantial upgrade to this highlighter. To prevent conflicts between the two highlighters, it is suggested that you disable the original one as shown in the screenshot below. All other features in Rus's original LilyPond bundle (commands, snippets, etc.) will continue to work normally.

![Screenshot](https://raw.githubusercontent.com/yrammos/tmLilyPond/master/Screenshot.png)

### Installation (for TextMate 2)

    mkdir -p ~/Library/Application\ Support/Avian/Bundles
    cd !$
    git clone git://github.com/yrammos/tmLilyPond.git "tmLilyPond.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

Copyright © 2014 by [Yannis Rammos](http://www.twitter.com/yannisrammos). This work is made available under the terms of the Creative Commons Attribution-NonCommercial 3.0 Unported (CC BY-NC 3.0) license, <http://creativecommons.org/licenses/by-sa/3.0/>.
