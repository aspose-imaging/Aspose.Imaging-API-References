---
title: BitmapV5Header
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: La struttura BitmapV5Header è il file di intestazione delle informazioni bitmap. È una versione estesa della struttura BITMAPINFOHEADER. Se bV5Height è negativo indicando un DIB top-down bV5Compression deve essere BI_RGB o BI_BITFIELDS. I DIB dallalto verso il basso non possono essere compressi. Linterfaccia ICM Independent Color Management Interface 2.0 consente di collegare o incorporare i profili colore dellInternational Color Consortium ICC nei DIB DIB. Vedere Utilizzo delle strutture per ulteriori informazioni. Quando un DIB viene caricato in memoria i dati del profilo se presenti dovrebbero seguire la tabella dei colori e bV5ProfileData dovrebbero fornire loffset dei dati del profilo dallinizio della struttura BITMAPV5HEADER. Il valore memorizzato in bV5ProfileData sarà diverso dal valore restituito dalloperatore sizeof dato largomento BITMAPV5HEADER perché bV5ProfileData è loffset in byte dallinizio della struttura BITMAPV5HEADER allinizio dei dati del profilo. i bit della bitmap non seguono la tabella dei colori in memoria. Le applicazioni dovrebbero modificare il membro bV5ProfileData dopo aver caricato il DIB in memoria. Per i DIB compressi i dati del profilo dovrebbero seguire i bit bitmap simili al formato del file. Il membro bV5ProfileData dovrebbe comunque fornire loffset dei dati del profilo dallinizio di BITMAPV5HEADER. Le applicazioni dovrebbero accedere ai dati del profilo solo quando bV5Size è uguale alla dimensione di BITMAPV5HEADER e bV5CSType è uguale a PROFILE_EMBEDDED o PROFILE_LINKED.
type: docs
weight: 1370
url: /it/net/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

La struttura BitmapV5Header è il file di intestazione delle informazioni bitmap. È una versione estesa della struttura BITMAPINFOHEADER. Se bV5Height è negativo, indicando un DIB top-down, bV5Compression deve essere BI_RGB o BI_BITFIELDS. I DIB dall'alto verso il basso non possono essere compressi. L'interfaccia ICM (Independent Color Management Interface) 2.0 consente di collegare o incorporare i profili colore dell'International Color Consortium (ICC) nei DIB (DIB). Vedere Utilizzo delle strutture per ulteriori informazioni. Quando un DIB viene caricato in memoria, i dati del profilo (se presenti) dovrebbero seguire la tabella dei colori, e bV5ProfileData dovrebbero fornire l'offset dei dati del profilo dall'inizio della struttura BITMAPV5HEADER. Il valore memorizzato in bV5ProfileData sarà diverso dal valore restituito dall'operatore sizeof dato l'argomento BITMAPV5HEADER, perché bV5ProfileData è l'offset in byte dall'inizio della struttura BITMAPV5HEADER all'inizio dei dati del profilo. (i bit della bitmap non seguono la tabella dei colori in memoria). Le applicazioni dovrebbero modificare il membro bV5ProfileData dopo aver caricato il DIB in memoria. Per i DIB compressi, i dati del profilo dovrebbero seguire i bit bitmap simili al formato del file. Il membro bV5ProfileData dovrebbe comunque fornire l'offset dei dati del profilo dall'inizio di BITMAPV5HEADER. Le applicazioni dovrebbero accedere ai dati del profilo solo quando bV5Size è uguale alla dimensione di BITMAPV5HEADER e bV5CSType è uguale a PROFILE_EMBEDDED o PROFILE_LINKED.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask) { get; set; } | Ottiene o imposta la maschera del colore che specifica il componente alfa di ogni pixel. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant) { get; set; } | Ottiene o imposta il numero di colori importanti della tavolozza. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused) { get; set; } | Ottiene o imposta il numero di colori della tavolozza utilizzati. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression) { get; set; } | Ottiene o imposta la compressione bitmap. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight) { get; set; } | Ottiene o imposta l'altezza della bitmap. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize) { get; set; } | Ottiene o imposta specifica la dimensione dei dati grezzi bitmap in byte. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes) { get; set; } | Ottiene o imposta il numero di piani. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth) { get; set; } | Ottiene o imposta la larghezza della bitmap. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter) { get; set; } | Ottiene o imposta la risoluzione dei pixel orizzontali. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter) { get; set; } | Ottiene o imposta la risoluzione dei pixel verticali. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel) { get; set; } | Ottiene o imposta il numero di bit per pixel. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask) { get; set; } | Ottiene o imposta la maschera di colore che specifica la componente blu di ogni pixel, valida solo se bV4Compression è impostato su BI_BITFIELDS. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype) { get; set; } | Ottiene o imposta lo spazio colore del DIB. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints) { get; set; } | Ottiene o imposta la classe CoordinatesTriple. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks) { get; set; } | Ottiene o imposta le maschere di bit extra. Presente solo nel caso in cui l'intestazione DIB sia BITMAPINFOHEADER e[`BitmapCompression`](../bitmapinfoheader/bitmapcompression) è impostato su uno dei dueBitfields (RGB) oAlphaBitfields (RGBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue) { get; set; } | Ottiene o imposta la gamma blu. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen) { get; set; } | Ottiene o imposta la gamma verde. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared) { get; set; } | Ottiene o imposta la gamma rossa. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask) { get; set; } | Ottiene o imposta la maschera di colore che specifica la componente verde di ogni pixel, valida solo se bV4Compression è impostato su BI_BITFIELDS. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize) { get; set; } | Ottiene o imposta la dimensione di questa struttura in byte. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent) { get; set; } | Ottiene o imposta l'intento di rendering per bitmap. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata) { get; set; } | Ottiene o imposta i dati del profilo. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize) { get; set; } | Ottiene o imposta la dimensione del profilo. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask) { get; set; } | Ottiene o imposta la maschera di colore che specifica la componente rossa di ogni pixel, valida solo se bV4Compression è impostato su BI_BITFIELDS. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved) { get; set; } | Ottiene o imposta il membro riservato. |

### Guarda anche

* class [BitmapV4Header](../bitmapv4header)
* spazio dei nomi [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
