# Constrained Device Application (Connected Devices)

## Lab Module 05

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

In this module, I added cloud connectivity to the CDA by integrating MQTT support. I created the `MqttClientConnector` class and connected it to the `DeviceDataManager`, enabling the app to publish and subscribe to messages from an MQTT broker.

I also updated the configuration to store MQTT settings and verified that the CDA could send actuator commands and receive responses over the network. This allows remote control and monitoring, which is a key step toward a fully connected IoT solution.

### Code Repository and Branch

URL: https://github.com/MiniX16/python-components/tree/lab-module-05

### Unit Tests Executed

- ConfigUtilTest  
- DataUtilTest  
- DeviceDataManagerTest  
- MqttClientConnectorTest  

### Integration Tests Executed

- ConstrainedDeviceAppTest
