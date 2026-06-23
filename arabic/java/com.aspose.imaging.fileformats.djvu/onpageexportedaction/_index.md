---
title: "OnPageExportedAction"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "مفوض لتفعيل عندما يتم تصدير الصفحة"
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.djvu/onpageexportedaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class OnPageExportedAction extends System.MulticastDelegate
```

مفوض لتفعيل عندما يتم تصدير الصفحة
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OnPageExportedAction()](#OnPageExportedAction--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [invoke(DjvuPage page)](#invoke-com.aspose.imaging.fileformats.djvu.DjvuPage-) | مفوض لتفعيل عندما يتم تصدير الصفحة |
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


مفوض لتفعيل عندما يتم تصدير الصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | الصفحة التي تم تصديرها إلى |

### beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.fileformats.djvu.DjvuPage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) |  |
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

