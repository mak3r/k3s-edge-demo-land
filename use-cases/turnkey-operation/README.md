# Turnkey Operation
This use case can be demonstrated using either single or multi-node clusters. The *secret sauce* to turnkey operation is actually a container or containers which expose local website at a fixed ip address when the device first starts up. The turnkey operator will then be asked to enter some basic information in a web form and once that is submitted, the device will be configured according to the selections.

## Device List
* @see [Single Node Master](../single-node-master/README.md)
* @see [Dual Node Master](../dual-node-master/README.md)

## DB Configuration
* Varies based on device selection

## Additional Resources
* TBD - turnkey containers under development

## Additional Notes
Recent developments in k3s now provide us with a *System Upgrade Controller*. This may be a valuable tool in turnkey operations.

## Demo Documentation
* Preconfigure device with turnkey container
    1. Plug in device
    1. Turn on
    1. Visit 192.168.1.1
    1. Enter form details
    1. Select *OK* button
    1. Wait for device to restart
    1. Visit *blah url* to see/operate configured device(s)