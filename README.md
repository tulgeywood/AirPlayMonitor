AirPlay Quality Monitor is a simple daemon to help diagnose networking issues with AirPlay. Normally all AirPlay information is logged to to the main system log in OS X which makes in fairly useless for collecting data when a use finally gets around to mentioning their issues to you. AQM instead creates a dedicated log at /var/log/airplay.log that provides the following:

Jun 26 14:54:24 RSSI: -49 Noise: -92 Tx Rate: 867 BSSID: xx:xx:xx:xx:xx:xx
Jun 26 15:01:23 Disconnected from "Apple TV" after 419 seconds

Though very simple currently, I plan to expand what items it pulls over time. For now though you can use this to see if your users are just getting bad signal or if a specific WAP is causing issues.
