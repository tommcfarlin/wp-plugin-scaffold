# WP Plugin Scaffold

The description for the plugin scaffolded by this repository.

## Installation

### Using The WordPress Dashboard

1. Navigate to the 'Add New' Plugin Dashboard.
2. Select `wp-plugin-scaffold.zip` from your computer.
3. Upload.
4. Activate the plugin on the WordPress Plugin Dashboard.

### Using FTP

1. Extract `wp-plugin-scaffold.zip` to your computer.
2. Upload the `wp-plugin-scaffold` directory to your `wp-content/plugins` directory.
3. Activate the plugin on the WordPress Plugins Dashboard.

### Git

1. Navigate to the `plugins` directory of your WordPress installation.
2. From the terminal, run `$ git clone git@github.com:tommcfarlin/wp-plugin-scaffold.git`

## Notes

This specific repository assumes you're running PHP 8.0.  At the time of this writing, WordPress is not fully compatible with PHP 8.0; however, if you change the references to PHP 7.4.28 in

* `composer.json`
* `plugin.php`

Then you should be okay. If you still experience problems, make sure you're not running Composer 2. If that still doesn't work, don't hesitate to open an [issue](https://github.com/tommcfarlin/wp-plugin-scaffold/issues).
