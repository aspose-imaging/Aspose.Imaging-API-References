---
title: "OnPageExportedAction"
second_title: "Aspose.Imaging för Java API-referens"
description: "Delegat för att utlösas när sidan exporteras"
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.djvu/onpageexportedaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class OnPageExportedAction extends System.MulticastDelegate
```

Delegat för att utlösas när sidan exporteras
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OnPageExportedAction()](#OnPageExportedAction--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [invoke(DjvuPage page)](#invoke-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Delegat för att utlösas när sidan exporteras |
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


Delegat för att utlösas när sidan exporteras

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | Sidan som exporterades till |

### beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.fileformats.djvu.DjvuPage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) |  |
| återanrop | com.aspose.ms.System.AsyncCallback |  |
| tillstånd | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resultat | com.aspose.ms.System.IAsyncResult |  |

