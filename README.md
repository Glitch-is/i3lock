i3lock - improved screen locker
===============================
This is a fork of i3lock which implements some security features like fingerprint scanners, image capturing on fail and email alerts. If your laptop gets stolen you'll be sure to get an imaga of their face sent via email and perhaps even their fingerprints, which you can then use to alert the authorities.

Features
--------
- Fingerprint Scanners
- Image Capture the Culprate
- Email Alerts With Evidence

Requirements
------------
- pkg-config
- libxcb
- libxcb-util
- libpam-dev
- libcairo-dev
- libxcb-xinerama
- libev
- libx11-dev
- libx11-xcb-dev
- libxkbfile-dev
- libxkbcommon >= 0.2.0
- libxcb-dpms-dev
- libxcb-image-dev
- libfprint
- fprintd
- fingerprint-gui

Running i3lock
-------------
Simply invoke the 'i3lock' command. To get out of it, enter your password and
press enter.
