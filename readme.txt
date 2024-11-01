=== Stop query_posts ===

Contributors: kovshenin
Donate link: http://kovshenin.com/beer/
Tags: query, posts
Requires at least: 3.5
Tested up to: 3.6
Stable tag: 0.9
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Let's stop this query_posts madness, shall we?

== Description ==

The query_posts() function is often misused by theme and plugin developers. This little plugin will call WordPress' built-in _doing_it_wrong() function, whenever query_posts() is used within a theme or plugin. It doesn't stop the query itself, but simply issues a notice if running in debug mode.

If you have a friend who uses query_posts(), use this plugin to help your friend out.