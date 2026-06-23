---
title: "IMaskingAsyncTask"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示遮罩异步任务。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.masking/imaskingasynctask/
---
**All Implemented Interfaces:**
[com.aspose.imaging.asynctask.IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask)
```
public interface IMaskingAsyncTask extends IAsyncTask
```

表示遮罩异步任务。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMaskingResult()](#getMaskingResult--) | 返回掩码操作的结果。 |
| [getErrorString()](#getErrorString--) | 返回掩码操作的错误。 |
### getMaskingResult() {#getMaskingResult--}
```
public abstract MaskingResult getMaskingResult()
```


返回掩码操作的结果。

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - The result of this task.
### getErrorString() {#getErrorString--}
```
public abstract String getErrorString()
```


返回掩码操作的错误。

**Returns:**
java.lang.String - 任务错误。
