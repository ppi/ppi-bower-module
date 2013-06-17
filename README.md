PPI Bower Module
=================

[@php]:     http://php.net/     "PHP: Hypertext Preprocessor"
[@ppi]:     http://ppi.io/      "PPI Framework - The PHP Meta Framework!"
[@bower]:   http://bower.io/    "A package manager for the web"

[PPI][@ppi] module to manage web assets with [Bower][@bower].

[![Build Status](https://secure.travis-ci.org/ppi/ppi-bower-module.png)](http://travis-ci.org/ppi/ppi-bower-module)

Bower
----

<img src="http://bower.io/img/bower-logo.png" width="200" height="200" />

> Bower is a package manager for the web. It offers a generic, unopinionated solution to the problem of front-end package management, while exposing the package dependency model via an API that can be consumed by a more opinionated build stack. There are no system wide dependencies, no dependencies are shared between different apps, and the dependency tree is flat.

Requirements
------------

* [PHP][@php] 5.3.3 and up
* [PPI Framework 2][@ppi] (2.1.x)

Installation (Composer)
-----------------------

### 0. Install Composer

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

``` bash
curl -s http://getcomposer.org/installer | php
```

### 1. Add this package to your composer.json

```js
{
    "require": {
        "ppi/bower-module": "dev-master"
    }
}
```

Now tell composer to download the module by running the command:

``` bash
$ php composer.phar update ppi/bower-module
```

Composer will install the module to your project's `vendor/ppi` directory.

### 2. Enable the module

Enable this module by editing `app/config/modules.yml`:

``` yml
modules:
    - PPI\BowerModule
    # ...
```

License
-------

This module is licensed under the MIT License. See the [LICENSE file](https://github.com/ppi/ppi-bower-module/blob/master/LICENSE) for details.

Authors
-------

* Vítor Brandão - <vitor@ppi.io> ~ [twitter.com/noiselabs](http://twitter.com/noiselabs) ~ [noiselabs.org](http://noiselabs.org)

See also the list of [contributors](https://github.com/ppi/ppi-bower-module/contributors) who participated in this project.

Submitting bugs and feature requests
------------------------------------

Bugs and feature requests are tracked on [GitHub](https://github.com/ppi/ppi-bower-module/issues).