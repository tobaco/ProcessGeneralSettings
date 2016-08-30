# Global settings for ProcessWire 2.8+

This module provides a solution for keeping general site settings in one place

## Features

- Admin can create unlimited number of settings
- Settings can be grouped
- Admin can set setting label, notes, property name, field width and type
- Settings can be of type text, checkbox, radios, select, email, url, integer

## How to use

In module configuration create as many settings as needed. Customize their label, type, width 
and provide a name you want to use in a template files (property name).
Every time you wish to output site name you can use $settings->site_name or wire('settings')->site_name
You can change global name ($settings) to something else in module configuration.

To get basic markup with all settings and their values use $settings->render().

Current limitation: 
-no way to change order of settings,
-new settings can be only appended,

## Requirements

This version of the module requires ProcessWire 2.8.  

---

Copyright 2016 by Piotr Markiewicz 
