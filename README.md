<!-- ### Displays Live NetSpeed &amp; Time always on your Android TV/ Fire TV screen. Also monitor Free Memory, Uptime and Session Data Usage in Useful Information Screen. -->
<!-- Available for Download @ -->
Report Issues, Bugs, Feature Suggestion in github issues section [here](https://github.com/visnkmr/timenetspeed/issues) or [telegram](https://vishnunkmr.t.me)  
  
**Monitor live bandwidth usage/ network speed on any device running on any OS except iOS.**  
  
✓ **Tested on:** Linux, Windows, MacOS, Windows Subsystem for Android, Android Phones, Tablets, Android TVs, Fire TVs. (Remote Friendly)  

**What does the app do?**  
It adds an overlay that shows mobile data, Ethernet or WiFi network speed. The overlay shows the rate at which your data is being consumed. The indicator updates in real-time showing the current network speed at all times.  

## PC version (Open Source):
There are 2 PC versions available one that use http server and other that uses server send events protcol(sse).
Has two components:  
### [SSE Server](https://github.com/visnkmr/netspeed_server/releases/latest) || [HTTP Server](https://github.com/visnkmr/netspeed_server_http/releases/latest)  
A rust server that saves the total data used in bytes every minute and provides a json endpoint that the GUI fetches the data from. You can choose to specify an interface name if required.  
### [GUI](https://github.com/visnkmr/ns_gui/releases/latest)  
A python GUI that can be moved freely to anywhere on screen and closed when not required.  

## Android version:
Available @ [Play Store](https://play.google.com/store/apps/details?id=visnkmr.apps.timenetspeed), [Amazon Appstore](https://www.amazon.com/Vishnu-N-K-Speed-Monitor/dp/B0786KC4C1/). Android version also has Useful Information Screen to monitor Free Memory, Uptime and Session Data Usage .  
  
**Customisation offered:**  
✓ 12 hour/ 24 hour clock.  
✓ Supports Android TVs with overscan enabled.  
✓ Adjust Size of Time and speed meter.  
  
*Please Note:  
Some Fire TV(s), Android device(s), TV(s) require additional [steps to enable overlay](https://visnkmr.github.io/overlay-permission-help) since they lack the settings option to be able to enable Overlay permission for any app, hence, Unless permission is allowed manually the overlays won't be displayed. Hence, shows you these details on opening the app.*  
