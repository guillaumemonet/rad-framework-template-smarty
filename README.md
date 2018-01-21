RAD : Smarty Template Service
==========================

[![Latest Stable Version](https://poser.pugx.org/rad/rad-framework-template-smarty/v/stable)](https://packagist.org/packages/rad/rad-framework-template-smarty)
[![Build Status](https://travis-ci.org/guillaumemonet/rad-framework-template-smarty.svg?branch=master)](https://travis-ci.org/guillaumemonet/rad-framework-template-smarty)
[![Total Downloads](https://poser.pugx.org/rad/rad-framework-template-smarty/downloads)](https://packagist.org/packages/rad/rad-framework-template-smarty)
[![Latest Unstable Version](https://poser.pugx.org/rad/rad-framework-template-smarty/v/unstable)](https://packagist.org/packages/rad/rad-framework-template-smarty)
[![License](https://poser.pugx.org/rad/rad-framework/license)](https://packagist.org/packages/rad/rad-framework-template-smarty)
[![Maintainability](https://api.codeclimate.com/v1/badges/a8004edb8c7a4a82773e/maintainability)](https://codeclimate.com/github/guillaumemonet/rad-framework-template-smarty/maintainability)

## Installation

[PHP](https://php.net) 7.1+ and [Composer](https://getcomposer.org) are required.

To get the latest version of RAD Smarty Template Service, simply add the following line to the require block of your `composer.json` file:

```
"rad/rad-framework-template-smarty": "dev-master"
```

## Usage

Put this config in your config.json service template section 

```json

"smarty": {
    "classname": "Rad\\Template\\SmartyTemplateHandler",
    "config": {
        "compile_check": true,
        "force_compile": false,
        "debugging": false,
        "error_reporting": true,
        "caching": false,
        "cache_locking": true,
        "cache_lifetime": 3600,
        "template_dir": "templates/",
        "compile_dir": "cache/",
        "config_dir": "config/",
        "cache_dir": "cache/"
    }
}

```

```php
Template::getHandler('smarty');
```

## How is works



