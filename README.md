# django-508-plugins
Installable Django app containing 508-compliant plugins.

## Requirements:

* jQuery 1.6+

## Current 508 Compliant packages:

* select2 v3 [ [Git](https://github.com/imsweb/select2/tree/IMS_select2) | [Docs](https://select2.github.io/select2/) ]
* selectWoo (select2 V4) [ [Git](https://github.com/woocommerce/selectWoo) | [Docs](https://select2.org/) ]
* jQuery 1.11.4 Datepicker [ [Git](https://github.com/jquery/jquery-ui) | [Docs](https://api.jqueryui.com/datepicker/) ]

## Usage

```
pip install django-508-plugins
```

Add the desired plugins to your INSTALLED_APP::

    INSTALLED_APPS = [
        ...
        'plugins.datepicker',
        'plugins.[select2 | selectWoo]'
    ]

**Note**: plugins.select2 and plugins.selectWoo may conflict if both are installed.  It is **highly** recommended that you only install one.
