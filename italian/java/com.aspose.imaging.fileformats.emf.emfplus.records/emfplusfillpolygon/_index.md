---
title: "EmfPlusFillPolygon"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusFillPolygon specifica il riempimento dell'interno di un poligono."
type: docs
weight: 36
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPolygon extends EmfPlusDrawingRecordType
```

Il record EmfPlusFillPolygon specifica il riempimento dell'interno di un poligono.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusFillPolygon(EmfPlusRecord source)](#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusFillPolygon`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isColor()](#isColor--) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [setColor(boolean value)](#setColor-boolean-) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [isCompressed()](#isCompressed--) | Ottiene o imposta un valore che indica se questa istanza è compressa. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se questa istanza è compressa. |
| [isRelative()](#isRelative--) | Ottiene o imposta un valore che indica se questa istanza è relativa. |
| [setRelative(boolean value)](#setRelative-boolean-) | Ottiene o imposta un valore che indica se questa istanza è relativa. |
| [getBrushId()](#getBrushId--) | Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| [getPointData()](#getPointData--) | Ottiene o imposta i dati dei punti, un array di Count punti che definiscono i vertici del poligono. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Ottiene o imposta i dati dei punti, un array di Count punti che definiscono i vertici del poligono. |
### EmfPlusFillPolygon(EmfPlusRecord source) {#EmfPlusFillPolygon-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPolygon(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusFillPolygon`.

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

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Ottiene o imposta un valore che indica se questa istanza è compressa. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit.

Valore: `true` se questa istanza è compressa; altrimenti, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è compressa. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se non impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit.

Valore: `true` se questa istanza è compressa; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### isRelative() {#isRelative--}
```
public boolean isRelative()
```


Ottiene o imposta un valore che indica se questa istanza è relativa. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se non impostato, PointData specifica posizioni assolute secondo il flag C.

Valore: `true` se questa istanza è relativa; altrimenti, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è relativa. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se non impostato, PointData specifica posizioni assolute secondo il flag C.

Valore: `true` se questa istanza è relativa; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Ottiene o imposta i dati dei punti. Un array di Count punti che definiscono i vertici del poligono. I primi due punti dell'array specificano il primo lato del poligono. Ogni punto aggiuntivo specifica un nuovo lato, i cui vertici includono il punto e il punto precedente. Se l'ultimo punto e il primo punto non coincidono, essi specificano l'ultimo lato del poligono.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Ottiene o imposta i dati dei punti. Un array di Count punti che definiscono i vertici del poligono. I primi due punti dell'array specificano il primo lato del poligono. Ogni punto aggiuntivo specifica un nuovo lato, i cui vertici includono il punto e il punto precedente. Se l'ultimo punto e il primo punto non coincidono, essi specificano l'ultimo lato del poligono.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

