# Gateway Device Application (Connected Devices)

## Lab Module 05

Be sure to implement all the PIOT-GDA-* issues (requirements).

### Description

In this module, I integrated MQTT support into the GDA. I implemented `MqttClientConnector` and connected it to the `DeviceDataManager`, allowing the GDA to handle messages from remote devices via an MQTT broker.

This setup enables the GDA to receive sensor data and send actuator responses through the cloud. I tested publishing and subscribing features and confirmed that messages were processed correctly.

### Code Repository and Branch

URL: https://github.com/MiniX16/java-components/tree/lab-module-05

### Unit Tests Executed

- ConfigUtilTest  
- DataUtilTest  
- MqttClientConnectorTest  
- DeviceDataManagerTest  

### Integration Tests Executed

- GatewayDeviceAppTest
