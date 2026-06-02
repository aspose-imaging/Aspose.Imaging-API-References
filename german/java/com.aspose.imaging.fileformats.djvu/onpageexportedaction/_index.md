---
title: "OnPageExportedAction"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Delegat, der ausgelöst wird, wenn die Seite exportiert wird"
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.djvu/onpageexportedaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class OnPageExportedAction extends System.MulticastDelegate
```

Delegat, der ausgelöst wird, wenn die Seite exportiert wird
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OnPageExportedAction()](#OnPageExportedAction--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [invoke(DjvuPage page)](#invoke-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Delegat, der ausgelöst wird, wenn die Seite exportiert wird |
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


Delegat, der ausgelöst wird, wenn die Seite exportiert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | Die Seite, zu der exportiert wurde |

### beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state) {#beginInvoke-com.aspose.imaging.fileformats.djvu.DjvuPage-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public final System.IAsyncResult beginInvoke(DjvuPage page, System.AsyncCallback callback, Object state)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) |  |
| Rückruf | com.aspose.ms.System.AsyncCallback |  |
| Zustand | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### endInvoke(System.IAsyncResult result) {#endInvoke-com.aspose.ms.System.IAsyncResult-}
```
public final void endInvoke(System.IAsyncResult result)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ergebnis | com.aspose.ms.System.IAsyncResult |  |

