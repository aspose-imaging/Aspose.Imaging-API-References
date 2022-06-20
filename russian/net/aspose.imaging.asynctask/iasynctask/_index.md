---
title: IAsyncTask
second_title: Справочник по Aspose.Imaging for .NET API
description: Асинхронная задача.
type: docs
weight: 100
url: /ru/net/aspose.imaging.asynctask/iasynctask/
---
## IAsyncTask interface

Асинхронная задача.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Error](../../aspose.imaging.asynctask/iasynctask/error) { get; } | Получает ошибку задачи, которая доступна после завершения задачи. |
| [IsBusy](../../aspose.imaging.asynctask/iasynctask/isbusy) { get; } | Получает значение, указывающее, выполняется ли в данный момент эта задача. |
| [IsCanceled](../../aspose.imaging.asynctask/iasynctask/iscanceled) { get; } | Получает значение, указывающее, была ли эта задача отменена. |
| [IsFaulted](../../aspose.imaging.asynctask/iasynctask/isfaulted) { get; } | Получает значение, указывающее, была ли эта задача ошибочной. |
| [ProgressEventHandler](../../aspose.imaging.asynctask/iasynctask/progresseventhandler) { get; set; } | Получает или задает обработчик событий выполнения асинхронной задачи. |
| [Result](../../aspose.imaging.asynctask/iasynctask/result) { get; } | Получает результат этой задачи. |

## Методы

| Имя | Описание |
| --- | --- |
| [Abort](../../aspose.imaging.asynctask/iasynctask/abort)() | Прерывает эту задачу. Задача выполняется немедленно, с риском не освободить внутренние неуправляемые ресурсы. |
| [Cancel](../../aspose.imaging.asynctask/iasynctask/cancel)() | Отменяет эту задачу. Задача безопасно завершается управляемой остановкой алгоритма. |
| [RunAsync](../../aspose.imaging.asynctask/iasynctask/runasync#runasync)() | Запускает эту задачу. |
| [RunAsync](../../aspose.imaging.asynctask/iasynctask/runasync#runasync_1)(ThreadPriority) | Запускает эту задачу. |
| [SetCompleteCallback](../../aspose.imaging.asynctask/iasynctask/setcompletecallback)(CompleteCallback) | Устанавливает полный делегат обратного вызова. |

### Смотрите также

* пространство имен [Aspose.Imaging.AsyncTask](../../aspose.imaging.asynctask)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->