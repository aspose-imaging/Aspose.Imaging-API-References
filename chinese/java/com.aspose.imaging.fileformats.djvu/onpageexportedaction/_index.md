---
title: "OnPageExportedAction"
second_title: "Aspose.Imaging for Java API 参考"
description: "在页面导出时触发的委托"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.fileformats.djvu/onpageexportedaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class OnPageExportedAction extends System.MulticastDelegate
```

在页面导出时触发的委托
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OnPageExportedAction()](#OnPageExportedAction--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(DjvuPage page)](#invoke-com.aspose.imaging.fileformats.djvu.DjvuPage-) | 在页面导出时触发的委托 |
| [beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.imaging.fileformats.djvu.DjvuPage-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### OnPageExportedAction() {#OnPageExportedAction--}
```
public OnPageExportedAction()
```


### invoke(DjvuPage page) {#invoke-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public abstract void invoke(DjvuPage page)
```


在页面导出时触发的委托

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | 已导出到的页面 |

### beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.fileformats.djvu.DjvuPage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) |  |
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

