---
title: "EmfPlusObject"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfPlusObject specifica un oggetto da utilizzare nelle operazioni grafiche."
type: docs
weight: 42
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

Il record EmfPlusObject specifica un oggetto da utilizzare nelle operazioni grafiche. La definizione dell'oggetto può estendersi su più record, il che è indicato dal valore del campo Flags.

Il record EmfPlusObject è generico; viene utilizzato per tutti i tipi di oggetti. I valori specifici per particolari tipi di oggetto sono contenuti nel campo ObjectData. Un modello concettuale per la gestione degli oggetti grafici è descritto in Managing Graphics Objects (sezione 3.1.2).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inizializza una nuova istanza della classe `EmfPlusObject`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isContinuable()](#isContinuable--) | Ottiene o imposta un valore che indica se questa istanza è continuabile. |
| [setContinuable(boolean value)](#setContinuable-boolean-) | Ottiene o imposta un valore che indica se questa istanza è continuabile. |
| [getObjectType()](#getObjectType--) | Ottiene o imposta il tipo dell'oggetto. |
| [setObjectType(byte value)](#setObjectType-byte-) | Ottiene o imposta il tipo dell'oggetto. |
| [getObjectId()](#getObjectId--) | Ottiene o imposta l'identificatore dell'oggetto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Ottiene o imposta l'identificatore dell'oggetto. |
| [getTotalObjectSize()](#getTotalObjectSize--) | Ottiene o imposta la dimensione totale dell'oggetto. |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | Ottiene o imposta la dimensione totale dell'oggetto. |
| [getObjectData()](#getObjectData--) | Ottiene o imposta un array di byte che contiene i dati per il tipo di oggetto specificato nel campo Flags. |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | Ottiene o imposta un array di byte che contiene i dati per il tipo di oggetto specificato nel campo Flags. |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


Inizializza una nuova istanza della classe `EmfPlusObject`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La sorgente. |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


Ottiene o imposta un valore che indica se questa istanza è continuabile. Indica che la definizione dell'oggetto continua nel successivo record EmfPlusObject. Questa flag non è mai impostata nel record finale che definisce l'oggetto.

Valore: `true` se questa istanza è compressa; altrimenti, `false`.

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


Ottiene o imposta un valore che indica se questa istanza è continuabile. Indica che la definizione dell'oggetto continua nel successivo record EmfPlusObject. Questa flag non è mai impostata nel record finale che definisce l'oggetto.

Valore: `true` se questa istanza è compressa; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


Ottiene o imposta il tipo dell'oggetto.

Valore: Il tipo dell'oggetto.

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


Ottiene o imposta il tipo dell'oggetto.

Valore: Il tipo dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice nella EMF+ Object Table da associare all'oggetto creato da questo record. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Ottiene o imposta l'identificatore dell'oggetto. L'indice nella EMF+ Object Table da associare all'oggetto creato da questo record. Il valore DEVE essere compreso tra 0 e 63, inclusi.

Valore: L'identificatore dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


Ottiene o imposta la dimensione totale dell'oggetto. Se il record è continuabile, quando il bit continue è impostato, questo campo sarà presente. Gli oggetti continuativi hanno più record EMF+ che iniziano con EmfPlusContineudObjectRecord. Ogni EmfPlusContinuedObjectRecord conterrà un TotalObjectSize. Una volta letto il numero di byte indicato da TotalObjectSize, il successivo record EMF+ non sarà trattato come parte dell'oggetto continuativo.

Valore: La dimensione totale dell'oggetto.

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


Ottiene o imposta la dimensione totale dell'oggetto. Se il record è continuabile, quando il bit continue è impostato, questo campo sarà presente. Gli oggetti continuativi hanno più record EMF+ che iniziano con EmfPlusContineudObjectRecord. Ogni EmfPlusContinuedObjectRecord conterrà un TotalObjectSize. Una volta letto il numero di byte indicato da TotalObjectSize, il successivo record EMF+ non sarà trattato come parte dell'oggetto continuativo.

Valore: La dimensione totale dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


Ottiene o imposta un array di byte che contiene i dati per il tipo di oggetto specificato nel campo Flags. Il contenuto e il formato dei dati possono variare per ciascun tipo di oggetto. Vedere le definizioni individuali degli oggetti nella sezione 2.2.1 per ulteriori informazioni.

Valore: I dati dell'oggetto.

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


Ottiene o imposta un array di byte che contiene i dati per il tipo di oggetto specificato nel campo Flags. Il contenuto e il formato dei dati possono variare per ciascun tipo di oggetto. Vedere le definizioni individuali degli oggetti nella sezione 2.2.1 per ulteriori informazioni.

Valore: I dati dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

