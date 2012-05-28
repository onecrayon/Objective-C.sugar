# Objective-C.sugar

This Sugar adds simple syntax highlighting for Objective-C .h and .m files to [Espresso](http://macrabbit.com/espresso/).

The Sugar is currently meant to help more with viewing Objective-C files than editing them. When I need to make any substantive edits I prefer to use Xcode, AppCode, or some other IDE with intelligent auto-completion and include parsing. I wrote Objective-C.sugar primarly as a way to make quickly referencing header files and so forth more pleasurable, because the aforementioned IDEs all take forever to launch.

## Installation

The best way to install Objective-C.sugar is directly from GitHub:

    cd ~/Library/Application\ Support/Espresso/Sugars
    git clone git://github.com/onecrayon/Objective-C.sugar.git

Relaunch Espresso, and Objective-C will be available in your **View&rarr;Languages** menu. You can then update the Sugar when necessary by running the following command:

    cd ~/Library/Application\ Support/Espresso/Sugars/Objective-C.sugar
    git pull

Alternately, you can [download the Sugar](https://github.com/onecrayon/Objective-C.sugar/zipball/master), decompress it, rename the resulting folder `Objective-C.sugar`, and double click to install it.

## MIT License 

Copyright (c) 2012 Ian Beck

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
