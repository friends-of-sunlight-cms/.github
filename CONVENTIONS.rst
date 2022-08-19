Folder Structure Conventions
============================

Folder structure options and naming conventions for Sunlight CMS plugins.

.. contents::

Typical directory layout of the ``extend`` plugin
-------------------------------------------------
::

    .
    ├── plugins
    │   ├── extend
    │   │   ├── foobar                      # Plugin name in lower case, no spaces (dash can be used)
    │   │   │   ├── lang                    # Files with localized texts used in the plugin
    │   │   |   |    ├── cs.php
    │   │   |   |    └── en.php
    │   │   │   ├── Resources               # Resources used by the plugin
    │   │   |   |    ├── css
    │   │   |   |    ├── images
    │   │   |   |    └── js
    │   │   │   ├── FoobarPlugin.php        # Capitalized plugin name followed by Plugin.php
    │   │   │   └── plugin.json             # Plugin definition file
    │   │   └── ...
    │   ├── templates
    │   └── languages
    └── ...

