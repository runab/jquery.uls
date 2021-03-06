jQuery Universal Language Selector 
==================================
Universal  Language Selector

[![Build Status](https://secure.travis-ci.org/wikimedia/jquery.uls.png)](http://travis-ci.org/wikimedia/jquery.uls)

This is a [Wikimedia Foundation Internationalization team project](https://www.mediawiki.org/wiki/Project_Milkshake).


![Universal Language Selector](https://upload.wikimedia.org/wikipedia/commons/c/cd/ULS-GeoIP.png "Universal Language Selector")

Quick start
-----------

```bash
git clone https://github.com/wikimedia/jquery.uls.git
```

Documentation
-------------

For documentation and examples please visit the [wiki](https://github.com/wikimedia/jquery.uls/wiki/_pages)


How to build and test jQuery ULS
----------------------------------

First, get a copy of the git repo by running:

```shell
git clone git://github.com/wikimedia/jquery.uls.git
```

Make sure you have `grunt` installed by testing:

```shell
grunt -version
```

If not, run:

```shell
npm install
```

To run tests locally, run `grunt test`. This will run the tests in PhantomJS.

You can also run the tests in a browser by navigating to the `test/` directory, but first run `grunt` to install the submodules.

Coding style
-------------

Please follow [jQuery coding guidelines](http://docs.jquery.com/JQuery_Core_Style_Guidelines)

Versioning
----------

For transparency and insight into the release cycle, and to upgrading easier,
we use the Semantic Versioning guidelines as much as possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit http://semver.org/.
