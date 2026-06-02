---
title: "AsyncTask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Asenkron görevleri oluşturmak için statik fabrika sınıfı"
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.asynctask/asynctask/
---
**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

Asenkron görevleri oluşturmak için statik fabrika sınıfı
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.imaging.asynctask.AsyncTaskAction-) | Herhangi bir sonuç olmadan asenkron görevi oluşturur. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.imaging.asynctask.AsyncTaskFunc-) | Genel tip sonuçlu asenkron görevi oluşturur. |
### create(AsyncTaskAction taskAction) {#create-com.aspose.imaging.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


Herhangi bir sonuç olmadan asenkron görevi oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.imaging.asynctask/asynctaskaction) | Görev eylemi. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.imaging.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Genel tip sonuçlu asenkron görevi oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.imaging.asynctask/asynctaskfunc) | Görev fonksiyonu. |

**Returns:**
[IAsyncTask](../../com.aspose.imaging.asynctask/iasynctask) - The asynchronous task
