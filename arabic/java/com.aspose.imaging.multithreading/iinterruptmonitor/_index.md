---
title: "IInterruptMonitor"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل معلومات حول الانقطاع."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.multithreading/iinterruptmonitor/
---```
public interface IInterruptMonitor
```

Represents information about interruption.
## Methods

| Method | Description |
| --- | --- |
| [isInterrupted()](#isInterrupted--) | Gets the value indicating whether operations should be interrupted. |
| [interrupt()](#interrupt--) | Sends a request to interrupt operations. |
### isInterrupted() {#isInterrupted--}
```
public abstract boolean isInterrupted()
```


Gets the value indicating whether operations should be interrupted.

**Returns:**
boolean - the value indicating whether operations should be interrupted.
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Sends a request to interrupt operations.

