---
title: "EmfCreatePalette Classe"
type: docs
weight: 310
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---

**Summary:** The EMR_CREATEPALETTE record defines a logical palette for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePalette

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfCreatePalette(source)](#EmfCreatePalette_source_1) | Inizializza una nuova istanza della classe [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| ih_pal | int | r/w | Ottiene o imposta un 32-bit unsigned integer che specifica l'indice dell'oggetto palette logica<br/>            nella EMF Object Table (sezione 3.1.1.1). Questo indice MUST essere salvato affinché questo oggetto possa essere<br/>            riutilizzato o modificato. |
| log_palette | [EmfLogPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpalette/) | r/w | Ottiene o imposta un oggetto LogPalette (sezione 2.2.17). Il campo Version di questo oggetto<br/>            MUST essere impostato a 0x0300. Se il valore NumberOfEntries in questo oggetto è zero, l'elaborazione di<br/>            questo record MUST fallire. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreatePalette(source) {#EmfCreatePalette_source_1}


```
 EmfCreatePalette(source) 
```

Inizializza una nuova istanza della classe [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La sorgente. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La sorgente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Il tipo di record. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


