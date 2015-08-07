Yii 2.0 web shell
=================

Web shell allows to run `yii` console commands using a browser.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist samdark/yii2-webshell "~1.0"
```

or add

```
"samdark/yii2-webshell": "~1.0"
```

to the require section of your `composer.json` file.


Configuration
-------------

To use web shell, include it as a module in the application configuration like the following:
 
```php
return [
    'modules' => [
        'webshell' => ['class' => 'samdark\webshell\Module'],
    ],
]
```

With the above configuration, you will be able to access web shell in your browser using
the URL `http://localhost/path/to/index.php?r=webshell`

