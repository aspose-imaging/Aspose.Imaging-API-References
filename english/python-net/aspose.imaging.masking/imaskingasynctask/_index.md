---
title: IMaskingAsyncTask Class
type: docs
weight: 60
url: /python-net/aspose.imaging.masking/imaskingasynctask/
---

Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

**Aspose.Imaging Version:** 23.6

The IMaskingAsyncTask type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| is_busy | bool | r | Gets a value indicating whether this task is currently running. |
| is_canceled | bool | r | Gets a value indicating whether this task was canceled. |
| is_faulted | bool | r | Gets a value indicating whether this task was faulted. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_masking_result()](#get_masking_result__0) | Returns the result of masking operation |
| [get_error()](#get_error__1) | Returns an error of masking operation |
| run_async() | Runs this task. |
| cancel() | Cancels this task.<br/>            The task is completed safely by the controlled stopping of the algorithm. |
| abort() | Aborts this task.<br/>            The task is completed immediately, with the risk of not freeing internal unmanaged resources. |
| wait_on_done() | Waits until task is finished. |

### get_masking_result() {#get_masking_result__0}


```
 get_masking_result() 
```

Returns the result of masking operation

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | The result of this task. |


### get_error() {#get_error__1}


```
 get_error() 
```

Returns an error of masking operation

**Returns**

| Type | Description |
| :- | :- |
| string | The task error. |


