---
title: "AsyncTaskFunc"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "المندوب الخاص بالعملية الطويلة للمهمة غير المتزامنة مع نتيجة من نوع عام."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.asynctask/asynctaskfunc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AsyncTaskFunc extends System.MulticastDelegate
```

المندوب الخاص بالعملية الطويلة للمهمة غير المتزامنة مع نتيجة من نوع عام.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [AsyncTaskFunc()](#AsyncTaskFunc--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [invoke(IAsyncTaskState taskState)](#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-) | المندوب الخاص بالعملية الطويلة للمهمة غير المتزامنة مع نتيجة من نوع عام. |
| [beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)](#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [endInvoke(System.IAsyncResult result)](#endInvoke-com.aspose.ms.System.IAsyncResult-) |  |
### AsyncTaskFunc() {#AsyncTaskFunc--}
```
public AsyncTaskFunc()
```


### invoke(IAsyncTaskState taskState) {#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-}
```
public abstract Object invoke(IAsyncTaskState taskState)
```


المندوب الخاص بالعملية الطويلة للمهمة غير المتزامنة مع نتيجة من نوع عام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) | حالة المهمة غير المتزامنة. |

**Returns:**
java.lang.Object - نتيجة العملية الطويلة.
### beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) |  |
| استدعاء | com.aspose.ms.System.AsyncCallback |  |
| الحالة | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final Object endInvoke(System.IAsyncResult result)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النتيجة | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.Object
