---
title: "EmfStretchDiBits Class"
type: docs
weight: 1410
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---

**Summary:** The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, optionally in combination with a brush pattern, according to a specified raster <br/>            operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStretchDiBits

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfStretchDiBits(source)](#EmfStretchDiBits_source_1) | Inizializza una nuova istanza della classe [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica un codice di operazione raster <br/>            . Questi codici definiscono come i dati di colore del rettangolo sorgente devono essere combinati con <br/>            i dati di colore del rettangolo di destinazione e, facoltativamente, un modello di pennello, per ottenere il colore finale. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il <br/>            rettangolo di delimitazione di destinazione in unità dispositivo. |
| cx_dest | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| cx_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo sorgente. |
| cy_dest | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| cy_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo sorgente. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Ottiene o imposta un buffer contenente il bitmap sorgente, che non è necessario sia <br/>            contiguo con la parte fissa del record EMR_STRETCHDIBITS. Di conseguenza, i campi in <br/>            questo buffer etichettati "UndefinedSpace" sono opzionali e DEVE essere ignorati. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella <br/>            tabella dei colori nell'intestazione del bitmap sorgente. Questo valore DEVE essere nell'enumerazione DIBColors (sezione 2.1.9). |
| x_dest | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro <br/>            del rettangolo di destinazione. |
| x_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo superiore sinistro <br/>            del rettangolo sorgente. |
| y_dest | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro <br/>            del rettangolo di destinazione. |
| y_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo superiore sinistro <br/>            del rettangolo sorgente. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfStretchDiBits(source) {#EmfStretchDiBits_source_1}


```
 EmfStretchDiBits(source) 
```

Inizializza una nuova istanza della classe [EmfStretchDiBits](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/).

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


