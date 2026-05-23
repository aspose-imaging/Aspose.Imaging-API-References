---
title: "WmfBitmapInfoHeader classe"
type: docs
weight: 70
url: /it/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

**Summary:** The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader__1) | Inizializza una nuova istanza della classe WmfBitmapInfoHeader |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| STRUCTURE_SIZE [static] | int | r | La dimensione della struttura |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | Ottiene o imposta un intero senza segno a 16-bit che definisce il formato di<br/>                ogni pixel e il numero massimo di colori nel DIB. Questo valore<br/>                DEVE essere presente nell'enumerazione [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) (sezione 2.1.1.3). |
| color_important | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che definisce il numero di indici di colore necessari per la visualizzazione<br/>                del DIB.<br/>                Se questo valore è zero, tutti gli indici di colore sono richiesti |
| color_used | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di indici nella tavola dei colori usata dal DIB, come<br/>                segue:<br/>                Se questo valore è zero, il DIB utilizza il numero massimo di colori corrispondente al valore BitCount.<br/>                Se questo valore è diverso da zero e il valore BitCount è inferiore a 16, questo valore specifica il numero di colori usati dal<br/>                DIB.<br/>                Se questo valore è diverso da zero e il valore BitCount è 16 o superiore, questo valore specifica la dimensione della tavola dei colori<br/>                utilizzata per ottimizzare le prestazioni della palette di sistema.<br/>                Nota: Se questo valore è diverso da zero e maggiore della dimensione massima possibile della tavola dei colori basata sul valore BitCount,<br/>                si DEVE presumere la dimensione massima della tavola dei colori. |
| compression | [WmfCompression](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/) | r/w | Ottiene o imposta un intero senza segno a 32 bit che definisce la modalità di compressione del DIB. Questo valore DEVE essere presente nell'Enumerazione Compression (sezione 2.1.1.7).<br/>                Questo valore NON DEVE specificare un formato compresso se il DIB è un bitmap top-down, come indicato dal valore Height. |
| header_size | int | r/w | Ottiene o imposta un intero senza segno a 32-bit che definisce la dimensione di questo<br/>                oggetto, in byte. |
| height | int | r/w | Ottiene o imposta un intero con segno a 32 bit che definisce l'altezza del DIB, in pixel. Questo valore NON DEVE essere zero.<br/>                Se questo valore è positivo, il DIB è un bitmap bottom-up e la sua origine è l'angolo inferiore sinistro.<br/>                Se questo valore è negativo, il DIB è un bitmap top-down e la sua origine è l'angolo superiore sinistro. I bitmap top-down<br/>                non supportano la compressione.<br/>                Questo campo DOVREBBE specificare l'altezza del file immagine decompresso, se il valore Compression specifica il formato JPEG o PNG. |
| image_size | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione, in byte, dell'immagine.<br/>                Se il valore Compression è BI_RGB, questo valore DOVREBBE essere zero e DEVE essere ignorato.<br/>                Se il valore Compression è BI_JPEG o BI_PNG, questo valore DEVE specificare la dimensione del buffer dell'immagine JPEG o PNG,<br/>                rispettivamente. |
| planes | int | r/w | Ottiene o imposta un intero senza segno a 16-bit che definisce il numero di<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) per il dispositivo di destinazione. Questo valore DEVE essere<br/>                0x0001. |
| width | int | r/w | Ottiene o imposta un intero con segno a 32 bit che definisce la larghezza del DIB, in pixel. Questo valore DEVE essere positivo.<br/>                Questo campo DOVREBBE specificare la larghezza del file immagine decompresso, se il valore Compression specifica il formato JPEG o PNG. |
| x_pels_per_meter | int | r/w | Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione orizzontale, in pixel per metro, del dispositivo di destinazione<br/>                per il DIB |
| y_pels_per_meter | int | r/w | Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione verticale, in pixel per metro, del dispositivo di destinazione<br/>                per il DIB |


### Constructor: WmfBitmapInfoHeader() {#WmfBitmapInfoHeader__1}


```
 WmfBitmapInfoHeader() 
```

Inizializza una nuova istanza della classe WmfBitmapInfoHeader

