---
title: "ProgressEventHandler"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Referenz zur Fortschritts‑Event‑Handler‑Funktion"
type: docs
weight: 88
url: /de/java/com.aspose.imaging/progresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProgressEventHandler extends System.MulticastDelegate
```

Referenz zur Fortschritts‑Event‑Handler‑Funktion
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ProgressEventHandler()](#ProgressEventHandler--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(ProgressEventHandlerInfo info)](#invoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-) | Referenz zur Fortschritts‑Event‑Handler‑Funktion |
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


Referenz zur Fortschritts‑Event‑Handler‑Funktion

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) | Die Daten des Fortschritts-Ereignishandlers. |

### beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) |  |
| Rückruf | com.aspose.ms.System.AsyncCallback |  |
| Zustand | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ergebnis | com.aspose.ms.System.IAsyncResult |  |

