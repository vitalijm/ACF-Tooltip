# Advanced Custom Fields: Tooltips

Change the display of the ACF instructions. The ACF-Tooltips plugin hides the instructions, adds a help symbol to the label of the fields and generate a tooltip of the instuction.

![advanced custom field column field in tabs](http://www.dreihochzwo.de/download/acf-tooltip2.jpg)

**This plugin needs the installation/activation of Advanced Custom Fields V5**

### Installation

This add-on can be treated as both a WP plugin and a theme include.

**Install as Plugin**

1. Copy the 'acf-tootip' folder into your plugins folder
2. Activate the plugin via the Plugins admin page

**Include within theme**

1.	Copy the 'acf-tootip' folder into your theme folder (can use sub folders). You can place the folder anywhere inside the 'wp-content' directory
2.	Edit your functions.php file and add the code below (Make sure the path is correct to include the acf-tootip.php file)

```php
include_once('acf-tooltip/acf-tooltip.php');
```

### Compatibility

This ACF field type is only compatible with ACF 5


### Changelog
**1.1.6**
* Fix to work correct on new posts/pages

**1.1.6**
* Another fix to work even if instructions are set below fields

**1.1.5**
* Prevent loading of scripts in field group editor

**1.1.4**
* Fix to work better with new ACF V 5.3.9.x

**1.1.3**
* Fix to work even if instructions are set below fields

**1.1.2**
* Fix to work correctly in table layout in Repeater Field

**1.1.1**
* Fix to work with Repeater Field

**1.1.0**
* Changed code to fix issue with special characters in tooltip 

**1.0.1**
* Small bugfixes

**1.0.0**
* First release
