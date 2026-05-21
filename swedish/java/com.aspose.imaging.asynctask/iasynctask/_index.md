---
title: "IAsyncTask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den asynkrona uppgiften."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.asynctask/iasynctask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Den asynkrona uppgiften.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar händelsehanteraren för framsteg för den asynkrona uppgiften. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Ställer in händelsehanteraren för framsteg för den asynkrona uppgiften. |
| [isBusy()](#isBusy--) | Hämtar ett värde som indikerar om denna uppgift för närvarande körs. |
| [isCanceled()](#isCanceled--) | Hämtar ett värde som indikerar om denna uppgift avbröts. |
| [isFaulted()](#isFaulted--) | Hämtar ett värde som indikerar om denna uppgift misslyckades. |
| [getError()](#getError--) | Hämtar uppgiftsfelet som är tillgängligt efter att uppgiften har slutförts. |
| [getResult()](#getResult--) | Hämtar resultatet av denna uppgift. |
| [runAsync()](#runAsync--) | Kör denna uppgift. |
| [runAsync(int priority)](#runAsync-int-) | Kör denna uppgift. |
| [cancel()](#cancel--) | Avbryter denna uppgift. |
| [abort()](#abort--) | Avbryter denna uppgift. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-) | Ställer in delegaten för slutförande‑återanropet. |
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Hämtar händelsehanteraren för framsteg för den asynkrona uppgiften.

Värde: Händelsehanteraren för framsteg för den asynkrona uppgiften.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler of the asynchronous task.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Ställer in händelsehanteraren för framsteg för den asynkrona uppgiften.

Värde: Händelsehanteraren för framsteg för den asynkrona uppgiften.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | händelsehanteraren för framsteg för den asynkrona uppgiften. |

### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Hämtar ett värde som indikerar om denna uppgift för närvarande körs.

Värde: `true` om denna uppgift för närvarande körs; annars `false`.

**Returns:**
boolean – ett värde som indikerar om denna uppgift för närvarande körs.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Hämtar ett värde som indikerar om denna uppgift avbröts.

Värde: `true` om denna uppgift avbröts; annars `false`.

**Returns:**
boolean - ett värde som indikerar om denna uppgift avbröts.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Hämtar ett värde som indikerar om denna uppgift misslyckades.

Värde: `true` om denna uppgift hade fel; annars, `false`.

**Returns:**
boolean - ett värde som indikerar om denna uppgift hade fel.
### getError() {#getError--}
```
public abstract Throwable getError()
```


Hämtar uppgiftsfelet som är tillgängligt efter att uppgiften har slutförts.

Värde: Uppgiftens fel.

**Returns:**
java.lang.Throwable - uppgiftens fel som är tillgängligt efter att uppgiften har slutförts.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Hämtar resultatet av denna uppgift.

Värde: Resultatet av denna uppgift.

**Returns:**
java.lang.Object - resultatet av denna uppgift.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Kör denna uppgift.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Kör denna uppgift.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prioritet | int | Trådens prioritet. |

### cancel() {#cancel--}
```
public abstract void cancel()
```


Avbryter denna uppgift. Uppgiften slutförs säkert genom en kontrollerad stoppning av algoritmen.

### abort() {#abort--}
```
public abstract void abort()
```


Avbryter denna uppgift. Uppgiften slutförs omedelbart, med risken att interna ohanterade resurser inte frigörs.

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Ställer in delegaten för slutförande‑återanropet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.imaging.asynctask/completecallback) | Den kompletta callbacken. |

