---
title: "AsyncTask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الفئة الثابتة للمصنع لإنشاء المهام غير المتزامنة"
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.asynctask/asynctask/
---
**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

الفئة الثابتة للمصنع لإنشاء المهام غير المتزامنة
## الطرق

| طريقة | الوصف |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.imaging.asynctask.AsyncTaskAction-) | ينشئ المهمة غير المتزامنة بدون أي نتيجة. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.imaging.asynctask.AsyncTaskFunc-) | ينشئ المهمة غير المتزامنة مع نتيجة من نوع عام. |
### create(AsyncTaskAction taskAction) {#create-com.aspose.imaging.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


ينشئ المهمة غير المتزامنة بدون أي نتيجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.imaging.asynctask/asynctaskaction) | إجراء المهمة. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.imaging.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


ينشئ المهمة غير المتزامنة مع نتيجة من نوع عام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.imaging.asynctask/asynctaskfunc) | دالة المهمة. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
