# PHP App Bootstrap

[![Latest Stable Version](https://poser.pugx.org/raphhh/php-app-bootstrap/v/stable.svg)](https://packagist.org/packages/raphhh/php-app-bootstrap)
[![Build Status](https://travis-ci.org/Raphhh/php-app-bootstrap.png)](https://travis-ci.org/Raphhh/php-app-bootstrap)
[![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/Raphhh/php-app-bootstrap/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/Raphhh/php-app-bootstrap/)
[![Code Coverage](https://scrutinizer-ci.com/g/Raphhh/php-app-bootstrap/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/Raphhh/php-app-bootstrap/)
[![Dependency Status](https://www.versioneye.com/user/projects/54062eb9c4c187ff6100006f/badge.svg?style=flat)](https://www.versioneye.com/user/projects/54062eb9c4c187ff6100006f)
[![Total Downloads](https://poser.pugx.org/raphhh/php-app-bootstrap/downloads.svg)](https://packagist.org/packages/raphhh/php-app-bootstrap)
[![Reference Status](https://www.versioneye.com/php/raphhh:php-app-bootstrap/reference_badge.svg?style=flat)](https://www.versioneye.com/php/raphhh:php-app-bootstrap/references)
[![License](https://poser.pugx.org/raphhh/php-app-bootstrap/license.svg)](https://packagist.org/packages/raphhh/php-app-bootstrap)

A bootstrap for a lib in PHP. Don't set, just code!  

This bootstrap will install all the basic files and settings to start a PHP library. 


## Installation

### With Samurai (recommended)

Just execute [Samurai](https://github.com/Raphhh/samurai) with 'app' bootstrap.

```
$ samurai new app
```

### With Composer

First, use [Composer](https://getcomposer.org/) to create your project. (Note that composer will also create all the repositories if they do not exist.)

```
$ composer create-project raphhh/php-app-bootstrap path/to/my/project
```

Go into your project.

```
$ cd path/to/my/project
```

Finally, run PHPUnit to test the installation.

```
$ ./vendor/bin/phpunit
```

If tests are ok, that means you can start your project.
You just need to replace composer.json and README.md with your specific info.

After this customisation, just code.
