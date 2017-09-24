grid_instrument (aka Launchpad Scale-mode)
============

Did you ever wish you could use your Launchpad as a MIDI controller? Do you covet the **scale mode** on the Launchpad Pro or Ableton Push, but not have the cash to buy them? Now you can play scales on any Novation Launchpad. 

Here's a quick [video demo](https://youtu.be/JJA2fm-2NVg).

At it's core, grid_instrument is a library that allows you to display a scale grid on your Novation Launchpad. It functions very similarly to the scale mode on Henri David's _fantastic_  [Launchpad95](http://motscousus.com/stuff/2011-07_Novation_Launchpad_Ableton_Live_Scripts/) scripts for Ableton Live, and also similarly to the [scale mode](https://global.novationmusic.com/launchpad-pro-scale-mode) on a Launchpad Pro.

Features:

* Can be used as a standalone app or incorporate into another Python project.
* Key switching (you know, so that you're not stuck in the key of C)
* Scale switching between the same 26 musical modes as Launchpad95
* Works on Raspberry Pi and Mac OS (probably Windows, too, but not tested).
* Works with all Novation Launchpads

## Requirements

Before you try to do anything, make sure you have **Python 2** and **pip** install.

## How to use it as a standalone app

Download the source code from github and install prerequisites:

    git clone https://github.com/GridInstrument
    cd GridInstrument; pip install launchpad_rtmidi_py

Run the app:

    python play.py

### How to use it as a Python library

You have two options for how to install it.

### Option 1: Install it manually

Download the source code from github:

    git clone https://github.com/GridInstrument
    cd GridInstrument

Install it:

    python setup.py install

#### Option 2: Install it with Pip

    pip install grid_instrument