Yii2 Meta
=========
Yii 2 Meta. Finds and lists actions in controllers/models/modules

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

This extension is based upon MetaData extension for Yii 1.x created by Vitaliy Stepanenko. It is modified to work with Yii 2.x.

Either run

```
php composer.phar require --prefer-dist sspl/meta-actios "*"
```

or add

```
"sspl/meta-actions": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \sspl\MetaData::getControllersActions(); ?>```
