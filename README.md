# Boundary Windows Performance Counters Plugin

Collects metrics from Windows performance counters.

## Prerequisites

### Supported OS

|     OS    | Linux | Windows | SmartOS | OS X |
|:----------|:-----:|:-------:|:-------:|:----:|
| Supported |       |    v    |         |      |

#### Requires Boundary Meter Versions V4.0 or later

- To install new meter go to Settings->Installation or [see instructons|https://help.boundary.com/hc/en-us/sections/200634331-Installation]. 
- To upgrade the meter to the latest version - [see instructons|https://help.boundary.com/hc/en-us/articles/201573102-Upgrading-the-Boundary-Meter].

### Plugin Setup

None

### Plugin Configuration Fields

|Field Name     |Description                                |
|:--------------|:------------------------------------------|
|Source         |display name                               |
|PollInterval   |Interval to query performance counters     |


### Metrics Collected

|Metric Name                      |Description                                                                                                   |
|:--------------------------------|:-------------------------------------------------------------------------------------------------------------|
|PROC - Perc Proc Time            |Percentage of the time the processor is busy                                                                  |
|MEM - Available Bytes            |Amount of memory available for allocation to a process or for system use                                      |
|MEM - Page Rate                  |Tracks the number of virtual memory pages read or written per second to or from the virtual memory file.      |
|PDISK - Disks Queue Length       |Tracks the average number of items in physical disks queue                                                    |
|PDISK - Disks Bytes Rate         |Current read or written rate to or from physical disks                                                        |
|PDISK - Perc Disks Time          |Percentage of the time the physical disks are busy servicing read or write requests                           |
|LDISK - Free disks space         |FreeSpace is the amount of total free storage space in bytes available on the logical disks                   |
|NET - Network receiving          |BytesReceivedPersec are the current transmission rates for the specified network card                         |
|NET - Network Queue Length       |Tracks the average number of items in the output queue of the specified network card                          |
|NET - Network sending            |BytesSentPersec are the current transmission rates for the specified network card                             |
|TCP4 - Connections               |TCP4ConnectionEstablished,  is the current number of established connections, inbound and outbound            |
|TCP6 - Connections               |TCP6ConnectionEstablished,  is the current number of established connections, inbound and outbound            |
