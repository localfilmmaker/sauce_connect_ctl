sauce_connect_ctl
=================

Service control script for managing Sauce-Connect java app for proxying secure connections with Sauce Labs.

This script will manage (start/stop/status) the Sauce-Connect java app which allows for secure proxy connections to SauceLabs.
Two env variables are required:
   SAUCELABS_USER
   SAUCELABS_APIKEY

If the file $HOME/.saucelabsrc exists, it will be sourced.

Download this script and place it in the same dir as the Sauce-Connect.jar java app.  You can download the Source-Connect app here: http://saucelabs.com/downloads/Sauce-Connect-latest.zip.
