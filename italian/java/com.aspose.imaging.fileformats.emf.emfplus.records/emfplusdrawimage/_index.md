---
title: "EmfPlusDrawImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawImage specifica il disegno di un'immagine scalata."
type: docs
weight: 22
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawImage specifica il disegno di un'immagine scalata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawImage`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getImageAttributesId()](#getImageAttributesId--) | Ottiene o imposta l'identificatore degli attributi immagine Un intero senza segno a 32 bit che specifica l'indice di un oggetto opzionale EmfPlusImageAttributes (sezione 2.2.1.5) nella EMF+ Object Table. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Ottiene o imposta l'identificatore degli attributi immagine Un intero senza segno a 32 bit che specifica l'indice di un oggetto opzionale EmfPlusImageAttributes (sezione 2.2.1.5) nella EMF+ Object Table. |
| [getRectData()](#getRectData--) | Ottiene o imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'immagine. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Ottiene o imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'immagine. |
| [getSrcRect()](#getSrcRect--) | Ottiene o imposta il rettangolo di origine Un oggetto EmfPlusRectF che specifica una porzione dell'immagine da renderizzare. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Ottiene o imposta il rettangolo di origine Un oggetto EmfPlusRectF che specifica una porzione dell'immagine da renderizzare. |
| [getSrcUnit()](#getSrcUnit--) | Ottiene o imposta l'unità di origine un intero a 32 bit con segno che specifica le unità del campo SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Ottiene o imposta l'unità di origine un intero a 32 bit con segno che specifica le unità del campo SrcRect. |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawImage`.

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


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusImage (sezione 2.2.1.4) nella tabella degli oggetti EMF+, che specifica l'immagine da renderizzare. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusImage (sezione 2.2.1.4) nella tabella degli oggetti EMF+, che specifica l'immagine da renderizzare. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Ottiene o imposta l'identificatore degli attributi immagine Un intero senza segno a 32 bit che specifica l'indice di un oggetto opzionale EmfPlusImageAttributes (sezione 2.2.1.5) nella EMF+ Object Table.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Ottiene o imposta l'identificatore degli attributi immagine Un intero senza segno a 32 bit che specifica l'indice di un oggetto opzionale EmfPlusImageAttributes (sezione 2.2.1.5) nella EMF+ Object Table.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Ottiene o imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'immagine. La porzione dell'immagine specificata dal campo SrcRect viene scalata per adattarsi a questo rettangolo.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Ottiene o imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'immagine. La porzione dell'immagine specificata dal campo SrcRect viene scalata per adattarsi a questo rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Ottiene o imposta il rettangolo di origine Un oggetto EmfPlusRectF che specifica una porzione dell'immagine da renderizzare. La porzione dell'immagine specificata da questo rettangolo viene scalata per adattarsi al rettangolo di destinazione specificato dal campo RectData.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Ottiene o imposta il rettangolo di origine Un oggetto EmfPlusRectF che specifica una porzione dell'immagine da renderizzare. La porzione dell'immagine specificata da questo rettangolo viene scalata per adattarsi al rettangolo di destinazione specificato dal campo RectData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Ottiene o imposta l'unità di origine un intero a 32 bit con segno che specifica le unità del campo SrcRect. Deve essere il membro UnitTypePixel dell'enumerazione UnitType (sezione 2.1.1.33).

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Ottiene o imposta l'unità di origine un intero a 32 bit con segno che specifica le unità del campo SrcRect. Deve essere il membro UnitTypePixel dell'enumerazione UnitType (sezione 2.1.1.33).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

