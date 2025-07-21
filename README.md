# remove_class_filter()

This repository defines a utility function `remove_class_filter` which can be used to remove a filter/action added by a WordPress plugin/theme class.

## Installation

This project can be installed using Composer as `humanmade/remove-class-filter`.

## Usage

```php
use function HM_Remove_Class_Filter\remove_class_filter;

// Remove LSD_Admin::block_admin from the admin_init action (default priority).
remove_class_filter( 'admin_init', 'LSD_Admin', 'block_admin' );
```
