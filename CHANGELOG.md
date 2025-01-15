# 3.0.0

* Added `jquery-ui.structure.min.css` and `jquery-ui.theme.min.css` to `/plugins/datepicker/static/jquery-ui`
* Switched from SelectWoo to Selectcn.

# 2.0.1

* Fixed a bug with datepicker where the datepicker widget was appearing in the wrong location if it was in a popover or modal or had some scrolling. This fix has yet to be included in the stable release of jquery-ui and a pull request for it can be found here: [https://github.com/jquery/jquery-ui/pull/1935](https://github.com/jquery/jquery-ui/pull/1935)

# 2.0.0

* Fixed some additional 508 compliant issues in selectWoo

* Renamed `selectWoo/js/select2.full.js` to `selectWoo/js/selectWoo.full.js`

* Updated selectWoo to version 1.0.6

* **BREAKING CHANGE** Changed datepicker compliance patch to extend the original datepicker implementation, rather than patching instances after initialization.

  Update instructions:
    Move the inclusion of `datepicker/jqueryui_datepicker_508.js` to right after the datepicker plugin.

# 1.0.1

* Fixed a bug where the datepicker `beforeSend` function wasn't passing in the parameters.

# 1.0.0

* Added a 508 compliant version of select2 V3

* Added a 508 compliant version of selectWoo (fork fo select2 V4)

* Added a 508 compliant version of jQuery UI datepicker
