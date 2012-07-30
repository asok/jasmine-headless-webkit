_I am looking for a new maintainer for this project. Please contact me via GitHub if you're interested._

# Jasmine Headless WebKit runner

Run your specs at sonic boom speed! No pesky reload button or page rendering slowdowns!

http://johnbintz.github.com/jasmine-headless-webkit/ has the most up-to-date information on using
this project. You can see the source of that site on the gh-pages branch.

## For those who want to hack on the project...

The best way to get everything running that you need for development and testing is
to use Guard:

``` bash
bundle install
bundle exec guard
... build Qt runner ...
... compile CoffeeScript to JS ...
... run RSpec and JHW ...
```

## License

* Copyright (c) 2011 John Bintz
* Original Qt WebKit runner Copyright (c) 2010 Sencha Inc.
* Jasmine JavaScript library Copyright (c) 2008-2011 Pivotal Labs

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

