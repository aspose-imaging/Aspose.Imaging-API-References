---
title: "AsyncTaskFunc"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Genel tip sonuçlu asenkron görev için uzun işlem temsilcisi."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.asynctask/asynctaskfunc/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class AsyncTaskFunc extends System.MulticastDelegate
```

Genel tip sonuçlu asenkron görev için uzun işlem temsilcisi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AsyncTaskFunc()](#AsyncTaskFunc--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [invoke(IAsyncTaskState taskState)](#invoke-com.aspose.imaging.asynctask.IAsyncTaskState-) | Genel tip sonuçlu asenkron görev için uzun işlem temsilcisi. |
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


Genel tip sonuçlu asenkron görev için uzun işlem temsilcisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) | Asenkron görevin durumu. |

**Returns:**
java.lang.Object - uzun işlemin sonucu.
### beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.asynctask.IAsyncTaskState-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(IAsyncTaskState taskState, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| taskState | [IAsyncTaskState](../../com.aspose.imaging.asynctask/iasynctaskstate) |  |
| geri çağırma | com.aspose.ms.System.AsyncCallback |  |
| durum | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final Object endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sonuç | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
java.lang.Object
