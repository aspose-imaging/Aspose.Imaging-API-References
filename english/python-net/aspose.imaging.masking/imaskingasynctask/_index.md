---
title: IMaskingAsyncTask Class
type: docs
weight: 60
url: /python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_busy | bool | r | Gets a value indicating whether this task is currently running. |
| is_canceled | bool | r | Gets a value indicating whether this task was canceled. |
| is_faulted | bool | r | Gets a value indicating whether this task was faulted. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| abort() | Aborts this task.<br/>            The task is completed immediately, with the risk of not freeing internal unmanaged resources. |
| cancel() | Cancels this task.<br/>            The task is completed safely by the controlled stopping of the algorithm. |
| [get_error()](#get_error__1) | Returns an error of masking operation |
| [get_masking_result()](#get_masking_result__2) | Returns the result of masking operation |
| run_async() | Runs this task. |
| wait_on_done() | Waits until task is finished. |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

Returns an error of masking operation

**Returns**

| Type | Description |
| :- | :- |
| string | The task error. |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

Returns the result of masking operation

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | The result of this task. |


