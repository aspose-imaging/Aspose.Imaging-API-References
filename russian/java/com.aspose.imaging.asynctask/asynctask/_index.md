---
title: "AsyncTask"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Статический фабричный класс для создания асинхронных задач"
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.asynctask/asynctask/
---
**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

Статический фабричный класс для создания асинхронных задач
## Методы

| Метод | Описание |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.imaging.asynctask.AsyncTaskAction-) | Создаёт асинхронную задачу без результата. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.imaging.asynctask.AsyncTaskFunc-) | Создаёт асинхронную задачу с результатом обобщённого типа. |
### create(AsyncTaskAction taskAction) {#create-com.aspose.imaging.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


Создаёт асинхронную задачу без результата.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.imaging.asynctask/asynctaskaction) | Действие задачи. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.imaging.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Создаёт асинхронную задачу с результатом обобщённого типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.imaging.asynctask/asynctaskfunc) | Функция задачи. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
