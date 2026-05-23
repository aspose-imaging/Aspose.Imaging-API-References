---
title: "Classe EmfPlgBlt"
type: docs
weight: 750
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

**Summary:** The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_1) | Inizializza una nuova istanza della classe [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Ottiene o imposta un array di tre oggetti WMF PointL ([MS-WMF] sezione 2.2.2.15) che <br/>            specifica tre angoli di un'area di destinazione a forma di parallelogramma per il trasferimento a blocchi.<br/>            L'angolo in alto a sinistra del rettangolo sorgente è mappato al primo punto di questo array, il <br/>            angolo in alto a destra al secondo punto, e l'angolo in basso a sinistra al terzo punto. L'angolo in basso a destra del rettangolo sorgente è mappato al quarto punto implicito nel <br/>            parallelogramma, che è calcolato dai primi tre punti (A, B e C) trattandoli come <br/>            vettori. <br/>            D = B + C A |
| bk_src_argb_32_color | int | r/w | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il <br/>            colore di sfondo del bitmap sorgente. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il <br/>            rettangolo di delimitazione, in unità dispositivo, per l'output verso la destinazione. |
| cx_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza logica del rettangolo di origine. |
| cy_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza logica del rettangolo di origine. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Ottiene o imposta un buffer contenente il bitmap di maschera, che non è <br/>            necessario che sia contiguo con la parte fissa del record EMR_PLGBLT o con l'altro. <br/>            Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e MUST siano ignorati. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Ottiene o imposta un buffer contenente il bitmap di origine, che non è <br/>            necessario che sia contiguo con la parte fissa del record EMR_PLGBLT o con l'altro. <br/>            Di conseguenza, i campi in questo buffer etichettati "UndefinedSpace" sono opzionali e MUST siano ignorati. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella <br/>            tabella dei colori nell'intestazione della bitmap di maschera. Questo valore DEVE appartenere all'enumerazione DIBColors. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella <br/>            tavola dei colori nell'intestazione del bitmap di origine. Questo valore MUST essere nella enumerazione DIBColors |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ottiene o imposta un oggetto XForm (sezione 2.2.28) che specifica una trasformazione dallo spazio mondiale allo spazio pagina da applicare al bitmap di origine. |
| x_mask | int | r/w | Ottiene o imposta un 32-bit signed integer che specifica la coordinata x logica dell'angolo superiore sinistro del bitmap maschera. |
| x_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x logica dell'angolo superiore sinistro <br/>            del rettangolo di origine. |
| y_mask | int | r/w | Ottiene o imposta un 32-bit signed integer che specifica la coordinata y logica dell'angolo superiore sinistro del bitmap maschera. |
| y_src | int | r/w | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y logica dell'angolo superiore sinistro <br/>            del rettangolo di origine. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPlgBlt(source) {#EmfPlgBlt_source_1}


```
 EmfPlgBlt(source) 
```

Inizializza una nuova istanza della classe [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/).

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


