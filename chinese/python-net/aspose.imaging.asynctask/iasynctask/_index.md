---
title: "IAsyncTask 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.imaging.asynctask](/imaging/python-net/aspose.imaging.asynctask/)

**Full Name:** aspose.imaging.asynctask.IAsyncTask

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| is_busy | bool | r | 获取一个值，指示此任务当前是否正在运行。 |
| is_canceled | bool | r | 获取一个值，指示此任务是否已被取消。 |
| is_faulted | bool | r | 获取一个值，指示此任务是否已出现错误。 |
| result | System.Object | r | 获取此任务的结果。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| abort() | 中止此任务。<br/>            任务会立即完成，但有可能未释放内部的非托管资源。 |
| cancel() | 取消此任务。<br/>            任务通过受控停止算法安全完成。 |
| run_async() | 运行此任务。 |
| wait_on_done() | 等待任务完成。 |


