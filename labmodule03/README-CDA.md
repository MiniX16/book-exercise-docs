# Constrained Device Application (Connected Devices)

## Lab Module 03

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

In this module, I implemented support for sensor data by creating new classes: `I2cSensorAdapter`, `MockI2cSensorAdapter`, `EnvironmentalSensorAdapterTask`, and `SensorAdapterManager`. These components allow the CDA to simulate collecting temperature, humidity, and pressure data, and send it to the `DeviceDataManager`.

The implementation uses mock data to simulate sensor readings, managed on a schedule. All components are integrated and tested to make sure sensor data flows correctly through the system. This lays the foundation for future hardware integration.

### Code Repository and Branch

URL: https://github.com/MiniX16/python-components/tree/lab-module-03

### Unit Tests Executed

- ConfigUtilTest  
- DataUtilTest  
- DeviceDataManagerTest  
- SensorAdapterManagerTest  
- EnvironmentalSensorAdapterTaskTest  
- MockI2cSensorAdapterTest  

### Integration Tests Executed

- ConstrainedDeviceAppTest
