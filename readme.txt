=== Plugin Name ===
Contributors: digitalnature, wycks
Donate link: http://wordpressfoundation.org
Tags: debug, var_dump, debugging
Requires at least: 3.5
Tested up to: 3.5.2
Stable tag: 1.0
 
A WordPress plugin that makes var_dump and print_r pretty! 
 
== Description ==
 
Make var_dump and print_r more readable 

Function output references with [http://queryposts.com](http://queryposts.com) API when possible.
 
* Use `r` instead of `var_dump`
* Use `rt` for text mode.

For example:

`r($GLOBALS['wp_query']->get_posts());`
`rt($GLOBALS['wp_query']->get_posts());`

You can use the hotkey "x" to collapse tabs

Notes :
 
*  Probably doesn't work in ie
*  Don't use this on a production site, but you probably already know that
*  More usage [https://github.com/digitalnature/php-ref](https://github.com/digitalnature/php-ref)

All the work was done by [digitalnature](https://github.com/digitalnature) I just wrapped it into a WordPress plugin and changed the look for inline debugging.


 Please report issues to:  [https://github.com/wycks/WP-Pretty-Debug](https://github.com/wycks/WP-Pretty-Debug)
 
== Installation ==
 
Use the Auto Installer.
Or Upload the zip and hit install.
 
 
== Frequently Asked Questions ==
 
 What is this?

 [var_dump](http://php.net/manual/en/function.var-dump.php) - Dumps information about a variable.
 
== Screenshots ==
 
1. A screenshot with mouseover
 
 
== Changelog ==
 