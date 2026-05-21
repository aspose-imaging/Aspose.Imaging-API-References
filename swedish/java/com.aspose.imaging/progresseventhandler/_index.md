---
title: "ProgressEventHandler"
second_title: "Aspose.Imaging för Java API-referens"
description: "Referens till funktionshanterare för förloppshändelse."
type: docs
weight: 88
url: /sv/java/com.aspose.imaging/progresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProgressEventHandler extends System.MulticastDelegate
```

Referens till funktionshanterare för förloppshändelse.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ProgressEventHandler()](#ProgressEventHandler--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(ProgressEventHandlerInfo info)](#invoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-) | Referens till funktionshanterare för förloppshändelse. |
| [beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### ProgressEventHandler() {#ProgressEventHandler--}
```
public ProgressEventHandler()
```


### invoke(ProgressEventHandlerInfo info) {#invoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-}
```
public abstract void invoke(ProgressEventHandlerInfo info)
```


Referens till funktionshanterare för förloppshändelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) | Data för progress‑händelsehanteraren. |

### beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) |  |
| återanrop | com.aspose.ms.System.AsyncCallback |  |
| tillstånd | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resultat | com.aspose.ms.System.IAsyncResult |  |

