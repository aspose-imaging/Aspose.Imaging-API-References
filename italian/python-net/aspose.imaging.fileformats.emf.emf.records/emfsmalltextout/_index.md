---
title: "Classe EmfSmallTextOut"
type: docs
weight: 1380
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---

**Summary:** The EMR_SMALLTEXTOUT record outputs a string.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSmallTextOut

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfSmallTextOut(source)](#EmfSmallTextOut_source_1) | Inizializza una nuova istanza della classe [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL opzionale a 128 bit ([MS-WMF] sezione 2.2.2.19) che<br/>            specifica il rettangolo di delimitazione in unità dispositivo. |
| c_chars | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri a 16 bit nella<br/>            stringa. La stringa NON è terminata con un carattere nullo. |
| ex_scale | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione x. |
| ey_scale | float | r/w | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica di quanto scalare il testo nella direzione y. |
| fu_options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica le opzioni di output del testo da utilizzare. Queste<br/>            opzioni sono specificate da uno o una combinazione di valori dell'enumerazione ExtTextOutOptions<br/>            (sezione 2.1.11). |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica la modalità grafica, dall'enumerazione<br/>            GraphicsMode (sezione 2.1.16). |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| text_string | string | r/w | Ottiene o imposta una stringa a lunghezza variabile che contiene la stringa di testo da disegnare, in codici a 8 bit o 16 bit, secondo il valore del campo fuOptions. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
| x | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x del punto in cui posizionare la stringa. |
| y | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y del punto in cui posizionare la stringa. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSmallTextOut(source) {#EmfSmallTextOut_source_1}


```
 EmfSmallTextOut(source) 
```

Inizializza una nuova istanza della classe [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/).

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


