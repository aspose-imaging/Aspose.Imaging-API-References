---
title: InterruptMonitor Class
type: docs
weight: 20
url: /python-net/aspose.imaging.multithreading/interruptmonitor/
---

**Summary:** Represents information about interruption.

**Module:** [aspose.imaging.multithreading](/imaging/python-net/aspose.imaging.multithreading/)

**Full Name:** aspose.imaging.multithreading.InterruptMonitor

**Inheritance:** IInterruptMonitor

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [InterruptMonitor()](#InterruptMonitor__1) | The IInterruptMonitor instance which is unique for each thread. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_interrupted | bool | r | Gets the value indicating whether operations should be interrupted. |
| thread_local_instance [static] | [IInterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/iinterruptmonitor/) | r/w | Gets or sets the IInterruptMonitor instance which is unique for each thread. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| interrupt() | Sends a request to interrupt operations. |


### Constructor: InterruptMonitor() {#InterruptMonitor__1}


```
 InterruptMonitor() 
```

The IInterruptMonitor instance which is unique for each thread.

