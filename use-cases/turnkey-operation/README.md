# Turnkey Operation
This use case can be demonstrated using either single or multi-node clusters. The *secret sauce* to turnkey operation is actually a container or containers which expose local website at a fixed ip address when the device first starts up. The turnkey operator will then be asked to enter some basic information in a web form and once that is submitted, the device will be configured according to the selections.

## Device List
* @see [Single Node Master](../single-node-master/README.md)
* @see [Dual Node Master](../dual-node-master/README.md)
* TODO: Multi-node master with embedded db docs 

## DB Configuration
* Varies based on device selection

## Additional Resources
* [A Turnkey Solution](https://github.com/mak3r/turnkey)

## Additional Notes
Recent developments in k3s now provide us with a *System Upgrade Controller*. This may be a valuable tool in turnkey operations.

## Demo Documentation
* Preconfigure a device with [a turnkey solution](https://github.com/mak3r/turnkey)
    * [User experience doc](https://github.com/mak3r/turnkey/blob/master/doc/user-instruction.md)
