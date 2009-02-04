Ruby Refactorings for TextMate
------------------------------

Common refactorings for Ruby code, written in Ruby. This project aims 
to be integrated with several editors (mainly TextMate), to provide 
simple refactorings, such as:

*  extract method

*  extract Class

*  extract Module

*  rename using ack

*  move using ack

Requirements
============

*  [ParseTree](http://parsetree.rubyforge.org)

*  modified ruby_parser, from [fabiokung's github repository](http://github.com/fabiokung/ruby_parser/tree/master)

*  modified sexp_processor, from [fabiokung's github repository](http://github.com/fabiokung/sexp_processor/tree/master)

* [rfactor](http://github.com/fabiokung/rfactor/tree/master)

Installation
============

To install via Git:

    gem install ParseTree
    gem install fabiokung-sexp_processor -s http://gems.github.com
    gem install fabiokung-ruby_parser -s http://gems.github.com
    gem install fabiokung-rfactor -s http://gems.github.com
    
    cd ~/"Library/Application Support/TextMate/Bundles/"
    git clone git://github.com/fabiokung/rfactor-tmbundle.git "Ruby Refactoring.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

Source can be viewed or forked via GitHub: [http://github.com/fabiokung/rfactor-tmbundle/tree/master](http://github.com/fabiokung/rfactor-tmbundle/tree/master)

License
=======

(The MIT License)

Copyright (c) 2008 Fabio Kung [fabio.kung@gmail.com](mailto:fabio.kung@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.