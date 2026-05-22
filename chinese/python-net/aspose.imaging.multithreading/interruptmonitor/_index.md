---
title: "InterruptMonitor 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.multithreading/interruptmonitor/
---

**Summary:** Represents information about interruption.

**Module:** [aspose.imaging.multithreading](/imaging/python-net/aspose.imaging.multithreading/)

**Full Name:** aspose.imaging.multithreading.InterruptMonitor

**Inheritance:** IInterruptMonitor

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [InterruptMonitor()](#InterruptMonitor__1) | 每个线程唯一的 IInterruptMonitor 实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| is_interrupted | bool | r | 获取指示是否应中断操作的值。 |
| thread_local_instance [static] | [IInterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/iinterruptmonitor/) | r/w | 获取或设置每个线程唯一的 IInterruptMonitor 实例。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| interrupt() | 发送请求以中断操作。 |


### Constructor: InterruptMonitor() {#InterruptMonitor__1}


```
 InterruptMonitor() 
```

每个线程唯一的 IInterruptMonitor 实例。

