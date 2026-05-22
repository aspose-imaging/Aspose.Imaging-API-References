---
title: "IMockingAsyncTask 类"
type: docs
weight: 60
url: /zh/python-net/aspose.imaging.masking/imaskingasynctask/
---

**Summary:** Represents the masking async task.

**Module:** [aspose.imaging.masking](/imaging/python-net/aspose.imaging.masking/)

**Full Name:** aspose.imaging.masking.IMaskingAsyncTask

**Inheritance:** IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| is_busy | bool | r | 获取一个值，指示此任务当前是否正在运行。 |
| is_canceled | bool | r | 获取一个值，指示此任务是否已被取消。 |
| is_faulted | bool | r | 获取一个值，指示此任务是否已出现错误。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| abort() | 中止此任务。<br/>            任务会立即完成，但有可能未释放内部的非托管资源。 |
| cancel() | 取消此任务。<br/>            任务通过受控停止算法安全完成。 |
| [get_error()](#get_error__1) | 返回掩码操作的错误 |
| [get_masking_result()](#get_masking_result__2) | 返回掩码操作的结果 |
| run_async() | 运行此任务。 |
| wait_on_done() | 等待任务完成。 |


### Method: get_error() {#get_error__1}


```
 get_error() 
```

返回掩码操作的错误

**Returns**

| Type | Description |
| :- | :- |
| string | 任务错误。 |


### Method: get_masking_result() {#get_masking_result__2}


```
 get_masking_result() 
```

返回掩码操作的结果

**Returns**

| Type | Description |
| :- | :- |
| [MaskingResult](/imaging/python-net/aspose.imaging.masking.result/maskingresult/) | 此任务的结果。 |


