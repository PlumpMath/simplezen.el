# simplezen.el [![Build Status](https://secure.travis-ci.org/magnars/simplezen.el.png)](http://travis-ci.org/magnars/simplezen.el)

A simple subset of zencoding-mode for Emacs.

## Installation

I highly recommended installing simplezen through elpa.

It's available on [marmalade](http://marmalade-repo.org/) and
[melpa](http://melpa.milkbox.net/):

    M-x package-install simplezen

You can also install the dependencies on your own, and just dump
simplezen in your path somewhere:

 - <a href="https://github.com/magnars/s.el">s.el</a>
 - <a href="https://github.com/magnars/dash.el">dash.el</a>

## Contribute

Yes, please do. :-)

All changes must be accompanied by feature tests, or I might break it later.
They are written in [Ecukes](http://ecukes.info), a Cucumber for Emacs.

You'll find the repo at:

    https://github.com/magnars/simplezen.el

To fetch the test dependencies, install
[carton](https://github.com/rejeep/carton) if you haven't already,
then:

    $ cd /path/to/simplezen
    $ carton

Run the tests with:

    $ ./run-tests.sh

## License

Copyright (C) 2013 Magnar Sveen

Author: Magnar Sveen <magnars@gmail.com>

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
