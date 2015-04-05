# PHP Web Application Bootstrap

[![Latest Stable Version](https://poser.pugx.org/raphhh/php-app-bootstrap/v/stable.svg)](https://packagist.org/packages/raphhh/php-app-bootstrap)
[![Build Status](https://travis-ci.org/Raphhh/php-app-bootstrap.png)](https://travis-ci.org/Raphhh/php-app-bootstrap)
[![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/Raphhh/php-app-bootstrap/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/Raphhh/php-app-bootstrap/)
[![Code Coverage](https://scrutinizer-ci.com/g/Raphhh/php-app-bootstrap/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/Raphhh/php-app-bootstrap/)
[![Total Downloads](https://poser.pugx.org/raphhh/php-app-bootstrap/downloads.svg)](https://packagist.org/packages/raphhh/php-app-bootstrap)
[![Reference Status](https://www.versioneye.com/php/raphhh:php-app-bootstrap/reference_badge.svg?style=flat)](https://www.versioneye.com/php/raphhh:php-app-bootstrap/references)
[![License](https://poser.pugx.org/raphhh/php-app-bootstrap/license.svg)](https://packagist.org/packages/raphhh/php-app-bootstrap)

A bootstrap for a web application in PHP. Don't set, just code!  

## About

This bootstrap will install all the basic files and settings to start a PHP web application. 

This assumes you'll use [Git](http://git-scm.com/) for vcs, 
[Composer](https://getcomposer.org/) for dependencies, 
[PHPUnit](https://phpunit.de/) for testing, 
[Travis](https://travis-ci.org) and [Scrutinizer](https://scrutinizer-ci.com/) for integration servers.

## Files architecture

    ├── public
    |   ├── .htaccess
    |   ├── index.php
    |   └── robots.txt
    ├── src
    |   └── Dummy.php
    ├── tests
    |   └── DummyTest.php
    ├── vendor
    ├── .editorconfig
    ├── .gitattributes
    ├── .gitignore
    ├── .scrutinizer.yml
    ├── .travis.yml
    ├── composer.json
    ├── composer.lock
    ├── LICENSE
    ├── phpunit.xml.dist
    ├── README.md
    └── run

- "public" is the web entry point.
- "src" contains all your PHP code.
- "tests" contains all your PHP tests. See [PHPUnit](https://phpunit.de/) for more information.
- "vendor" contains all your PHP dependencies. See [Composer](https://getcomposer.org/) for more information.

## Installation

### With Samurai (recommended)

Just execute [Samurai](https://github.com/Raphhh/samurai) with 'app' bootstrap.

```
$ samurai new app
```

### With Composer

First, execute [Composer](https://getcomposer.org/) to create your project.

```
$ composer create-project raphhh/php-lib-bootstrap path/to/my/project
```

Go into your project.

```
$ cd path/to/my/project
```

Then, you need to replace composer.json with your specific info.

## Usage

### Launch unit tests

This bootstrap is configured to use [PHPUnit](https://phpunit.de). To run the tests, cd to your project and enter the following command in your console:
```
$ vendor/bin/phpunit
```

### Launch app in the browser

The public entry point of the application is the dir "public". To run the app, cd to your project and enter the following command in your console:

```
$ run
```
This command will launch for you the PHP internal server. Then, open your browser and go to http://localhost:8080/
