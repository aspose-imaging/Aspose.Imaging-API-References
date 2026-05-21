---
title: "EmfIntersectClipRect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_INTERSECTCLIPRECT specifica una nuova regione di ritaglio dall'intersezione della regione di ritaglio corrente e del rettangolo specificato."
type: docs
weight: 66
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

Il record EMR\_INTERSECTCLIPRECT specifica una nuova regione di ritaglio dall'intersezione della regione di ritaglio corrente e del rettangolo specificato. Nota: i campi non descritti in questa sezione sono specificati nella sezione 2.3.2.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfIntersectClipRect`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getClip()](#getClip--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo in unità logiche. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo in unità logiche. |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfIntersectClipRect`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo in unità logiche.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

