---
title: "ProgressEventHandler"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "مرجع دالة معالج حدث التقدم"
type: docs
weight: 88
url: /ar/java/com.aspose.imaging/progresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProgressEventHandler extends System.MulticastDelegate
```

مرجع دالة معالج حدث التقدم
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ProgressEventHandler()](#ProgressEventHandler--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [invoke(ProgressEventHandlerInfo info)](#invoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-) | مرجع دالة معالج حدث التقدم |
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


مرجع دالة معالج حدث التقدم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) | بيانات معالج حدث التقدم. |

### beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(ProgressEventHandlerInfo info, System.AsyncCallback callback, Object state)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| info | [ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) |  |
| استدعاء | com.aspose.ms.System.AsyncCallback |  |
| الحالة | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النتيجة | com.aspose.ms.System.IAsyncResult |  |

