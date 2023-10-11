### V1.7.1
- Minor fixes.

### V1.7.0
- Added a set of device triggers to make common automations easier

### V1.6.0
- Diagnostic by @greghesp in #224
- Fix start time sensor. Adjust end time sensor. by @AdrianGarside in #225
- Fix firmware check on X1 by @AdrianGarside in #228
- Generate start time for P1P/S by @AdrianGarside in #230
- Delete dead mc print support by @AdrianGarside in #229

### V1.5.0
- Fix syntax error by @AdrianGarside in #205
- New filaments by @faucherc in #204
- Readme updates by @AdrianGarside in #208
- Re-enable Bambu cloud MQTT connection to printer. by @AdrianGarside in #209
- Add mqtt mode diagnostic sensor by @AdrianGarside in #210
- Alternative fix for start time by @AdrianGarside in #212
- Avoid overlapping initialization and AMS reinitialization by @AdrianGarside in #214
- Fix mqtt mode change to reload integration by @AdrianGarside in #216
- Detect offline with bambu cloud mqtt mode connection by @AdrianGarside in #217

### V1.4.13
- Fixed some typos and correction to string comparison by @fmeus in #200
- Add pause print status by @piitaya in #202

### V1.4.12
- Gracefully handle print_status (gcode_state) being an empty string on printer power on by @AdrianGarside in #197

### V1.4.11
- Adrian/add failed state translation support by @AdrianGarside in #192
- Update french translations and add empty attribute translation by @piitaya in #190
- Update rtsp URL to use host address instead of one given in the mqtt payload due to report of the latter being incorrect.

### V1.4.9
- Add entity translation support by @piitaya in #178
- Support for adding LED chamber lights via the WLED integration by @dreed47 in #180
- Add Camera functionality by @greghesp in #184
- Add active tray sensor by @AdrianGarside in 8eca79e
- Add gcode filename and task name by @AdrianGarside in ee815b7

...
