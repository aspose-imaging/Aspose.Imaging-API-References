---
title: WmfBitmapInfoHeader
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto BitmapInfoHeader contiene informazioni sulle dimensioni e sul formato del colore di una bitmap DIB indipendente dal dispositivo .
type: docs
weight: 8470
url: /it/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

L'oggetto BitmapInfoHeader contiene informazioni sulle dimensioni e sul formato del colore di una bitmap (DIB) indipendente dal dispositivo .

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount) { get; set; } | Ottiene o imposta un numero intero senza segno a 16 bit che definisce il formato di di ciascun pixel e il numero massimo di colori nel DIB. Questo valore DEVE essere nel[`BitCount`](../wmfbitmapbaseheader/bitcount) Enumerazione (sezione 2.1.1.3). |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant) { get; set; } | Ottiene o imposta un numero intero senza segno a 32 bit che definisce il numero di indici di colore necessari per visualizzare il DIB. Se questo valore è zero, tutti gli indici di colore sono obbligatori |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di indici nella tabella dei colori utilizzati dal DIB, come segue : Se questo valore è zero, il DIB utilizza il numero massimo di colori che corrispondono al valore BitCount. Se questo valore è diverso da zero e il valore BitCount è minore di 16, questo valore specifica il numero di colori utilizzati da il DIB. Se questo valore è diverso da zero e il valore BitCount è 16 o maggiore, questo valore specifica la dimensione del colore table utilizzato per ottimizzare le prestazioni della tavolozza di sistema. Nota Se questo valore è diverso da zero e maggiore della dimensione massima possibile della tabella dei colori basata sul valore BitCount , DOVREBBE essere assunta la dimensione massima della tabella dei colori. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che definisce la modalità di compressione del DIB. Questo valore DEVE essere nell'enumerazione di compressione (sezione 2.1.1.7). Questo valore NON DEVE specificare un formato compresso se il DIB è una bitmap top-down, come indicato dal valore di Altezza. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione di questo oggetto, in byte. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che definisce l'altezza del DIB, in pixel. Questo valore NON DEVE essere zero. Se questo valore è positivo, il DIB è una bitmap dal basso verso l'alto e la sua origine è l'angolo inferiore sinistro. Se questo valore è negativo, il DIB è una bitmap dall'alto verso il basso e la sua origine è l'angolo in alto a sinistra. Le bitmap top-down non supportano la compressione. Questo campo DOVREBBE specificare l'altezza del file immagine decompresso, se il valore di compressione specifica il formato JPEG o PNG . |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che definisce la dimensione, in byte, dell'immagine. Se il valore di Compressione è BI_RGB, questo valore DOVREBBE essere zero e DEVE essere ignorato. Se il valore di Compressione è BI_JPEG o BI_PNG, questo valore DEVE specificare la dimensione del buffer dell'immagine JPEG o PNG, rispettivamente. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes) { get; set; } | Ottiene o imposta un intero senza segno a 16 bit che definisce il numero di planes per il dispositivo di destinazione. Questo valore DEVE essere 0x0001. |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che definisce la larghezza del DIB, in pixel. Questo valore DEVE essere positivo. Questo campo DOVREBBE specificare la larghezza del file immagine decompresso, se il valore di compressione specifica il formato JPEG o PNG . |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione orizzontale, in pixel per metro, del dispositivo target per il DIB |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che definisce la risoluzione verticale, in pixel per metro, del dispositivo target per il DIB |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize) | La dimensione della struttura |

### Guarda anche

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader)
* spazio dei nomi [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
