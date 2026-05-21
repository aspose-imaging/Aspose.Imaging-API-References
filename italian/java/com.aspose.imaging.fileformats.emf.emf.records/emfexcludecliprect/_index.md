---
title: "EmfExcludeClipRect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_EXCLUDECLIPRECT specifica una nuova regione di ritaglio che consiste nella regione di ritaglio esistente meno il rettangolo specificato."
type: docs
weight: 50
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

Il record EMR\_EXCLUDECLIPRECT specifica una nuova regione di ritaglio che consiste nella regione di ritaglio esistente meno il rettangolo specificato. Nota: i campi che non sono descritti in questa sezione sono specificati nella sezione 2.3.2.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfExcludeClipRect`. |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | Inizializza una nuova istanza della classe `EmfExcludeClipRect`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getClip()](#getClip--) | Ottiene un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di ritaglio in unità logiche. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di ritaglio in unità logiche. |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfExcludeClipRect`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


Inizializza una nuova istanza della classe `EmfExcludeClipRect`.

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Ottiene un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di ritaglio in unità logiche.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di ritaglio in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

