# Yii2 Semantic UI extension

[Semantic UI](http://semantic-ui.com) extension for [Yii2](http://www.yiiframework.com)

## Installation

### Composer

The preferred way to install this extension is through [Composer](http://getcomposer.org/).

Either run

```
php composer.phar require zelenin/yii2-semantic-ui "*"
```

or add

```
"zelenin/yii2-semantic-ui": "*"
```

to the require section of your ```composer.json```

## Usage

Add SemanticUICSSAsset to AppAsset:

```php
<?php

namespace backend\assets;

use yii\web\AssetBundle;

class AppAsset extends AssetBundle
{
    public $basePath = '@webroot';
    public $baseUrl = '@web';
    public $css = [];
    public $js = [];
    public $depends = [
        'yii\web\YiiAsset',
        'yii\web\JqueryAsset',
        'Zelenin\yii\SemanticUI\assets\SemanticUICSSAsset'
    ];
}
```

Use Semantic UI widgets and elements. Standard Yii2 widgets also adopted.

### Demo

[Demo site](http://yii2-semantic-ui.zelenin.pw)

### Work in progress

I need your feedback! I need your pull requests!

## Author

[Aleksandr Zelenin](https://github.com/zelenin/), e-mail: [aleksandr@zelenin.me](mailto:aleksandr@zelenin.me)
