PPI Bower Module
=================

[@php]:     http://php.net/     "PHP: Hypertext Preprocessor"
[@ppi]:     http://ppi.io/      "PPI Framework - The PHP Meta Framework!"
[@bower]:   http://bower.io/    "A package manager for the web"

[PPI][@ppi] module to manage web assets with [Bower][@bower].

<!--- [![Build Status](https://secure.travis-ci.org/ppi/ppi-bower-module.png)](http://travis-ci.org/ppi/ppi-bower-module) -->

Bower
-----

<img src="http://bower.io/img/bower-logo.png" width="128" height="128" />

> Bower is a package manager for the web. It offers a generic, unopinionated solution to the problem of front-end package management, while exposing the package dependency model via an API that can be consumed by a more opinionated build stack. There are no system wide dependencies, no dependencies are shared between different apps, and the dependency tree is flat.

PPI
----

<img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Ppi-framework-logo.png" />

> PPI is an open source php meta-framework. It has taken the good bits from Symfony2, ZendFramework2 & Doctrine2 and combined them together to create a solid and very easy web application framework. It can be considered the boilerplate of PHP frameworks.

Requirements
------------

* [PHP][@php] 5.3.3 and up
* [PPI Framework 2][@ppi] (2.1.x)
* [Node.js](http://nodejs.org/) and [Bower][@bower]

Installation
------------

### 1. Install Node.js and Bower

If **Node.js** is not yet installed follow the instructions in [Installing Node.js via package manager](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager) for your OS and distro. **Npm** is packaged along with Node.

**Bower** depends on Node and npm. It's installed globally using npm:

```bash
npm install -g bower
```

### 2. Install Composer

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

``` bash
curl -s http://getcomposer.org/installer | php
```

### 3. Add ppi/bower-module to your composer.json and install it

``` bash
$ php composer.phar require ppi/bower-module dev-master
```

Composer will install the module to your project's `vendor/ppi` directory.

### 4. Enable the module

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