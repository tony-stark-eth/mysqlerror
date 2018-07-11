mysql-php/errors
===========

MySQL Server Error Constants

[![Latest Stable Version](https://poser.pugx.org/mysql-php/errors/v/stable)](https://packagist.org/packages/mysql-php/errors)
[![Total Downloads](https://poser.pugx.org/mysql-php/errors/downloads)](https://packagist.org/packages/mysql-php/errors)
[![License](https://poser.pugx.org/mysql-php/errors/license)](https://packagist.org/packages/mysql-php/errors)
[![Monthly Downloads](https://poser.pugx.org/mysql-php/errors/d/monthly)](https://packagist.org/packages/mysql-php/errors)

Covers up to MySQL 5.7.13. Notice that some constants were renamed in later
versions of MySQL, because they became obsolete. (In case you wonder: the names
here match the symbols MySQL uses in source code.) Obsolete names haven't been
changed in this package to avoid breaking code, but you should no longer be
using them in applications. 

## Usage

To start using error constants in your code, require mysql-php/errors in [Composer](https://getcomposer.org/):

```
composer require mysql-php/errors
```

## Changes

Here's the full list of changes since this package's first version:

| Code | This package | MySQL (as of 5.7.8) |
| ---: | ------------ | ------------------- |
| 1150 | ER_DELAYED_CANT_CHANGE_LOCK | ER_UNUSED1 |
| 1151 | ER_TOO_MANY_DELAYED_THREADS | ER_UNUSED2 |
| 1165 | ER_DELAYED_INSERT_TABLE_LOCKED | ER_UNUSED3 |
| 1349 | ER_VIEW_SELECT_DERIVED | ER_VIEW_SELECT_DERIVED_UNUSED |
