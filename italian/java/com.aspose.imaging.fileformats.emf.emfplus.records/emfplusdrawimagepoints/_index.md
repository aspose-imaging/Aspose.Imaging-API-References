---
title: "EmfPlusDrawImagePoints"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawImagePoints specifica il disegno di un'immagine scalata all'interno di un parallelogramma."
type: docs
weight: 23
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawImagePoints specifica il disegno di un'immagine scalata all'interno di un parallelogramma.

Un EmfPlusImage può specificare sia un bitmap sia un metafile. I colori di un'immagine possono essere manipolati durante il rendering. Possono essere corretti, scuriti, schiariti e rimossi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawImagePoints`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | Ottiene o imposta un valore che indica se [applying an effect]. |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | Ottiene o imposta un valore che indica se [applying an effect]. |
| [getRelative()](#getRelative--) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawImagePoints` è relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawImagePoints` è relativo. |
| [getImageAttributesId()](#getImageAttributesId--) | Ottiene o imposta un intero senza segno a 32 bit che contiene l'indice dell'oggetto opzionale EmfPlusImageAttributes (sezione 2.2.1.5) nella tabella degli oggetti EMF+. |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | Ottiene o imposta un intero senza segno a 32 bit che contiene l'indice dell'oggetto opzionale EmfPlusImageAttributes (sezione 2.2.1.5) nella tabella degli oggetti EMF+. |
| [getSrcUnit()](#getSrcUnit--) | Ottiene o imposta un intero con segno a 32 bit che definisce le unità del campo SrcRect. |
| [setSrcUnit(int value)](#setSrcUnit-int-) | Ottiene o imposta un intero con segno a 32 bit che definisce le unità del campo SrcRect. |
| [getSrcRect()](#getSrcRect--) | Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce una porzione dell'immagine da renderizzare. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce una porzione dell'immagine da renderizzare. |
| [getPointData()](#getPointData--) | Ottiene o imposta un array di punti Count che specificano tre punti di un parallelogramma. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Ottiene o imposta un array di punti Count che specificano tre punti di un parallelogramma. |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawImagePoints`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Ottiene o imposta un valore che indica se il PointData è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota: se il flag P (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Ottiene o imposta un valore che indica se il PointData è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota: se il flag P (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato.

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

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


Ottiene o imposta un valore che indica se [applying an effect]. Questo bit indica che il rendering dell'immagine include l'applicazione di un effetto. Se impostato, un oggetto della classe Effect DEVE essere stato specificato in un record EmfPlusSerializableObject precedente (sezione 2.3.5.2).

Valore: `true` se [applying an effect]; altrimenti, `false`.

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


Ottiene o imposta un valore che indica se [applying an effect]. Questo bit indica che il rendering dell'immagine include l'applicazione di un effetto. Se impostato, un oggetto della classe Effect DEVE essere stato specificato in un record EmfPlusSerializableObject precedente (sezione 2.3.5.2).

Valore: `true` se [applying an effect]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Ottiene o imposta un valore che indica se questo `EmfPlusDrawImagePoints` è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se cancellato, PointData specifica posizioni assolute secondo il flag C. Nota: se questo flag è impostato, il flag C (sopra) è indefinito e DEVE essere ignorato.

Valore: `true` se relativo; altrimenti, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Ottiene o imposta un valore che indica se questo `EmfPlusDrawImagePoints` è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se cancellato, PointData specifica posizioni assolute secondo il flag C. Nota: se questo flag è impostato, il flag C (sopra) è indefinito e DEVE essere ignorato.

Valore: `true` se relativo; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


Ottiene o imposta un intero senza segno a 32 bit che contiene l'indice dell'oggetto opzionale EmfPlusImageAttributes (sezione 2.2.1.5) nella tabella degli oggetti EMF+.

Valore: l'identificatore degli attributi dell'immagine.

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che contiene l'indice dell'oggetto opzionale EmfPlusImageAttributes (sezione 2.2.1.5) nella tabella degli oggetti EMF+.

Valore: l'identificatore degli attributi dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


Ottiene o imposta un intero con segno a 32 bit che definisce le unità del campo SrcRect. DEVE essere il valore UnitPixel dell'enumerazione UnitType (sezione 2.1.1.33).

Valore: l'unità di origine.

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


Ottiene o imposta un intero con segno a 32 bit che definisce le unità del campo SrcRect. DEVE essere il valore UnitPixel dell'enumerazione UnitType (sezione 2.1.1.33).

Valore: l'unità di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce una porzione dell'immagine da renderizzare.

Valore: il rettangolo di origine.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Ottiene o imposta un oggetto EmfPlusRectF (sezione 2.2.2.39) che definisce una porzione dell'immagine da renderizzare.

Valore: il rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Ottiene o imposta un array di Count punti che specificano tre punti di un parallelogramma. I tre punti rappresentano gli angoli superiore sinistro, superiore destro e inferiore sinistro del parallelogramma. Il quarto punto del parallelogramma è estrapolato dai primi tre. La porzione dell'immagine specificata dal campo SrcRect DOVREBBE avere trasformazioni di scala e shear applicate, se necessario, per adattarsi all'interno del parallelogramma.

Valore: i dati del punto.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Ottiene o imposta un array di Count punti che specificano tre punti di un parallelogramma. I tre punti rappresentano gli angoli superiore sinistro, superiore destro e inferiore sinistro del parallelogramma. Il quarto punto del parallelogramma è estrapolato dai primi tre. La porzione dell'immagine specificata dal campo SrcRect DOVREBBE avere trasformazioni di scala e shear applicate, se necessario, per adattarsi all'interno del parallelogramma.

Valore: i dati del punto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

