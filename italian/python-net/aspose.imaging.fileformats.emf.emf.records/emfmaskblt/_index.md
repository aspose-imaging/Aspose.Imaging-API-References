---
title: "Classe EmfMaskBlt"
type: docs
weight: 600
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---

**Summary:** The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern and with the application of a color mask <br/>            bitmap, according to specified foreground and background raster operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMaskBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfMaskBlt(source)](#EmfMaskBlt_source_1) | Inizializza una nuova istanza della classe [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il <br/>            colore di sfondo del bitmap di origine. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il <br/>            rettangolo di delimitazione di destinazione in unità dispositivo. |
| cx_dest | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di destinazione. |
| cy_dest | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di destinazione. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Ottiene o imposta un buffer contenente le bitmap di maschera, che non <br/>            devono essere contigue con la parte fissa del record EMR_MASKBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e <br/>            DEVONO essere ignorati. |
| rop4 | [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) | r/w | Ottiene o imposta un'operazione raster quaternaria, che specifica le operazioni raster ternarie per <br/>            i colori di primo piano e di sfondo di una bitmap. Questi valori definiscono come i dati di colore del <br/>            rettangolo sorgente devono essere combinati con i dati di colore del rettangolo di destinazione. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Ottiene o imposta un buffer contenente le bitmap sorgente, che non <br/>            devono essere contigue con la parte fissa del record EMR_MASKBLT o tra loro. Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e <br/>            DEVONO essere ignorati. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella <br/>            tabella dei colori nell'intestazione della bitmap di maschera. Questo valore DEVE appartenere all'enumerazione DIBColors. |
| usage_src | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella <br/>            tabella dei colori nell'intestazione del bitmap sorgente. Questo valore DEVE essere nell'enumerazione DIBColors (sezione 2.1.9). |
| x_dest | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro <br/>            del rettangolo di destinazione. |
| x_mask | int | r/w | Ottiene o imposta un 32-bit signed integer che specifica la coordinata x logica dell'angolo superiore sinistro del bitmap maschera. |
| x_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro <br/>            del rettangolo di origine. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare al bitmap di origine. |
| y_dest | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro <br/>            del rettangolo di destinazione. |
| y_mask | int | r/w | Ottiene o imposta un 32-bit signed integer che specifica la coordinata y logica dell'angolo superiore sinistro del bitmap maschera. |
| y_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro <br/>            del rettangolo di origine. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMaskBlt(source) {#EmfMaskBlt_source_1}


```
 EmfMaskBlt(source) 
```

Inizializza una nuova istanza della classe [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/).

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


