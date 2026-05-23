---
title: "Класс InterruptMonitor"
type: docs
weight: 20
url: /ru/python-net/aspose.imaging.multithreading/interruptmonitor/
---

**Summary:** Represents information about interruption.

**Module:** [aspose.imaging.multithreading](/imaging/python-net/aspose.imaging.multithreading/)

**Full Name:** aspose.imaging.multithreading.InterruptMonitor

**Inheritance:** IInterruptMonitor

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [InterruptMonitor()](#InterruptMonitor__1) | Экземпляр IInterruptMonitor, уникальный для каждого потока. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_interrupted | bool | r | Получает значение, указывающее, следует ли прерывать операции. |
| thread_local_instance [static] | [IInterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/iinterruptmonitor/) | r/w | Получает или задает экземпляр IInterruptMonitor, уникальный для каждого потока. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| interrupt() | Отправляет запрос на прерывание операций. |


### Constructor: InterruptMonitor() {#InterruptMonitor__1}


```
 InterruptMonitor() 
```

Экземпляр IInterruptMonitor, уникальный для каждого потока.

