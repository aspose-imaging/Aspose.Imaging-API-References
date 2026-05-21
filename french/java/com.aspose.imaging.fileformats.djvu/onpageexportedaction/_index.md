---
title: "OnPageExportedAction"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Délégué déclenché lors de l'exportation de la page"
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.djvu/onpageexportedaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class OnPageExportedAction extends System.MulticastDelegate
```

Délégué déclenché lors de l'exportation de la page
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OnPageExportedAction()](#OnPageExportedAction--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(DjvuPage page)](#invoke-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Délégué déclenché lors de l'exportation de la page |
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


Délégué déclenché lors de l'exportation de la page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | La page vers laquelle elle a été exportée |

### beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.fileformats.djvu.DjvuPage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| state | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| résultat | com.aspose.ms.System.IAsyncResult |  |

