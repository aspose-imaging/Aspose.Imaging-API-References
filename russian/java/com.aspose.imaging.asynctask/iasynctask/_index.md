---
title: "IAsyncTask"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Асинхронная задача."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.asynctask/iasynctask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Асинхронная задача.
## Методы

| Метод | Описание |
| --- | --- |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает обработчик события прогресса асинхронной задачи. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Устанавливает обработчик события прогресса асинхронной задачи. |
| [isBusy()](#isBusy--) | Получает значение, указывающее, выполняется ли эта задача в данный момент. |
| [isCanceled()](#isCanceled--) | Получает значение, указывающее, была ли эта задача отменена. |
| [isFaulted()](#isFaulted--) | Получает значение, указывающее, завершилась ли эта задача с ошибкой. |
| [getError()](#getError--) | Получает ошибку задачи, доступную после её завершения. |
| [getResult()](#getResult--) | Получает результат этой задачи. |
| [runAsync()](#runAsync--) | Запускает эту задачу. |
| [runAsync(int priority)](#runAsync-int-) | Запускает эту задачу. |
| [cancel()](#cancel--) | Отменяет эту задачу. |
| [abort()](#abort--) | Прерывает эту задачу. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-) | Устанавливает делегат обратного вызова завершения. |
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Получает обработчик события прогресса асинхронной задачи.

Значение: Обработчик события прогресса асинхронной задачи.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler of the asynchronous task.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Устанавливает обработчик события прогресса асинхронной задачи.

Значение: Обработчик события прогресса асинхронной задачи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | обработчик события прогресса асинхронной задачи. |

### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Получает значение, указывающее, выполняется ли эта задача в данный момент.

Значение: `true`, если эта задача в данный момент выполняется; иначе `false`.

**Returns:**
boolean - значение, указывающее, выполняется ли эта задача в данный момент.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Получает значение, указывающее, была ли эта задача отменена.

Значение: `true`, если эта задача была отменена; иначе `false`.

**Returns:**
boolean - значение, указывающее, была ли эта задача отменена.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Получает значение, указывающее, завершилась ли эта задача с ошибкой.

Значение: `true`, если эта задача завершилась с ошибкой; иначе `false`.

**Returns:**
boolean - значение, указывающее, завершилась ли эта задача с ошибкой.
### getError() {#getError--}
```
public abstract Throwable getError()
```


Получает ошибку задачи, доступную после её завершения.

Значение: Ошибка задачи.

**Returns:**
java.lang.Throwable - ошибка задачи, доступная после завершения задачи.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Получает результат этой задачи.

Значение: Результат этой задачи.

**Returns:**
java.lang.Object - результат этой задачи.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Запускает эту задачу.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Запускает эту задачу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| приоритет | int | Приоритет потока. |

### cancel() {#cancel--}
```
public abstract void cancel()
```


Отменяет эту задачу. Задача завершается безопасно за счёт контролируемой остановки алгоритма.

### abort() {#abort--}
```
public abstract void abort()
```


Прерывает эту задачу. Задача завершается немедленно, с риском не освобождения внутренних неуправляемых ресурсов.

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.imaging.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Устанавливает делегат обратного вызова завершения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.imaging.asynctask/completecallback) | Обратный вызов завершения. |

