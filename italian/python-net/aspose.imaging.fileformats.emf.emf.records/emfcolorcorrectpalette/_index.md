---
title: "EmfColorCorrectPalette Classe"
type: docs
weight: 140
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---

**Summary:** The EMR_COLORCORRECTPALETTE record specifies how to correct the entries of a logical palette<br/>            object using WCS 1.0 values.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfColorCorrectPalette

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfColorCorrectPalette(source)](#EmfColorCorrectPalette_source_1) | Inizializza una nuova istanza della [EmfColorCorrectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/) classe. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| ih_palette | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice di un oggetto palette logica<br/>            (sezione 2.2.17) nella EMF Object Table (sezione 3.1.1.1). |
| n_first_entry | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice della prima voce da correggere. |
| n_pal_entries | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci della palette da correggere. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfColorCorrectPalette(source) {#EmfColorCorrectPalette_source_1}


```
 EmfColorCorrectPalette(source) 
```

Inizializza una nuova istanza della [EmfColorCorrectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/) classe.

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


