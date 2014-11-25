WordPress
=========

This is a fork of the WordPress GitHub project (wordpress/wordpress).

This fork contains a composer.json file so that WordPress can be easily installed via Composer.

This project tracks versions by adding a fourth versioning number onto WordPress versions.

For example,
* version 4.0 of WordPress would be version 4.0.0.1
* version 4.0.1 of WordPress would be version 4.0.1.1

In other words, look at the first 3 components of this projects version number to determine what
version of WordPress is being used.

It seems that it safe to do this because the WordPress project has only ever used a maximum of 3
versioning components (*.*.*).
 