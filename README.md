# [JoomLavel-documentation](https://joomlavel.io/)

## Why this platform?

We noticed that many web developers start a projects on Joomla (one of tht most popular CMS), but then reach limitations of this platform. Our concept is to build platform to easy enhance Joomla with Laravel, which allows to do a lot more.
We offer a system that has no such limitations, is universal and even allows to integrate already existing software or internet services.

## Overview
### [JoomLavel/Connect](https://github.com/JoomLavel/connect)
Component Generator is based on templates. It does require [JoomLavel/RAD](https://github.com/JoomLavel/rad) and [JoomLavel/templates](https://github.com/JoomLavel/templates). JL/Connect can be managed by a command line tool in the root directory called *JoomLavel*

### JoomLavel/JoomlaDbLink
This is a [laravel eloquent](https://laravel.com/docs/8.x/eloquent) modelset for a joomla DB. It can be managed by a command line tool in the root directory called *JoomLavel*

`foo@bar:/$ composer create-project --prefer-dist laravel/lumen blog`

`foo@bar:~$ cd blog`

`foo@bar:~$ composer require joomlavel/joomladblink`

`foo@bar:~$ php JoomLavel publish:all`

Do not forget to add the DB_PREFIX of your Joomlaa DB in the .env file

`foo@bar:~$ echo 'DB_PREFIX=mx_' >> .env`


### JoomLavel/JoomlaAdapter
Laravel API for Joomla Views

### JoomLavel/LaravelAdapter
Joomla Component for Laravel Views

## want more ...

### [scoping document](https://github.com/JoomLavel/documentation/blob/master/scoping_document.md)

documentation of JoomLavel ecosystem, including use cases, user journey, tutorials will follow
