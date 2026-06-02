---
title: "EmfPlusDrawRects"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawRects specifica il disegno di una serie di rettangoli"
type: docs
weight: 27
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawRects extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawRects specifica il disegno di una serie di rettangoli
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawRects(EmfPlusRecord source)](#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawRects`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getRectData()](#getRectData--) | Ottiene o imposta i dati del rettangolo Un array di oggetti EmfPlusRect o EmfPlusRectF di lunghezza Count che definisce i dati del rettangolo. |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | Ottiene o imposta i dati del rettangolo Un array di oggetti EmfPlusRect o EmfPlusRectF di lunghezza Count che definisce i dati del rettangolo. |
### EmfPlusDrawRects(EmfPlusRecord source) {#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawRects(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawRects`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Ottiene o imposta un valore che indica se il PointData è compresso. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se non impostato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39).

Valore: `true` se compresso; altrimenti, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Ottiene o imposta un valore che indica se il PointData è compresso. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se non impostato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39).

Valore: `true` se compresso; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella EMF+ Object Table per disegnare i rettangoli. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella EMF+ Object Table per disegnare i rettangoli. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


Ottiene o imposta i dati del rettangolo Un array di oggetti EmfPlusRect o EmfPlusRectF di lunghezza Count che definisce i dati del rettangolo.

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


Ottiene o imposta i dati del rettangolo Un array di oggetti EmfPlusRect o EmfPlusRectF di lunghezza Count che definisce i dati del rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

