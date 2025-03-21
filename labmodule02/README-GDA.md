# Gateway Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-GDA-* issues (requirements).

### Description

In this module, I created and connected a new `SystemPerformanceManager` class to the main GDA app. This manager is responsible for collecting system performance metrics like CPU and memory usage through scheduled tasks. I added the necessary classes and interfaces to support this, following the design from the CDA implementation.

After integrating the manager into the app, I verified that performance data was being collected and logged correctly. This prepares the GDA for future modules where it will forward this data to other components or services.

### Code Repository and Branch

URL: https://github.com/MiniX16/java-components/tree/lab-module-02

### Unit Tests Executed

- ConfigUtilTest  
- DataUtilTest  
- SystemPerformanceManagerTest  
- SystemCpuUtilTaskTest  
- SystemMemUtilTaskTest  

### Integration Tests Executed

- GatewayDeviceAppTest
