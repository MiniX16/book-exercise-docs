# Constrained Device Application (Connected Devices)

## Lab Module 04

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

In this module, I added actuator support to the CDA. I created `LedActivatorTask`, `HvacActuatorSimTask`, `HumidifierActuatorSimTask`, and `GenericActuatorSimTask` to simulate devices that respond to commands like turning on/off or changing levels (e.g., temperature or humidity).

These actuator classes are managed by `ActuatorAdapterManager`, which connects them to the `DeviceDataManager`. I also added a new actuator data type for testing. The implementation simulates how the CDA would control real hardware in future deployments.

### Code Repository and Branch

URL: https://github.com/MiniX16/python-components/tree/lab-module-04

### Unit Tests Executed

- ConfigUtilTest  
- DataUtilTest  
- DeviceDataManagerTest  
- ActuatorAdapterManagerTest  
- GenericActuatorSimTaskTest  
- HvacActuatorSimTaskTest  
- HumidifierActuatorSimTaskTest  
- LedActivatorTaskTest  

### Integration Tests Executed

- ConstrainedDeviceAppTest
