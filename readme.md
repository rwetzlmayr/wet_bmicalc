=== Body Mass Index (BMI) Calculator Widget ===
Contributors: wet
Tags: widget, sidebar, health, nutrition, fitness, bmi, body mass index, shortcode
Requires at least: 2.8
Tested up to: 3.4
Stable tag: trunk

Allows the user to calculate her Body Mass Index (BMI), a commonly accepted characteristic for obesity based on her body's weight and height.

== Description ==

Allows the user to calculate her Body Mass Index (BMI), a commonly accepted characteristic for obesity based on her body's weight and height. Please visit the accompanying [WordPress Body Mass Index Widget](http://bikinifigur.at/goodies/wp-bmi-rechner) article for further information on this widget's usage and the index' characteristics or value ranges.

Caveat: Your Body Mass Index is just a rough indication of your body's health condition and weight proportions. Do not use this value as a sole criterion for choosing your daily diet or excersising.

= Credits =

German translation by [Robert](http://abnehmtipps.at/) and [Nic Bastelt](http://nicbastelt.com/).
Hungarian translation by [Krisztina](http://reisesuechtig.com/).
Dutch translation by Rene.
Spanish translation by Brian Flores.

== Installation ==

1. Unzip `wet_bmicalc.zip` and upload the contained files to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

= Add the sidebar widget =

1. Install the `Body Mass Index` widget through the 'Design' menu in WordPress

= (Optional, for advanced users) Add `wet_bmicalc` to a post or a page =

1. Type `[wet_bmicalc]` into a post's or a page's body text.

= (Optional, for advanced users) Add `wet_bmicalc` to a template =

1. Enter `<?php echo do_shortcode('[wet_bmicalc]'); ?>` into a suitable template file.

== Frequently Asked Questions ==

= Which prerequisites does `wet_bmicalc` expect? =

Actually, very little. `wet_bmicalc` requires JavaScript for its calculations, that's about all.

= How would I modify wet_bmicalc's options when it is used as a short tag or inside a template? =

To modify this plugin's option, you will have to add a widget at least once. Once the options are set, they are used for all instances of this plugin and you can safely remove the widget.

== Changelog ==

= 1.6.0 =

1. Compatibility check with WordPress 3.4
1. Enhanced configurability

= 1.5.0 =

1. Compatibility check with WordPress 3.1
