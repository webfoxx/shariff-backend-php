# Changelog

## 6.0.0 TBD

* Dropped support for PHP 5.5.
* Updated composer dependencies. (liayn, core23)
* Removed unused HHVM specific code. (liayn)
* Removed unnecessary files from composer package. (core23)
* Clarified description of domains parameter. (cmb69)

## 5.2.3 2016-04-01

* Fixed backwards compatibility break. (liayn)

## 5.2.2 2016-03-31

* Re-release of 5.2.1 because of wrong tag.

## 5.2.1 2016-03-31

* Fixed handling of Guzzle request options. (liayn)
* Removed non CLI command from composer. (core23)

## 5.2.0 2016-02-24

* Added support for blank domains. (core23)
* Fixed possible error caused by deprecation warning. (core23)

## 5.1.0 2016-02-18

* Added support for multiple domains. (liayn, core23, compeak)
* Improved checking of Facebook configuration. (liayn)

## 5.0.0 2016-02-03

* Added support for PHP 7. (core23, liayn)
* Dropped support for HHVM. (core23, liayn)

## 4.1.0 2016-02-01

* Cleaned up PHPDoc comments. (core23)
* Improved exception handling of Facebook backend. (core23)
* Added logger. (core23)
* Added PHP-CS-Fixer to standardise code format. (core23)

## 4.0.2 2016-01-27

* Fixed array keys not being checked for existence. (liayn, wmtech-1)
* Fixed encoding of urls passed to Facebook. (liayn, hokascha)

## 4.0.1 2016-01-11

* Re-added necessary dependencies.

## 4.0.0 2016-01-07

* Cleaned up dependencies. (core23)
* Dropped support for PHP 5.4. (core23)

## 3.0.1 2015-12-03

* Updated installation instructions.
* Optimized build process.

## 3.0.0 2015-12-02

* Removed build artifacts from repository.
* Cleaned up testing. (liayn)
* Fixed phpUnit dependencies. (liayn)
* Introduced changelog.
