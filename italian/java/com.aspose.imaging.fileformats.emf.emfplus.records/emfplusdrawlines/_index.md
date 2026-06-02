---
title: "EmfPlusDrawLines"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawlLines specifica il disegno di una serie di linee collegate."
type: docs
weight: 24
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawlLines specifica il disegno di una serie di linee collegate.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawLines`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. |
| [getRelative()](#getRelative--) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è relativo. |
| [getClosedShape()](#getClosedShape--) | Ottiene o imposta un valore che indica se [closed shape]. |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | Ottiene o imposta un valore che indica se [closed shape]. |
| [getPointData()](#getPointData--) | Ottiene o imposta i dati dei punti. Un array di Count punti che specificano i punti di inizio e fine delle linee da disegnare. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Ottiene o imposta i dati dei punti. Un array di Count punti che specificano i punti di inizio e fine delle linee da disegnare. |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawLines`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare le linee. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare le linee. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota: se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato

Valore: `true` se compresso; altrimenti, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota: se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato

Valore: `true` se compresso; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente con coordinate (0,0). Se non impostato, PointData specifica posizioni assolute secondo il flag C. Nota: se questo flag è impostato, il flag Compressed (sopra) è indefinito e DEVE essere ignorato

Valore: `true` se relativo; altrimenti, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente con coordinate (0,0). Se non impostato, PointData specifica posizioni assolute secondo il flag C. Nota: se questo flag è impostato, il flag Compressed (sopra) è indefinito e DEVE essere ignorato

Valore: `true` se relativo; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


Ottiene o imposta un valore che indica se [closed shape].

Valore: `true` se [forma chiusa]; altrimenti, `false`.

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


Ottiene o imposta un valore che indica se [closed shape].

Valore: `true` se [forma chiusa]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Ottiene o imposta i dati dei punti. Un array di Count punti che specificano i punti di inizio e fine delle linee da disegnare.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Ottiene o imposta i dati dei punti. Un array di Count punti che specificano i punti di inizio e fine delle linee da disegnare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

