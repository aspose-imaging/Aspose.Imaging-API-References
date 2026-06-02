---
title: "OnPageExportedAction"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Delegado que se dispara cuando la página se exporta"
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.djvu/onpageexportedaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class OnPageExportedAction extends System.MulticastDelegate
```

Delegado que se dispara cuando la página se exporta
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OnPageExportedAction()](#OnPageExportedAction--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(DjvuPage page)](#invoke-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Delegado que se dispara cuando la página se exporta |
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


Delegado que se dispara cuando la página se exporta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | La página a la que se exportó |

### beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.fileformats.djvu.DjvuPage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| estado | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resultado | com.aspose.ms.System.IAsyncResult |  |

