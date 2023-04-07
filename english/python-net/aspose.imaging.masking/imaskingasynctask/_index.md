---
title: IMaskingAsyncTask Class
type: docs
weight: 10
url: /python-net/api-reference/aspose.imaging.masking/imaskingasynctask/
---

Represents the masking async task.

**Namespace:** [aspose.imaging.masking](/imaging/python-net/api-reference/aspose.imaging.masking/)

**Full Class Name:** aspose.imaging.masking.IMaskingAsyncTask

**Assembly:**  Aspose.Imaging Version: 23.3.0

The IMaskingAsyncTask type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|is_busy|Gets a value indicating whether this task is currently running.|
|is_canceled|Gets a value indicating whether this task was canceled.|
|is_faulted|Gets a value indicating whether this task was faulted.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_masking_result()|Returns the result of masking operation|
|get_error()|Returns an error of masking operation|
|run_async()|Runs this task.|
|cancel()|Cancels this task.<br/>            The task is completed safely by the controlled stopping of the algorithm.|
|abort()|Aborts this task.<br/>            The task is completed immediately, with the risk of not freeing internal unmanaged resources.|
|wait_on_done()|Waits until task is finished.|
