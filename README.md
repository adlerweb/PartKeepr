[![PartKeepr](https://partkeepr.org/images/partkeepr-banner.png)](https://www.partkeepr.org)

[![JSON-LD enabled](http://json-ld.org/images/json-ld-button-88.png)](http://json-ld.org)
[![Build Status](https://travis-ci.org/partkeepr/PartKeepr.svg?branch=sf2migration)](https://travis-ci.org/partkeepr/PartKeepr)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/a9f5bdce-ac86-4c51-b87d-56fd0f241155/mini.png)](https://insight.sensiolabs.com/projects/a9f5bdce-ac86-4c51-b87d-56fd0f241155)
[![Code Climate](https://codeclimate.com/github/partkeepr/PartKeepr/badges/gpa.svg)](https://codeclimate.com/github/partkeepr/PartKeepr)
[![Test Coverage](https://codeclimate.com/github/partkeepr/PartKeepr/badges/coverage.svg)](https://codeclimate.com/github/partkeepr/PartKeepr/coverage)
[![Dependency Status](https://www.versioneye.com/user/projects/564e098f3d4c250039000001/badge.svg?style=flat)](https://www.versioneye.com/user/projects/564e098f3d4c250039000001)

PartKeepr is an [inventory management software](https://en.wikipedia.org/wiki/Inventory_management_software), primarily
designed for electronic components.

PartKeepr is written in **PHP** and using the [**Symfony2**](http://symfony.com) framework.

Warning
-------

Partkeepr is currently unmaintained and dependend on frameworks and libraries known to be outdated, insecure and a bad idea to run on a webserver. Please DO NOT use PartKeepr on a webserver reachable over the internet.

Requirements
------------

PartKeepr needs:

* PHP between 5.6 and 7.2. Some distributions don't have PHP 5.6 yet, but [provide packages](documentation/installation/php56.md). 
* PHP 7.2 currently needs a small workaround (see https://github.com/partkeepr/PartKeepr/issues/905)
* PHP 7.3 is currently not supported (see https://github.com/partkeepr/PartKeepr/issues/1020)
* A MySQL or PostgreSQL database

Installation
------------

Please read our [setup guide](documentation/Installation.md)

Thanks
------

A very big "thank you" goes out to Georgyo of NYC resistor - although he claimed that he isn't creative, he invented the
name "PartKeepr" which eventually became the project's name.
