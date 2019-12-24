# smogbusters
Air monitoring project

Links:
 - particulate matter (PM) map: http://smogbusters.org/
 - charts: http://grafana.smogbusters.org/dashboard/db/measurements?refresh=10s&orgId=1
 - list of components: [bom.md](./docs/bom.md)

![smogbusters-prototype](./docs/images/smogbuster-v2.0-800px.png)

## IDE Setup

To run project it is required to install to local Arduino IDE additional board compatible with ours from BOM.

To do that it is required to:
* open Arduino IDE
* ```Preferences -> Additional Boards Manager URLs``` set: http://arduino.esp8266.com/stable/package_esp8266com_index.json
* Close window clicking ```OK```
* Go to ```Tools -> Boards -> Boards Manager```
* Find and install ```esp8266 by ESP8266 Community```


