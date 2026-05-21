---
title: "EmfPlusDrawPie"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusDrawPie specifica il disegno di una sezione dell'interno di un'ellisse."
type: docs
weight: 26
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

Il record EmfPlusDrawPie specifica il disegno di una sezione dell'interno di un'ellisse.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusDrawPie`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCompressed()](#getCompressed--) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se il PointData è compresso. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getStartAngle()](#getStartAngle--) | Ottiene o imposta l'angolo di partenza Un valore a virgola mobile a 32 bit, non negativo, che specifica l'angolo tra l'asse x e il punto di partenza della fetta di torta. |
| [setStartAngle(float value)](#setStartAngle-float-) | Ottiene o imposta l'angolo di partenza Un valore a virgola mobile a 32 bit, non negativo, che specifica l'angolo tra l'asse x e il punto di partenza della fetta di torta. |
| [getSweepAngle()](#getSweepAngle--) | Ottiene o imposta l'angolo di sweep Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco che definisce la fetta di torta da disegnare, come angolo in gradi misurato dal punto di partenza definito dal valore StartAngle. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Ottiene o imposta l'angolo di sweep Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco che definisce la fetta di torta da disegnare, come angolo in gradi misurato dal punto di partenza definito dal valore StartAngle. |
| [getRectData()](#getRectData--) | Ottiene o imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse che contiene la fetta di torta. |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Ottiene o imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse che contiene la fetta di torta. |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusDrawPie`.

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


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare la torta. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella degli oggetti EMF+ per disegnare la torta. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Ottiene o imposta l'angolo di partenza Un valore a virgola mobile a 32 bit, non negativo, che specifica l'angolo tra l'asse x e il punto di partenza della fetta di torta. Qualsiasi valore è accettabile, ma DEVE essere interpretato modulo 360, con il risultato utilizzato nell'intervallo da 0,0 inclusivo a 360,0 esclusivo.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Ottiene o imposta l'angolo di partenza Un valore a virgola mobile a 32 bit, non negativo, che specifica l'angolo tra l'asse x e il punto di partenza della fetta di torta. Qualsiasi valore è accettabile, ma DEVE essere interpretato modulo 360, con il risultato utilizzato nell'intervallo da 0,0 inclusivo a 360,0 esclusivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Ottiene o imposta l'angolo di sweep Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco che definisce la fetta di torta da disegnare, come angolo in gradi misurato dal punto di partenza definito dal valore StartAngle. Qualsiasi valore è accettabile, ma DEVE essere limitato a -360,0 fino a 360,0 inclusi. Un valore positivo indica che lo sweep è definito in senso orario, e un valore negativo indica che lo sweep è definito in senso antiorario.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Ottiene o imposta l'angolo di sweep Un valore a virgola mobile a 32 bit che specifica l'estensione dell'arco che definisce la fetta di torta da disegnare, come angolo in gradi misurato dal punto di partenza definito dal valore StartAngle. Qualsiasi valore è accettabile, ma DEVE essere limitato a -360,0 fino a 360,0 inclusi. Un valore positivo indica che lo sweep è definito in senso orario, e un valore negativo indica che lo sweep è definito in senso antiorario.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Ottiene o imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse che contiene la fetta di torta. Questo rettangolo definisce la posizione, la dimensione e la forma della fetta. Il tipo di oggetto in questo campo è specificato dal valore del campo Flags.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Ottiene o imposta i dati del rettangolo Un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro di delimitazione dell'ellisse che contiene la fetta di torta. Questo rettangolo definisce la posizione, la dimensione e la forma della fetta. Il tipo di oggetto in questo campo è specificato dal valore del campo Flags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

