---
title: "Класс IAsyncTask"
type: docs
weight: 30
url: /ru/python-net/aspose.imaging.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Возвращает значение, указывающее, выполняется ли эта задача в данный момент. |
| is_canceled | bool | r | Возвращает значение, указывающее, была ли эта задача отменена. |
| is_faulted | bool | r | Возвращает значение, указывающее, произошла ли ошибка в этой задаче. |
| result | System.Object | r | Возвращает результат этой задачи. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Прерывает эту задачу.<br/>            Задача завершается немедленно, с риском не освобождения внутренних неуправляемых ресурсов. |
| cancel() | Отменяет эту задачу.<br/>            Задача завершается безопасно за счёт контролируемой остановки алгоритма. |
| run_async() | Запускает эту задачу. |
| wait_on_done() | Ожидает, пока задача не будет завершена. |


