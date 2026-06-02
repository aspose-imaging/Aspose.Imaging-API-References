---
title: "EmfOffsetClipRgn"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_OFFSETCLIPRGN sposta la regione di ritaglio corrente nel contesto del dispositivo di riproduzione degli offset specificati."
type: docs
weight: 78
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfOffsetClipRgn extends EmfClippingRecordType
```

Il record EMR\_OFFSETCLIPRGN sposta la regione di ritaglio corrente nel contesto del dispositivo di riproduzione degli offset specificati.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfOffsetClipRgn(EmfRecord source)](#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfOffsetClipRgn`. |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn--) | Inizializza una nuova istanza della classe `EmfOffsetClipRgn`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOffset()](#getOffset--) | Ottiene un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica gli offset orizzontali e verticali in unità logiche. |
| [setOffset(Point value)](#setOffset-com.aspose.imaging.Point-) | Imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica gli offset orizzontali e verticali in unità logiche. |
### EmfOffsetClipRgn(EmfRecord source) {#EmfOffsetClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfOffsetClipRgn(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfOffsetClipRgn`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfOffsetClipRgn() {#EmfOffsetClipRgn--}
```
public EmfOffsetClipRgn()
```


Inizializza una nuova istanza della classe `EmfOffsetClipRgn`.

### getOffset() {#getOffset--}
```
public Point getOffset()
```


Ottiene un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica gli offset orizzontali e verticali in unità logiche.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setOffset(Point value) {#setOffset-com.aspose.imaging.Point-}
```
public void setOffset(Point value)
```


Imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica gli offset orizzontali e verticali in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

