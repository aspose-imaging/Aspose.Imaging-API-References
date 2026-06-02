---
title: "EmfRecord"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe base per i record EMF Tutti i record EMF DEVONO avere una lunghezza che sia un multiplo di 4 byte."
type: docs
weight: 106
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

Classe base per i record EMF. Tutti i record EMF DEVONO avere una lunghezza che sia un multiplo di 4 byte. Questo è rappresentato nelle strutture generiche dei tipi di record EMF precedenti includendo campi AlignmentPadding dove appropriato alla fine di queste strutture. Il contenuto dei campi AlignmentPadding DEVONO sempre essere ignorati. Per brevità, questi campi non sono mostrati in ogni singola definizione di record EMF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | Inizializza una nuova istanza della classe `EmfRecord`. |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfRecord`. |
| [EmfRecord(int type)](#EmfRecord-int-) | Inizializza una nuova istanza della classe `EmfRecord`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Ottiene il tipo. |
| [setType(int value)](#setType-int-) | Imposta il tipo. |
| [getSize()](#getSize--) | Ottiene la dimensione del record |
| [setSize(int value)](#setSize-int-) | Imposta la dimensione del record |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


Inizializza una nuova istanza della classe `EmfRecord`.

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfRecord`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


Inizializza una nuova istanza della classe `EmfRecord`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Il tipo di record. |

### getType() {#getType--}
```
public int getType()
```


Ottiene il tipo.

**Returns:**
int - Il tipo.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Imposta il tipo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il tipo. |

### getSize() {#getSize--}
```
public int getSize()
```


Ottiene la dimensione del record

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Imposta la dimensione del record

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

