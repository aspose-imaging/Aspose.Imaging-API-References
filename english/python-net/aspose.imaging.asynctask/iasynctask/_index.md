---
title: IAsyncTask Class
type: docs
weight: 30
url: /python-net/aspose.imaging.asynctask/iasynctask/
---

The asynchronous task.

**Namespace:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Class Name:** aspose.imaging.asynctask.IAsyncTask

**Assembly:**  Aspose.Imaging Version: 23.5.6

The IAsyncTask type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|is_busy|Gets a value indicating whether this task is currently running.|
|is_canceled|Gets a value indicating whether this task was canceled.|
|is_faulted|Gets a value indicating whether this task was faulted.|
|result|Gets the result of this task.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|run_async()|Runs this task.|
|cancel()|Cancels this task.<br/>            The task is completed safely by the controlled stopping of the algorithm.|
|abort()|Aborts this task.<br/>            The task is completed immediately, with the risk of not freeing internal unmanaged resources.|
|wait_on_done()|Waits until task is finished.|
