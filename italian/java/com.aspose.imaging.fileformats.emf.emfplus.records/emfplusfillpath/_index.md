---
title: "EmfPlusFillPath"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Fill path record FLAGS intero senza segno a 16 bit che fornisce informazioni su come l'operazione deve essere eseguita e sulla struttura del record."
type: docs
weight: 34
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

Fill path record FLAGS: intero senza segno a 16 bit che fornisce informazioni su come l'operazione deve essere eseguita e sulla struttura del record. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (1 bit): questo bit indica il tipo di dati nel campo BrushId. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella EMF+ Object Table. X (1 bit): riservato e DEVE essere ignorato. ObjectId (1 byte): l'indice dell'oggetto EmfPlusPath (sezione 2.2.1.6) da riempire, nella EMF+ Object Table. Il valore DEVE essere compreso tra 0 e 63, inclusi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusFillPath`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isColor()](#isColor--) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [setColor(boolean value)](#setColor-boolean-) | Ottiene o imposta un valore che indica se questa istanza è a colori. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getBrushId()](#getBrushId--) | Ottiene o imposta l'ID del Brush: un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Ottiene o imposta l'ID del Brush: un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags. |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusFillPath`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Ottiene o imposta un valore che indica se questa istanza è a colori. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella EMF+ Object Table.

Valore: `true` se questa istanza è a colori; altrimenti, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è a colori. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se non impostato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella EMF+ Object Table.

Valore: `true` se questa istanza è a colori; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice dell'oggetto EmfPlusPath (sezione 2.2.1.6) da riempire, nella EMF+ Object Table. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice dell'oggetto EmfPlusPath (sezione 2.2.1.6) da riempire, nella EMF+ Object Table. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Ottiene o imposta l'ID del Brush: un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Ottiene o imposta l'ID del Brush: un intero senza segno a 32 bit che definisce il pennello, il cui contenuto è determinato dal bit S nel campo Flags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

