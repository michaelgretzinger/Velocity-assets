### Project Information:
Project: Ping driver
Description: A generic ICMP driver that implements the Management interface.
Category: driver
Class: TestedBySpirent

A generic ICMP driver that implements the Management interface. Can be used only for
determine online status of device, port and properties lists always returned empty. The following
resource properties requires:
* ipAddress (optional, but either ipAddress or Hostname must be specified)
* Hostname (optional, but either ipAddress or Hostname must be specified)

 ----
1 test case in project
## Test Case File: ping.fftc
### getDeviceStatus
### getProperties
### getPorts
### getHostParameter