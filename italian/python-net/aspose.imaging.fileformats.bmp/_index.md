---
title: "aspose.imaging.fileformats.bmp"
type: docs
weight: 140
url: /it/python-net/aspose.imaging.fileformats.bmp/
---


Il modulo gestisce l'elaborazione del formato file Bmp.

## **Classes**
| **Class** | **Descrizione** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | Dimensioni e formato colore del DIB.<br/> Nome intestazione BITMAPCOREHEADER noto anche come OS21XBITMAPHEADER. |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | Specifica BITMAPINFOHEADER. <br/> Supporto OS: Windows NT, 3.1x o successive.<br/> Caratteristiche: Aggiunge formati a 16 bpp e 32 bpp. Aggiunge compressione RLE. |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | La struttura BitmapV4Header è il file di intestazione delle informazioni bitmap. È una versione estesa della struttura BITMAPINFOHEADER.<br/> <br/>La struttura BitmapV4Header è estesa per consentire il passaggio di un'immagine JPEG o PNG come immagine sorgente a StretchDIBits.<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | La struttura BitmapV5Header è il file di intestazione delle informazioni bitmap. È una versione estesa della struttura BITMAPINFOHEADER.<br/> <br/>Se bV5Height è negativo, indicando un DIB top-down, bV5Compression deve essere BI_RGB o BI_BITFIELDS. I DIB top-down non possono essere compressi.<br/> L'interfaccia Independent Color Management (ICM) 2.0 consente ai profili colore International Color Consortium (ICC) di essere collegati o incorporati nei DIB (DIB). <br/> Vedere Using Structures per ulteriori informazioni. Quando un DIB viene caricato in memoria, i dati del profilo (se presenti) dovrebbero seguire la tavola dei colori, <br/> e bV5ProfileData dovrebbe fornire l'offset dei dati del profilo dall'inizio della struttura BITMAPV5HEADER. <br/> Il valore memorizzato in bV5ProfileData sarà diverso dal valore restituito dall'operatore sizeof dato l'argomento BITMAPV5HEADER, <br/> perché bV5ProfileData è l'offset in byte dall'inizio della struttura BITMAPV5HEADER all'inizio dei dati del profilo. <br/> (I bit bitmap non seguono la tavola dei colori in memoria). Le applicazioni dovrebbero modificare il membro bV5ProfileData dopo aver caricato il DIB in memoria.<br/> Per i DIB impacchettati, i dati del profilo dovrebbero seguire i bit bitmap in modo simile al formato file. <br/> Il membro bV5ProfileData dovrebbe comunque fornire l'offset dei dati del profilo dall'inizio della BITMAPV5HEADER.<br/> Le applicazioni dovrebbero accedere ai dati del profilo solo quando bV5Size è uguale alla dimensione della BITMAPV5HEADER e bV5CSType è uguale a PROFILE_EMBEDDED o PROFILE_LINKED.<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | Puoi gestire facilmente file Bitmap (BMP) e Device Independent Bitmap<br/> (DIB), facilitando la manipolazione efficiente e l'elaborazione di immagini raster<br/> . Eseguendo varie operazioni sulle immagini, questa API semplifica il<br/> flusso di lavoro, offrendo agli sviluppatori un toolkit affidabile per lavorare con i formati BMP e<br/> DIB nelle loro applicazioni software. |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | Un OS/2 2.x OS22XBITMAPHEADER noto anche come BITMAPCOREHEADER2. |
## **Enumerations**
| **Enumeration** | **Descrizione** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Specifica diversi metodi di compressione bitmap. |
