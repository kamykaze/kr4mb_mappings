KeyRemap4MacBook Mappings
=========================

This project contains remapping files for [KeyRemap4MacBook](https://github.com/tekezo/KeyRemap4MacBook/)

KeyRemap4MacBook is a powerful utility for keyboard customization that utilizes
xml files to add custom keyboard mappings.

Current Features:

* custom Numeric Keypad mode - an alternative to Virtual NumLock that does not require you to move your hand from the home keys
* Spaces Mode - allows you to change Desktops (aka Spaces), trigger Mission Control, etc.
* Cursor Mode - allows you to use arrow keys, home, end, etc. from the home row
* Window Sizing Mode - compatible with TotalSpaces and BetterTouchTool, allows you to resize your windows to predefined size/location quickly

Requirements
------------

KeyRemap4MacBook 8.0.0 or later

see KeyRemap4MacBook for other requirements

How to Setup
------------
There's no installation necessary, but here are some instructions on how to get 
these mappings to show up on KeyRemap4MacBook:

1. Get the repo by cloning it to a location of your choice

<pre>
git clone git@github.com:kamykaze/kr4mb\_mappings.git
</pre>

2. Go into KeyRemap4MacBook's private.xml location

<pre>
cd ~/Library/Application\ Support/KeyRemap4MacBook
</pre>

3. Symlink the mappings folder

<pre>
ln -s <PATH_TO_KR4MB>/mappings
</pre>

4a. If you don't have other customizations in your private.xml file, feel free to 
symlink the private.xml as well

<pre>
ln -s <PATH_TO_KR4MB>/private.xml
</pre>

or

4b. Copy the contents of the private.xml to the top of your private.xml

