---
title: "IAsyncTask"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die asynchrone Aufgabe."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.asynctask/iasynctask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Die asynchrone Aufgabe.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ruft den Fortschritts-Event-Handler der asynchronen Aufgabe ab. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Setzt den Fortschritts-Event-Handler der asynchronen Aufgabe. |
| [isBusy()](#isBusy--) | Ruft einen Wert ab, der angibt, ob diese Aufgabe gerade ausgeführt wird. |
| [isCanceled()](#isCanceled--) | Ruft einen Wert ab, der angibt, ob diese Aufgabe abgebrochen wurde. |
| [isFaulted()](#isFaulted--) | Ruft einen Wert ab, der angibt, ob diese Aufgabe einen Fehler aufwies. |
| [getError()](#getError--) | Ruft den Aufgabenfehler ab, der nach Abschluss der Aufgabe verfügbar ist. |
| [getResult()](#getResult--) | Ruft das Ergebnis dieser Aufgabe ab. |
| [runAsync()](#runAsync--) | Führt diese Aufgabe aus. |
| [runAsync(int priority)](#runAsync-int-) | Führt diese Aufgabe aus. |
| [cancel()](#cancel--) | Bricht diese Aufgabe ab. |
| [abort()](#abort--) | Beendet diese Aufgabe. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-) | Setzt den Abschluss-Callback-Delegaten. |
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Ruft den Fortschritts-Event-Handler der asynchronen Aufgabe ab.

Wert: Der Fortschritts-Event-Handler der asynchronen Aufgabe.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler of the asynchronous task.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Setzt den Fortschritts-Event-Handler der asynchronen Aufgabe.

Wert: Der Fortschritts-Event-Handler der asynchronen Aufgabe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | der Fortschritts-Event-Handler der asynchronen Aufgabe. |

### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Ruft einen Wert ab, der angibt, ob diese Aufgabe gerade ausgeführt wird.

Wert: `true`, wenn diese Aufgabe gerade ausgeführt wird; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob diese Aufgabe gerade ausgeführt wird.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Ruft einen Wert ab, der angibt, ob diese Aufgabe abgebrochen wurde.

Wert: `true`, wenn diese Aufgabe abgebrochen wurde; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob diese Aufgabe abgebrochen wurde.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Ruft einen Wert ab, der angibt, ob diese Aufgabe einen Fehler aufwies.

Wert: `true`, wenn diese Aufgabe fehlerhaft war; andernfalls `false`.

**Returns:**
boolean - ein Wert, der angibt, ob diese Aufgabe fehlerhaft war.
### getError() {#getError--}
```
public abstract Throwable getError()
```


Ruft den Aufgabenfehler ab, der nach Abschluss der Aufgabe verfügbar ist.

Wert: Der Fehler der Aufgabe.

**Returns:**
java.lang.Throwable - der Aufgabenfehler, der nach Abschluss der Aufgabe verfügbar ist.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Ruft das Ergebnis dieser Aufgabe ab.

Wert: Das Ergebnis dieser Aufgabe.

**Returns:**
java.lang.Object - das Ergebnis dieser Aufgabe.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Führt diese Aufgabe aus.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Führt diese Aufgabe aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Priorität | int | Die Thread-Priorität. |

### cancel() {#cancel--}
```
public abstract void cancel()
```


Bricht diese Aufgabe ab. Die Aufgabe wird sicher abgeschlossen, indem der Algorithmus kontrolliert gestoppt wird.

### abort() {#abort--}
```
public abstract void abort()
```


Bricht diese Aufgabe sofort ab. Die Aufgabe wird sofort beendet, wobei das Risiko besteht, interne nicht verwaltete Ressourcen nicht freizugeben.

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Setzt den Abschluss-Callback-Delegaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.imaging.asynctask/completecallback) | Der Abschluss-Callback. |

