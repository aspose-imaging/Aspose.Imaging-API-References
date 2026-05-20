---
title: "EmfPlusFillClosedCurve"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusFillClosedCurve specifica il riempimento dell'interno di una spline cardinale chiusa"
type: docs
weight: 32
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

Il record EmfPlusFillClosedCurve specifica il riempimento dell'interno di una spline cardinale chiusa
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusFillClosedCurve`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isColor()](#isColor--) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [setColor(boolean value)](#setColor-boolean-) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è compresso. |
| [getWinding()](#getWinding--) | Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è avvolgente. |
| [setWinding(boolean value)](#setWinding-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è avvolgente. |
| [getRelative()](#getRelative--) | Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è relativo. |
| [getBrushId()](#getBrushId--) | Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica l'EmfPlusBrush, il cui contenuto è determinato dal bit S nel campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica l'EmfPlusBrush, il cui contenuto è determinato dal bit S nel campo Flags. |
| [getTension()](#getTension--) | Ottiene o imposta la tensione, un valore a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre attraversa i punti. |
| [setTension(float value)](#setTension-float-) | Ottiene o imposta la tensione, un valore a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre attraversa i punti. |
| [getPointData()](#getPointData--) | Ottiene o imposta i dati dei punti, un array di Count punti che specificano i punti finali delle linee che definiscono la spline. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Ottiene o imposta i dati dei punti, un array di Count punti che specificano i punti finali delle linee che definiscono la spline. |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusFillClosedCurve`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Ottiene o imposta un valore che indica se questa istanza è a colori. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella Tabella Oggetti EMF+.

Valore: `true` se questa istanza è a colori; altrimenti, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è a colori. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella Tabella Oggetti EMF+.

Valore: `true` se questa istanza è a colori; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. ---------------------- Un'operazione di riempimento \"winding\" riempie le aree secondo la regola della \"parità pari-dispari\". Secondo questa regola, un punto di prova può essere determinato come interno o esterno a una curva chiusa come segue: Tracciare una linea dal punto di prova a un punto distante dalla curva. Se quella linea attraversa la curva un numero dispari di volte, il punto di prova è interno alla curva; altrimenti, è esterno alla curva. --------------------- Un'operazione di riempimento \"alternate\" riempie le aree secondo la regola del \"non-zero\". Secondo questa regola, un punto di prova può essere determinato come interno o esterno a una curva chiusa come segue: Tracciare una linea da un punto di prova a un punto distante dalla curva. Contare il numero di volte in cui la curva attraversa la linea di prova da sinistra a destra, e contare il numero di volte in cui la curva attraversa la linea di prova da destra a sinistra. Se questi due numeri sono uguali, il punto di prova è esterno alla curva; altrimenti, è interno alla curva.

Valore: `true` se compresso; altrimenti, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è compresso. Questo bit indica se il campo PointData specifica dati compressi. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. ---------------------- Un'operazione di riempimento \"winding\" riempie le aree secondo la regola della \"parità pari-dispari\". Secondo questa regola, un punto di prova può essere determinato come interno o esterno a una curva chiusa come segue: Tracciare una linea dal punto di prova a un punto distante dalla curva. Se quella linea attraversa la curva un numero dispari di volte, il punto di prova è interno alla curva; altrimenti, è esterno alla curva. --------------------- Un'operazione di riempimento \"alternate\" riempie le aree secondo la regola del \"non-zero\". Secondo questa regola, un punto di prova può essere determinato come interno o esterno a una curva chiusa come segue: Tracciare una linea da un punto di prova a un punto distante dalla curva. Contare il numero di volte in cui la curva attraversa la linea di prova da sinistra a destra, e contare il numero di volte in cui la curva attraversa la linea di prova da destra a sinistra. Se questi due numeri sono uguali, il punto di prova è esterno alla curva; altrimenti, è interno alla curva.

Valore: `true` se compresso; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è avvolgente. Questo bit indica come eseguire l'operazione di riempimento. Se impostato, il riempimento è un riempimento \"winding\". Se non impostato, il riempimento è un riempimento \"alternate\".

Valore: `true` se avvolgente; altrimenti, `false`.

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è avvolgente. Questo bit indica come eseguire l'operazione di riempimento. Se impostato, il riempimento è un riempimento \"winding\". Se non impostato, il riempimento è un riempimento \"alternate\".

Valore: `true` se avvolgente; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se non impostato, PointData specifica posizioni assolute secondo il flag C. Nota: se questo flag è impostato, il flag C (sopra) è indefinito e DEVE essere ignorato.

Valore: `true` se relativo; altrimenti, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Ottiene o imposta un valore che indica se questo `EmfPlusFillClosedCurve` è relativo. Questo bit indica se il campo PointData specifica posizioni relative o assolute. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se non impostato, PointData specifica posizioni assolute secondo il flag C. Nota: se questo flag è impostato, il flag C (sopra) è indefinito e DEVE essere ignorato.

Valore: `true` se relativo; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica l'EmfPlusBrush, il cui contenuto è determinato dal bit S nel campo Flags. Questo pennello è usato per riempire l'interno della spline cardinale chiusa.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica l'EmfPlusBrush, il cui contenuto è determinato dal bit S nel campo Flags. Questo pennello è usato per riempire l'interno della spline cardinale chiusa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


Ottiene o imposta la tensione, un valore a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre attraversa i punti. Un valore di 0,0 indica che la spline è una sequenza di linee rette. Man mano che il valore aumenta, la curva diventa più arrotondata. Per ulteriori informazioni, vedere [SPLINE77] e [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Ottiene o imposta la tensione, un valore a virgola mobile a 32 bit che specifica quanto strettamente la spline si piega mentre attraversa i punti. Un valore di 0,0 indica che la spline è una sequenza di linee rette. Man mano che il valore aumenta, la curva diventa più arrotondata. Per ulteriori informazioni, vedere [SPLINE77] e [PETZOLD].

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Ottiene o imposta i dati dei punti, un array di Count punti che specificano i punti finali delle linee che definiscono la spline. In una spline cardinale chiusa, la curva continua attraverso l'ultimo punto nell'array PointData e si collega al primo punto dell'array.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Ottiene o imposta i dati dei punti, un array di Count punti che specificano i punti finali delle linee che definiscono la spline. In una spline cardinale chiusa, la curva continua attraverso l'ultimo punto nell'array PointData e si collega al primo punto dell'array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

