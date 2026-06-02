---
title: "IAsyncTask"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il task asincrono."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.asynctask/iasynctask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Il task asincrono.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene il gestore dell'evento di avanzamento dell'attività asincrona. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Imposta il gestore dell'evento di avanzamento dell'attività asincrona. |
| [isBusy()](#isBusy--) | Ottiene un valore che indica se questa attività è attualmente in esecuzione. |
| [isCanceled()](#isCanceled--) | Ottiene un valore che indica se questa attività è stata annullata. |
| [isFaulted()](#isFaulted--) | Ottiene un valore che indica se questa attività ha generato un errore. |
| [getError()](#getError--) | Ottiene l'errore dell'attività disponibile dopo il completamento dell'attività. |
| [getResult()](#getResult--) | Ottiene il risultato di questa attività. |
| [runAsync()](#runAsync--) | Esegue questa attività. |
| [runAsync(int priority)](#runAsync-int-) | Esegue questa attività. |
| [cancel()](#cancel--) | Annulla questa attività. |
| [abort()](#abort--) | Interrompe questa attività. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-) | Imposta il delegato di callback di completamento. |
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Ottiene il gestore dell'evento di avanzamento dell'attività asincrona.

Valore: Il gestore dell'evento di avanzamento dell'attività asincrona.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler of the asynchronous task.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Imposta il gestore dell'evento di avanzamento dell'attività asincrona.

Valore: Il gestore dell'evento di avanzamento dell'attività asincrona.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | il gestore dell'evento di avanzamento dell'attività asincrona. |

### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Ottiene un valore che indica se questa attività è attualmente in esecuzione.

Valore: `true` se questa attività è attualmente in esecuzione; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questa attività è attualmente in esecuzione.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Ottiene un valore che indica se questa attività è stata annullata.

Valore: `true` se questa attività è stata annullata; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questa attività è stata annullata.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Ottiene un valore che indica se questa attività ha generato un errore.

Valore: `true` se questa attività è fallita; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questa attività è fallita.
### getError() {#getError--}
```
public abstract Throwable getError()
```


Ottiene l'errore dell'attività disponibile dopo il completamento dell'attività.

Valore: L'errore del task.

**Returns:**
java.lang.Throwable - l'errore del task disponibile dopo il completamento del task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Ottiene il risultato di questa attività.

Valore: Il risultato di questo task.

**Returns:**
java.lang.Object - il risultato di questo task.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Esegue questa attività.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Esegue questa attività.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| priorità | int | La priorità del thread. |

### cancel() {#cancel--}
```
public abstract void cancel()
```


Annulla questa attività. Il task è completato in modo sicuro mediante l'arresto controllato dell'algoritmo.

### abort() {#abort--}
```
public abstract void abort()
```


Interrompe questa attività. Il task è completato immediatamente, con il rischio di non liberare le risorse interne non gestite.

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Imposta il delegato di callback di completamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.imaging.asynctask/completecallback) | Il callback di completamento. |

