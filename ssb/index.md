# TSSSB and winssb

`winssb` is only avalible in the Electron desktop client.  It provides apis for interacting with the native window and other native functions.

`TSSSB` seems to provide higher-level APIs dealing with native platforms such as:
* Downloads
* Multiple Workspaces
* Deep linking
* Voice Calling

In the web browser, TSSSB exposes a single stub: `TSSSB.call` which returns `False`