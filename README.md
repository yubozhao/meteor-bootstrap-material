Bootstrap for meteor
====================

This package integrates bootstrap-material(FezVrasta/bootstrap-material-design) into meteor and lets you configure what parts you need.

How to install
--------------



1. execute `meteor add bozhao:bootstrap less` or `meteor add nemo64:bootstrap`
2. execute `meteor add bozhao:bootstrap-material`
3. create an empty `custom.bootstrap.json` file somewhere in your project. (`/client/lib/custom.material.json` for example)
4. start meteor and then edit the file you just created (see [custom.material.json](#custom.material.json)).
5. (optional) edit `custom.material.base.import.less` which now appeared next to the json file

custom.bootstrap.json
---------------------
This file is to configure which bootstrap parts you need in your project. Set those you like to `true`!
If the file is empty, it will be filled for with the following content:
```JSON
{"modules": {
   "_alerts":                           false,
   "_buttons":                          false,
   "_cards":                            false,
   "_checkboxes":                       false,
   "_dialogs":                          false,
   "_icons-material-design":            false,
   "_icons":                            false,
   "_inputs":                           false,
   "_labels":                           false,
   "_lists":                            false,
   "_mixins":                           false,
   "_navbar":                           false,
   "_panels":                           false,
   "_plugin-dropdownjs":                false,
   "_plugin-nouislider":                false,
   "_plugin-selectize":                 false,
   "_plugin-snackbarjs":                false,
   "_popups":                           false,
   "_radios":                           false,
   "_shadows":                          false,
   "_tabs":                             false,
   "_togglebutton":                     false,
   "_variables":                        false,
   "_welljumbo":                        false,
   "material-wfont":                    false,
   "material":                          false,
   "ripples":                           false
}}
```

License
-------

This package is licensed with the MIT license.
Also, look at the [Bootstrap license](https://github.com/twbs/bootstrap/blob/v3.2.0/LICENSE).

Origin
------

This package is based on and inspired by the [bootstrap3-less](https://github.com/simison/bootstrap3-less) package. I created a new repository because it takes a completely different approach now which is also incompatible.
