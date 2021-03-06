Debugging shortcut for Yii2
======================
This package wrap VarDumper::dump() to d(), dd() functions as a shortcut.

Installation
------------
### Install With Composer

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require man-85/yii2-dumper "*"
```

Or, you may add

```
"man-85/yii2-dumper": "*"
```

to the require section of your `composer.json` file and execute `php composer.phar update`.

### Install From the Archive

Download the latest release from here [releases](https://github.com/man-85/yii2-dumper/releases), then extract it to your project.

Usage
------------
Since for the sake of Simplicity and Quick Development, I’ve created a helper for those who use Yii. You can just call dd($var1); for dump & die or d($var1); for dump data.

```
d($var);
dd($var);
```
