---
title: "EmfSelectObject"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SELECTOBJECT aggiunge un oggetto grafico al contesto del dispositivo di riproduzione del metafile corrente."
type: docs
weight: 116
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

Il record EMR\_SELECTOBJECT aggiunge un oggetto grafico al contesto del dispositivo di riproduzione del metafile corrente. L'oggetto è specificato o dal suo indice nella EMF Object Table (sezione 3.1.1.1) o dal suo valore nell'enumerazione StockObject (sezione 2.1.31).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSelectObject`. |
| [EmfSelectObject()](#EmfSelectObject--) | Inizializza una nuova istanza della classe `EmfSelectObject`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Ottiene o imposta un intero senza segno a 32 bit che specifica sia l'indice di un oggetto grafico nella EMF Object Table sia l'indice di un oggetto stock dall'enumerazione `Consts.EmfStockObject`. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica sia l'indice di un oggetto grafico nella EMF Object Table sia l'indice di un oggetto stock dall'enumerazione `Consts.EmfStockObject`. |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


Inizializza una nuova istanza della classe `EmfSelectObject`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Il record. |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


Inizializza una nuova istanza della classe `EmfSelectObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica sia l'indice di un oggetto grafico nella EMF Object Table sia l'indice di un oggetto stock dall'enumerazione `Consts.EmfStockObject`.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica sia l'indice di un oggetto grafico nella EMF Object Table sia l'indice di un oggetto stock dall'enumerazione `Consts.EmfStockObject`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

