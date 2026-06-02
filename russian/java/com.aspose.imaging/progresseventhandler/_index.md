---
title: "ProgressEventHandler"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Ссылка на функцию обработчика события прогресса"
type: docs
weight: 88
url: /ru/java/com.aspose.imaging/progresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProgressEventHandler extends System.MulticastDelegate
```

Ссылка на функцию обработчика события прогресса
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ProgressEventHandler()](#ProgressEventHandler--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [invoke(ProgressEventHandlerInfo info)](#invoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-) | Ссылка на функцию обработчика события прогресса |
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


Ссылка на функцию обработчика события прогресса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) | Данные обработчика события прогресса. |

### beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| результат | com.aspose.ms.System.IAsyncResult |  |

