Card Generator
==============

Business card generator for the Mozilla community


## How to add new card template ##
* Fork yourselves a copy of this repo and edit there.
* Add a normal HTML file of the card design to `/templates` directory and of the back side of the card to `/templates/back` directory.
* In the template HTML, add the attribute `contenteditable` for all text you want to make editable.
* Add any images required in template file to `templates/images` and use their absolute path in the html (absoute path starting with `http://cards.mozillakerala.org/templates/images/`)
* The dimensions of the card template should be 388x227px
* Commit and push to your own fork, and open a pull request.

_(Or if that's too much for you, you can just send the template design to hello@mozillakerala.org)_

## Dependencies ##
* PHP5 with GD library

## Contributors ##
* [jsx](https://github.com/riverspirit)
* [shine](https://github.com/shinescodes)
* [Tanay](https://github.com/tanay1337)

## License ##

#### MIT License (MIT) ####

_Copyright (c) 2013 jsx and other contributors_

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
