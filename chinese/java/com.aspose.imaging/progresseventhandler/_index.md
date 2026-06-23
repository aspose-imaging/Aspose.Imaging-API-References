---
title: "ProgressEventHandler"
second_title: "Aspose.Imaging for Java API 参考"
description: "进度事件处理函数引用"
type: docs
weight: 88
url: /zh/java/com.aspose.imaging/progresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProgressEventHandler extends System.MulticastDelegate
```

进度事件处理函数引用
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ProgressEventHandler()](#ProgressEventHandler--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(ProgressEventHandlerInfo info)](#invoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-) | 进度事件处理函数引用 |
| [beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### ProgressEventHandler() {#ProgressEventHandler--}
```
public ProgressEventHandler()
```


### invoke(ProgressEventHandlerInfo info) {#invoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-}
```
public abstract void invoke(ProgressEventHandlerInfo info)
```


进度事件处理函数引用

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) | 进度事件处理程序数据。 |

### beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) |  |
| 回调 | com.aspose.ms.System.AsyncCallback |  |
| 状态 | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 结果 | com.aspose.ms.System.IAsyncResult |  |

