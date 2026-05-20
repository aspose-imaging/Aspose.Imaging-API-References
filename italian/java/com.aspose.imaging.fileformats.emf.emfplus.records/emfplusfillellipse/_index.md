---
title: "EmfPlusFillEllipse"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusFillEllipse specifica il riempimento dell'interno di un'ellisse"
type: docs
weight: 33
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

Il record EmfPlusFillEllipse specifica il riempimento dell'interno di un'ellisse
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusFillEllipse`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isColor()](#isColor--) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [setColor(boolean value)](#setColor-boolean-) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [isCompressed()](#isCompressed--) | Ottiene o imposta un valore che indica se questa istanza è compressa. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Ottiene o imposta un valore che indica se questa istanza è compressa. |
| [getBrushId()](#getBrushId--) | Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| [getRectData()](#getRectData--) | Ottiene o imposta i dati del rettangolo, ovvero un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro delimitante dell'ellisse |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Ottiene o imposta i dati del rettangolo, ovvero un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro delimitante dell'ellisse |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusFillEllipse`.

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


Ottiene o imposta un valore che indica se questa istanza è compressa. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se cancellato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39).

Valore: `true` se questa istanza è compressa; altrimenti, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è compressa. Se impostato, RectData contiene un oggetto EmfPlusRect (sezione 2.2.2.38). Se cancellato, RectData contiene un oggetto EmfPlusRectF (sezione 2.2.2.39).

Valore: `true` se questa istanza è compressa; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. Questa definizione è usata per riempire l'interno dell'ellisse

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Ottiene o imposta l'identificatore del pennello, un intero senza segno a 32 bit che specifica il pennello, il cui contenuto è determinato dal bit S nel campo Flags. Questa definizione è usata per riempire l'interno dell'ellisse

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Ottiene o imposta i dati del rettangolo, ovvero un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro delimitante dell'ellisse

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Ottiene o imposta i dati del rettangolo, ovvero un oggetto EmfPlusRect o EmfPlusRectF che definisce il riquadro delimitante dell'ellisse

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

