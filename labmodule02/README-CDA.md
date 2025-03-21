# Constrained Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

In this module, I implemented the `SystemPerformanceManager` component to collect and manage system metrics like CPU and memory usage. I created two utility classes: `SystemCpuUtilTask` and `SystemMemUtilTask`, which inherit from a shared `BaseSystemUtilTask` base class. These tasks are scheduled by the manager to run periodically.

Then, I integrated the `SystemPerformanceManager` into the main CDA app. I also created tests for each new class to verify that they behave as expected. The CDA now collects and logs system performance data in real-time, which will be useful for monitoring and future cloud integration.

### Code Repository and Branch

URL: https://github.com/MiniX16/python-components/tree/lab-module-02

### Unit Tests Executed

- ConfigUtilTest  
- DataUtilTest  
- NameServerManagerTest  
- SystemPerformanceManagerTest  
- SystemCpuUtilTaskTest  
- SystemMemUtilTaskTest  

### Integration Tests Executed

- ConstrainedDeviceAppTest
