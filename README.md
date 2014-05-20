ConnectME
=========

Ruby scripts for making the connection process at FHNW easier.

rVPNMeNow.rb
------------

Requirements:

    # 'json' is used to read settings.json
    $ gem install json

Usage:

    $ ruby rVPNMeNow.rb <action (open/close)> <settings>
    # example: ruby rVPNMeNow.rb open settings.json
    # example: ruby rVPNMeNow.rb close

Connects you to the school VPN via Applescript. It also requires a given
settings.json file with your Account credentials.

rCheckWifi.rb
-------------

Checks if you're connected to the school Wifi.

Usage:

    $ ruby rCheckWifi.rb

rADMeNow.rb
-----------

This script connects and opens the Active Directory.
If you're not connected to the VPN it does it for you.

Usage:

    $ ruby rADMeNow.rb
