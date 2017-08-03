RWinOut
=========
Example of IPython extension with a simple dirty hack which solves (workaround :) the R magic output problem on Windows OS. For the error description, check [here](https://bitbucket.org/rpy2/rpy2/issues/125/set_writeconsole-not-working-on-windows).

It can be used as starting point to make much more cool stuff! Check the [official doc](http://ipython.readthedocs.io/en/stable/config/index.html#extending-and-integrating-with-ipython) for more information.

-------

Installation
-------------
It was tested using Windows versions of Python 3.6 and Anaconda 4.4 with the R-essentials package.

Install `RWinOut` directly from the repository using the `%install_ext` magic command:

    %install_ext https://raw.githubusercontent.com/vitorcurtis/RWinOut/master/RWinOut.py

or download it!

#### Dependencies
It requires the Python package *rpy2* 2.8.X and the R package *R.utils*.

Usage
-----
Just load it:

    %load_ext RWinOut

instead of the rpy2.ipython extensions.

License
-------
*RWinOut* is licensed under the MIT license. See the license file for details.
