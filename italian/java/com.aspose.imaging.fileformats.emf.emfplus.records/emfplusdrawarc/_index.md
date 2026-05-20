---
title: "EmfPlusDrawArc"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawArc specifica il disegno dell'arco di un'ellisse."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawArc specifica il disegno dell'arco di un'ellisse.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawArc`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDataSize()](#getDataSize--) | Ottiene la dimensione dei dati. |
| [setDataSize(int value)](#setDataSize-int-) | Imposta la dimensione dei dati. |
| [getRectFloat()](#getRectFloat--) | Ottiene un valore che indica se i dati contengono record EmfPlusRectF o EmfPlusRect. Questo bit indica se i dati nel campo RectData sono compressi. |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | Imposta un valore che indica se i dati contengono record EmfPlusRectF o EmfPlusRect. Questo bit indica se i dati nel campo RectData sono compressi. |
| [getObjectId()](#getObjectId--) | Ottiene l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Imposta l'identificatore dell'oggetto. |
| [getSize()](#getSize--) | Ottiene la dimensione. |
| [setSize(int value)](#setSize-int-) | Imposta la dimensione. |
| [getStartAngle()](#getStartAngle--) | Ottiene l'angolo di partenza Un valore floating-point non negativo a 32 bit che specifica l'angolo tra l'asse x e il punto iniziale dell'arco. |
| [setStartAngle(float value)](#setStartAngle-float-) | Imposta l'angolo di partenza Un valore floating-point non negativo a 32 bit che specifica l'angolo tra l'asse x e il punto iniziale dell'arco. |
| [getSweepAngle()](#getSweepAngle--) | Ottiene l'angolo di sweep Un valore floating-point a 32 bit che specifica l'estensione dell'arco da disegnare, come angolo in gradi misurato dal punto di partenza definito dal valore StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Imposta l'angolo di sweep Un valore floating-point a 32 bit che specifica l'estensione dell'arco da disegnare, come angolo in gradi misurato dal punto di partenza definito dal valore StartAngle. |
| [getRectangleData()](#getRectangleData--) | Ottiene i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce la bounding box dell'ellisse collineare con l'arco. |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | Imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce la bounding box dell'ellisse collineare con l'arco. |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawArc`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Ottiene la dimensione dei dati. Un intero senza segno a 32 bit che specifica il numero di byte allineati a 32 bit dei dati specifici del record che seguono. Per questo tipo di record, il valore DEVE essere uno dei seguenti: 0x00000010 Se il bit C è impostato nel campo Flags. 0x00000018 Se il bit C è cancellato nel campo Flags.

**Returns:**
int - La dimensione dei dati.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Imposta la dimensione dei dati. Un intero senza segno a 32 bit che specifica il numero di byte allineati a 32 bit dei dati specifici del record che seguono. Per questo tipo di record, il valore DEVE essere uno dei seguenti: 0x00000010 Se il bit C è impostato nel campo Flags. 0x00000018 Se il bit C è cancellato nel campo Flags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La dimensione dei dati. |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


Ottiene un valore che indica se i dati contengono record EmfPlusRectF o EmfPlusRect. Questo bit indica se i dati nel campo RectData sono compressi. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se cancellato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39).

**Returns:**
boolean - `true` se float; altrimenti, `false`.
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


Imposta un valore che indica se i dati contengono record EmfPlusRectF o EmfPlusRect. Questo bit indica se i dati nel campo RectData sono compressi. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se non impostato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se float; altrimenti, `false`. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare l'arco. Il valore DEVE essere compreso tra 0 e 63, inclusi.

**Returns:**
byte - L'identificatore dell'oggetto.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare l'arco. Il valore DEVE essere compreso tra 0 e 63, inclusi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte | L'identificatore dell'oggetto. |

### getSize() {#getSize--}
```
public int getSize()
```


Ottiene la dimensione. Un intero senza segno a 32 bit che specifica il numero di byte allineati a 32 bit dell'intero record, includendo l'intestazione di 12 byte e i dati specifici del record. Per questo tipo di record, il valore DEVE essere uno dei seguenti: 0x0000001C se il bit C è impostato nel campo Flags. 0x00000024 se il bit C è non impostato nel campo Flags.

**Returns:**
int - La dimensione.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Imposta la dimensione. Un intero senza segno a 32 bit che specifica il numero di byte allineati a 32 bit dell'intero record, includendo l'intestazione di 12 byte e i dati specifici del record. Per questo tipo di record, il valore DEVE essere uno dei seguenti: 0x0000001C se il bit C è impostato nel campo Flags. 0x00000024 se il bit C è non impostato nel campo Flags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La dimensione. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Ottiene l'angolo di partenza. Un valore a virgola mobile non negativo a 32 bit che specifica l'angolo tra l'asse x e il punto iniziale dell'arco. Qualsiasi valore è accettabile, ma DEVE essere interpretato modulo 360, con il risultato utilizzato compreso nell'intervallo da 0,0 inclusi a 360,0 esclusi.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Imposta l'angolo di partenza. Un valore a virgola mobile non negativo a 32 bit che specifica l'angolo tra l'asse x e il punto iniziale dell'arco. Qualsiasi valore è accettabile, ma DEVE essere interpretato modulo 360, con il risultato utilizzato compreso nell'intervallo da 0,0 inclusi a 360,0 esclusi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Ottiene l'angolo di sweep. Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco da disegnare, come angolo in gradi misurato dal punto di partenza definito dal valore StartAngle. Qualsiasi valore è accettabile, ma DEVE essere limitato a -360,0 fino a 360,0 inclusi. Un valore positivo indica che lo sweep è definito in senso orario, e un valore negativo indica che lo sweep è definito in senso antiorario.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Imposta l'angolo di sweep. Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco da disegnare, come angolo in gradi misurato dal punto di partenza definito dal valore StartAngle. Qualsiasi valore è accettabile, ma DEVE essere limitato a -360,0 fino a 360,0 inclusi. Un valore positivo indica che lo sweep è definito in senso orario, e un valore negativo indica che lo sweep è definito in senso antiorario.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


Ottiene i dati del rettangolo. Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse collineare con l'arco. Questo rettangolo definisce la posizione, le dimensioni e la forma dell'arco. Il tipo di oggetto in questo campo è specificato dal valore del campo Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


Imposta i dati del rettangolo. Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse collineare con l'arco. Questo rettangolo definisce la posizione, le dimensioni e la forma dell'arco. Il tipo di oggetto in questo campo è specificato dal valore del campo Flags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

