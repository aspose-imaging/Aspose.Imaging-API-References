---
title: "Classe EmfRoundRect"
type: docs
weight: 1020
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---

**Summary:** The EMR_ROUNDRECT record specifies a rectangle with rounded corners. The rectangle is outlined <br/>            by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRoundRect

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfRoundRect()](#EmfRoundRect__1) | Inizializza una nuova istanza della classe [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/). |
| [EmfRoundRect(source)](#EmfRoundRect_source_2) | Inizializza una nuova istanza della classe [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto RectL WMF a 128 bit, specificato in [MS-WMF] sezione 2.2.2.19, che <br/>            specifica il rettangolo inclusivo-inclusivo da disegnare. |
| corner | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Ottiene o imposta un oggetto SizeL WMF a 64 bit, specificato in [MS-WMF] sezione 2.2.2.22, che <br/>            specifica la larghezza e l'altezza, in coordinate logiche, dell'ellisse usata per disegnare gli angoli arrotondati. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfRoundRect() {#EmfRoundRect__1}


```
 EmfRoundRect() 
```

Inizializza una nuova istanza della classe [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/).

### Constructor: EmfRoundRect(source) {#EmfRoundRect_source_2}


```
 EmfRoundRect(source) 
```

Inizializza una nuova istanza della classe [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/).

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


