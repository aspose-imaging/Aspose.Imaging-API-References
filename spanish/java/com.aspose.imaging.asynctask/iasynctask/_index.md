---
title: "IAsyncTask"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La tarea asíncrona."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.asynctask/iasynctask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

La tarea asíncrona.
## Métodos

| Método | Descripción |
| --- | --- |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene el controlador de eventos de progreso de la tarea asíncrona. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Establece el controlador de eventos de progreso de la tarea asíncrona. |
| [isBusy()](#isBusy--) | Obtiene un valor que indica si esta tarea está en ejecución. |
| [isCanceled()](#isCanceled--) | Obtiene un valor que indica si esta tarea fue cancelada. |
| [isFaulted()](#isFaulted--) | Obtiene un valor que indica si esta tarea falló. |
| [getError()](#getError--) | Obtiene el error de la tarea que está disponible después de que la tarea se complete. |
| [getResult()](#getResult--) | Obtiene el resultado de esta tarea. |
| [runAsync()](#runAsync--) | Ejecuta esta tarea. |
| [runAsync(int priority)](#runAsync-int-) | Ejecuta esta tarea. |
| [cancel()](#cancel--) | Cancela esta tarea. |
| [abort()](#abort--) | Aborta esta tarea. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-) | Establece el delegado de devolución de llamada de finalización. |
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Obtiene el controlador de eventos de progreso de la tarea asíncrona.

Valor: El controlador de eventos de progreso de la tarea asíncrona.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler of the asynchronous task.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Establece el controlador de eventos de progreso de la tarea asíncrona.

Valor: El controlador de eventos de progreso de la tarea asíncrona.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | el controlador de eventos de progreso de la tarea asíncrona. |

### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Obtiene un valor que indica si esta tarea está en ejecución.

Valor: `true` si esta tarea está en ejecución; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si esta tarea está en ejecución.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Obtiene un valor que indica si esta tarea fue cancelada.

Valor: `true` si esta tarea fue cancelada; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si esta tarea fue cancelada.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Obtiene un valor que indica si esta tarea falló.

Valor: `true` si esta tarea tuvo un error; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si esta tarea tuvo un error.
### getError() {#getError--}
```
public abstract Throwable getError()
```


Obtiene el error de la tarea que está disponible después de que la tarea se complete.

Valor: El error de la tarea.

**Returns:**
java.lang.Throwable - el error de la tarea que está disponible después de que la tarea se completa.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Obtiene el resultado de esta tarea.

Valor: El resultado de esta tarea.

**Returns:**
java.lang.Object - el resultado de esta tarea.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Ejecuta esta tarea.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Ejecuta esta tarea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prioridad | int | La prioridad del hilo. |

### cancel() {#cancel--}
```
public abstract void cancel()
```


Cancela esta tarea. La tarea se completa de forma segura mediante la detención controlada del algoritmo.

### abort() {#abort--}
```
public abstract void abort()
```


Abortar esta tarea. La tarea se completa inmediatamente, con el riesgo de no liberar recursos internos no administrados.

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Establece el delegado de devolución de llamada de finalización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.imaging.asynctask/completecallback) | La devolución de llamada completa. |

