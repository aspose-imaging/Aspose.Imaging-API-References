---
title: "EmfRectangle"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_RECTANGLE disegna un rettangolo."
type: docs
weight: 107
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

Il record EMR\_RECTANGLE disegna un rettangolo. Il rettangolo è delineato usando la penna corrente e riempito usando il pennello corrente.

La posizione corrente non è né usata né aggiornata da Rectangle. Se viene usata una penna PS\_NULL, le dimensioni del rettangolo sono 1 pixel in meno in altezza e 1 pixel in meno in larghezza.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfRectangle`. |
| [EmfRectangle()](#EmfRectangle--) | Inizializza una nuova istanza della classe `EmfRectangle`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBox()](#getBox--) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo inclusivo‑inclusivo da disegnare. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo inclusivo‑inclusivo da disegnare. |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfRectangle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


Inizializza una nuova istanza della classe `EmfRectangle`.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo inclusivo‑inclusivo da disegnare.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che definisce il rettangolo inclusivo‑inclusivo da disegnare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

