Yii2 LightBox2 assets
=====================

This is asset for using [Lightbox2](https://github.com/lokesh/lightbox2)

## Installation

The preferred way to install this yii2-extension is through [composer](http://getcomposer.org/download/).

Either run

```sh
composer require "tsanchev/yii2-lightbox2"
```

or add

```json
"tsanchev/yii2-lightbox2": "*"
```

to the require section of your composer.json.

## Usage

Include in view

```php
 use tsanchev\lightbox2\LightboxAsset;
 
 LightboxAsset::register($this);
 ```  
        
 or in asset file
 
 ```php
 'tsanchev\lightbox2\LightboxAsset',
 ```

## License

This project is released under the terms of the BSD-3-Clause [license](LICENSE).
Read more [here](http://choosealicense.com/licenses/bsd-3-clause).

Copyright © 2015-2016, tsanchev (http://tsanchev.com/)
