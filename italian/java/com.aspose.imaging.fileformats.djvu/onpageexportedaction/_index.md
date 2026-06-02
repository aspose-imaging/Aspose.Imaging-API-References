---
title: "OnPageExportedAction"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Delegato per l'attivazione quando la pagina è esportata"
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.djvu/onpageexportedaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class OnPageExportedAction extends System.MulticastDelegate
```

Delegato per l'attivazione quando la pagina è esportata
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OnPageExportedAction()](#OnPageExportedAction--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke(DjvuPage page)](#invoke-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Delegato per l'attivazione quando la pagina è esportata |
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


Delegato per l'attivazione quando la pagina è esportata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | La pagina a cui è stata esportata |

### beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.fileformats.djvu.DjvuPage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) |  |
| callback | com.aspose.ms.System.AsyncCallback |  |
| stato | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| risultato | com.aspose.ms.System.IAsyncResult |  |

