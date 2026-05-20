---
title: "EmfPlusDrawBeziers"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawBeziers specifica il disegno di una sequenza di curve di Bézier collegate."
type: docs
weight: 17
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawBeziers specifica il disegno di una sequenza di curve Bézier collegate. L'ordine dei punti dati Bézier è: punto iniziale, punto di controllo 1, punto di controllo 2 e punto finale. Per ulteriori informazioni vedere [MSDN-DrawBeziers].
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawBeziers`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [getRelative()](#getRelative--) | Ottiene o imposta un valore che indica se il PointData è relativo. |
| [setRelative(boolean value)](#setRelative-boolean-) | Ottiene o imposta un valore che indica se il PointData è relativo. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getPointData()](#getPointData--) | Ottiene o imposta i dati del punto, un array di Count punti che specificano i punti di inizio, fine e di controllo delle curve Bézier. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Ottiene o imposta i dati del punto, un array di Count punti che specificano i punti di inizio, fine e di controllo delle curve Bézier. |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawBeziers`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Ottiene o imposta un valore che indica se il PointData è compresso. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se cancellato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota: se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato.

Valore: `true` se compresso; altrimenti, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Ottiene o imposta un valore che indica se il PointData è compresso. Se impostato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate intere a 16 bit. Se cancellato, PointData specifica posizioni assolute nello spazio delle coordinate con coordinate a virgola mobile a 32 bit. Nota: se il flag Relative (sotto) è impostato, questo flag è indefinito e DEVE essere ignorato.

Valore: `true` se compresso; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Ottiene o imposta un valore che indica se il PointData è relativo. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se cancellato, PointData specifica posizioni assolute secondo il flag C. Nota: se questo flag è impostato, il flag C (sopra) è indefinito e DEVE essere ignorato.

Valore: `true` se relativo; altrimenti, `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Ottiene o imposta un valore che indica se il PointData è relativo. Se impostato, ogni elemento in PointData specifica una posizione nello spazio delle coordinate che è relativa alla posizione specificata dall'elemento precedente nell'array. Nel caso del primo elemento in PointData, si assume una posizione precedente alle coordinate (0,0). Se cancellato, PointData specifica posizioni assolute secondo il flag C. Nota: se questo flag è impostato, il flag C (sopra) è indefinito e DEVE essere ignorato.

Valore: `true` se relativo; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare le curve Bézier. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare le curve Bézier. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Ottiene o imposta i dati del punto, un array di Count punti che specificano i punti di inizio, fine e di controllo delle curve Bézier. La coordinata finale di una curva Bézier è la coordinata iniziale della successiva. I punti di controllo sono usati per produrre l'effetto Bézier. Il tipo di dati in questo array è specificato dal campo Flags, come segue: Tipo di Dati Significato oggetto EmfPlusPointR (sezione 2.2.2.37) Se il flag P è impostato nei Flags, i punti specificano posizioni relative. oggetto EmfPlusPointF (sezione 2.2.2.36) Se i bit P e C sono cancellati nel campo Flags, i punti specificano posizioni assolute. oggetto EmfPlusPoint (sezione 2.2.2.35) Se il bit P è cancellato e il bit C è impostato nel campo Flags, i punti specificano posizioni relative. Una curva Bézier non passa attraverso i suoi punti di controllo. I punti di controllo agiscono come

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Ottiene o imposta i dati del punto, un array di Count punti che specificano i punti di inizio, fine e di controllo delle curve Bézier. La coordinata finale di una curva Bézier è la coordinata iniziale della successiva. I punti di controllo sono usati per produrre l'effetto Bézier. Il tipo di dati in questo array è specificato dal campo Flags, come segue: Tipo di Dati Significato oggetto EmfPlusPointR (sezione 2.2.2.37) Se il flag P è impostato nei Flags, i punti specificano posizioni relative. oggetto EmfPlusPointF (sezione 2.2.2.36) Se i bit P e C sono cancellati nel campo Flags, i punti specificano posizioni assolute. oggetto EmfPlusPoint (sezione 2.2.2.35) Se il bit P è cancellato e il bit C è impostato nel campo Flags, i punti specificano posizioni relative. Una curva Bézier non passa attraverso i suoi punti di controllo. I punti di controllo agiscono come

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

