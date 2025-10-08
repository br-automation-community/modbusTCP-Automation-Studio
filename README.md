## Description
modbusTCP library for Automation Studio with legacy runtimes that don't support native modbusTCP.

See [**description**](https://github.com/br-automation-community/modbusTCP-Automation-Studio/blob/master/Description%20modbusTCP%20library%20AS6.x.pdf) for more details. Also see release package for additional tools.

## Revision History
Version 3.0

- Update project to AS6
- Change logger function call to avoid warnings in AS6

Version 2.1

- SLAVE: Changed default port to 502

Version 2.0

- CHANGE: Ported library to AS4
- CHANGE: Added device configuration error to slave
- CHANGE: Changed logger structure to pointer with fixed size
- CHANGE: Added error message to port open steps
- CHANGE: Auto detect cycle time in master
- CHANGE: Added configuration constants
- CHANGE: Updated configuration
