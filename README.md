AirPlay Quality Monitor is a simple daemon to help diagnose networking issues with AirPlay. Normally all AirPlay information is logged to to the main system log in OS X which makes in fairly useless for collecting data when a use finally gets around to mentioning their issues to you. AQM instead creates a dedicated log at /var/log/airplay.log that provides the following:

Jul 19 21:01:57 Successfully connected to: Apple TV

Jul 19 21:01:57 RSSI: -43 Noise: -93 Tx Rate: 867 BSSID: 6c:70:9f:e0:71:65

Jul 19 22:28:41 Disconnected from "Apple TV" after 5204 seconds

Though very simple currently, I plan to expand what items it pulls over time. For now though you can use this to see if your users are just getting bad signal or if a specific WAP is causing issues.
