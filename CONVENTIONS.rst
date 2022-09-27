Basic recommended conventions
#############################

Recommended folder structure and naming conventions for Sunlight CMS plugins.

.. contents::

Plugin folder structure
***********************

Extend plugin
-------------
::

    .
    ├── plugins
    │   ├── extend
    │   │   ├── foobar                   	# Plugin name in lower case, no spaces (dash can be used)
	│   │   │   ├── hcm                     # Files with HCM modules
    │   │   │   ├── lang                    # Files with localized texts used in the plugin
    │   │   │   │    ├── cs.php
    │   │   │   │    └── en.php
    │   │   │   ├── resources               # Resources used by the plugin
    │   │   │   │    ├── css
    │   │   │   │    ├── images
    │   │   │   │    └── js
    │   │   │   ├── FoobarPlugin.php        # Capitalized plugin name followed by Plugin.php
    │   │   │   └── plugin.json             # Plugin definition file
    │   │   └── ...
    │   ├── templates
    │   └── languages
    └── ...
    
Template plugin
-------------
::

    .
    ├── plugins
    │   ├── extend
    │   ├── templates
    │   │   ├── cooltemplate                # Plugin name in lower case, no spaces
    │   │   │   ├── images                  # Folder for images
    │   │   │   │    ├── bbcode             # BBCode buttons
    │   │   │   │    ├── icons              # Icons for dialogs
    │   │   │   │    └── system             # System images - horizontal line, poll bar...
    │   │   │   ├── labels                  # Files with localized template box labels
    │   │   │   │    ├── cs.php
    │   │   │   │    └── en.php
    │   │   │   ├── style.css               # File with CSS classes
    │   │   │   ├── plugin.json             # Plugin definition file
    │   │   │   └── template.php            # Base file, which contains the HTML structure of the theme
    │   │   └── ...
    │   └── languages
    └── ...

