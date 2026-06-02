---
title: "EmfPlusDrawEllipse"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawEllipse specifica il disegno di un'ellisse."
type: docs
weight: 21
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawEllipse extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawEllipse specifica il disegno di un'ellisse.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawEllipse(EmfPlusRecord source)](#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawEllipse`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [getRectData()](#getRectData--) | Ottiene o imposta i dati del rettangolo, sia un oggetto EmfPlusRect sia un oggetto EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Ottiene o imposta i dati del rettangolo, sia un oggetto EmfPlusRect sia un oggetto EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse. |
### EmfPlusDrawEllipse(EmfPlusRecord source) {#EmfPlusDrawEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawEllipse(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawEllipse`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare l'ellisse. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare l'ellisse. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

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

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Ottiene o imposta i dati del rettangolo, sia un oggetto EmfPlusRect sia un oggetto EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Ottiene o imposta i dati del rettangolo, sia un oggetto EmfPlusRect sia un oggetto EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

