---
title: "OnPageExportedAction"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Sayfa dışa aktarıldığında tetiklenecek temsilci"
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.djvu/onpageexportedaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class OnPageExportedAction extends System.MulticastDelegate
```

Sayfa dışa aktarıldığında tetiklenecek temsilci
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OnPageExportedAction()](#OnPageExportedAction--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [invoke(DjvuPage page)](#invoke-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Sayfa dışa aktarıldığında tetiklenecek temsilci |
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


Sayfa dışa aktarıldığında tetiklenecek temsilci

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | Dışa aktarılan sayfa. |

### beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.fileformats.djvu.DjvuPage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) |  |
| geri çağırma | com.aspose.ms.System.AsyncCallback |  |
| durum | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sonuç | com.aspose.ms.System.IAsyncResult |  |

