---
title: "EmfPlusDrawClosedCurve"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawClosedCurve specifica il disegno di una spline cardinale chiusa."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawClosedCurve extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawClosedCurve specifica il disegno di una spline cardinale chiusa.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawClosedCurve(EmfPlusRecord source)](#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawClosedCurve`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è compresso. |
| [getRelative()](#getRelative--) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusDrawClosedCurve` è relativo. |
| [getTension()](#getTension--) | Ottiene o imposta la tensione, un numero a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre attraversa i punti. |
| [setTension(float value)](#setTension-float-) | Ottiene o imposta la tensione, un numero a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre attraversa i punti. |
| [getPointData()](#getPointData--) | Ottiene o imposta i dati dei punti, un array di Count punti che specificano i punti finali delle linee che definiscono la spline. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Ottiene o imposta i dati dei punti, un array di Count punti che specificano i punti finali delle linee che definiscono la spline. |
### EmfPlusDrawClosedCurve(EmfPlusRecord source) {#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawClosedCurve(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawClosedCurve`. RecordType - Un intero senza segno a 16 bit che identifica questo tipo di record come EmfPlusDrawClosedCurve dall'enumerazione RecordType (sezione 2.1.1.1). Il valore DEVE essere 0x4017.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare la curva chiusa. Il valore DEVE essere da zero a 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare la curva chiusa. Il valore DEVE essere da zero a 63, inclusi.

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

### getTension() {#getTension--}
```
public float getTension()
```


Ottiene o imposta la tensione Un numero a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre passa attraverso i punti. Un valore di 0 specifica che la spline è una sequenza di linee rette. Man mano che il valore aumenta, la curva diventa più arrotondata. Per ulteriori informazioni, vedere [SPLINE77] e [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Ottiene o imposta la tensione Un numero a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre passa attraverso i punti. Un valore di 0 specifica che la spline è una sequenza di linee rette. Man mano che il valore aumenta, la curva diventa più arrotondata. Per ulteriori informazioni, vedere [SPLINE77] e [PETZOLD].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Ottiene o imposta i dati del punto Un array di punti Count che specificano i punti finali delle linee che definiscono la spline. In una spline cardinale chiusa, la curva continua attraverso l'ultimo punto nell'array PointData e si collega con il primo punto dell'array. Il tipo di dati in questo array è specificato dal campo Flags, come segue: Tipo di Dati Significato oggetto EmfPlusPointR (sezione 2.2.2.37) Se il flag P è impostato nei Flags, i punti specificano posizioni relative. oggetto EmfPlusPointF (sezione 2.2.2.36) Se i bit P e C sono impostati nel campo Flags, i punti specificano posizioni assolute. oggetto EmfPlusPoint (sezione 2.2.2.35) Se il bit P è cancellato e il bit C è impostato nel campo Flags, i punti specificano posizioni relative.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Ottiene o imposta i dati del punto Un array di punti Count che specificano i punti finali delle linee che definiscono la spline. In una spline cardinale chiusa, la curva continua attraverso l'ultimo punto nell'array PointData e si collega con il primo punto dell'array. Il tipo di dati in questo array è specificato dal campo Flags, come segue: Tipo di Dati Significato oggetto EmfPlusPointR (sezione 2.2.2.37) Se il flag P è impostato nei Flags, i punti specificano posizioni relative. oggetto EmfPlusPointF (sezione 2.2.2.36) Se i bit P e C sono impostati nel campo Flags, i punti specificano posizioni assolute. oggetto EmfPlusPoint (sezione 2.2.2.35) Se il bit P è cancellato e il bit C è impostato nel campo Flags, i punti specificano posizioni relative.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

