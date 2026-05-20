---
title: "EmfPlusSetClipRect"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusSetClipRect combina la regione di ritaglio corrente con un rettangolo."
type: docs
weight: 56
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

Il record EmfPlusSetClipRect combina la regione di ritaglio corrente con un rettangolo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusSetClipRect`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCm()](#getCm--) | Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. |
| [setCm(byte value)](#setCm-byte-) | Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. |
| [getClipRect()](#getClipRect--) | Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce il rettangolo da utilizzare nell'operazione CombineMode. |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce il rettangolo da utilizzare nell'operazione CombineMode. |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusSetClipRect`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getCm() {#getCm--}
```
public byte getCm()
```


Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. Vedere l'enumerazione CombineMode (sezione 2.1.1.4) per il significato dei valori.

Valore: Il cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Ottiene o imposta il CM (4 bit): Specifica l'operazione logica per combinare due regioni. Vedere l'enumerazione CombineMode (sezione 2.1.1.4) per il significato dei valori.

Valore: Il cm.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce il rettangolo da utilizzare nell'operazione CombineMode.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce il rettangolo da utilizzare nell'operazione CombineMode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

