---
title: JpegOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Inizializza una nuova istanza diJpegOptionsaspose.imaging.imageoptions/jpegoptions classe.
type: docs
weight: 10
url: /it/net/aspose.imaging.imageoptions/jpegoptions/jpegoptions/
---
## JpegOptions() {#constructor}

Inizializza una nuova istanza di[`JpegOptions`](../../jpegoptions) classe.

```csharp
public JpegOptions()
```

### Esempi

L'esempio seguente carica un'immagine BMP e la salva in JPEG utilizzando varie opzioni di salvataggio.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine BMP da un file.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Esegui un po' di elaborazione delle immagini.

    // Usa opzioni aggiuntive per specificare i parametri dell'immagine desiderati.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // Il numero di bit per canale è 8.
    // Quando si utilizza una tavolozza, l'indice del colore viene memorizzato nei dati dell'immagine invece del colore stesso.
    saveOptions.BitsPerChannel = 8;

    // Imposta il tipo progressivo di compressione.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
    saveOptions.Quality = 100;

    // Imposta la risoluzione orizzontale/verticale su 96 punti per pollice.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Se l'immagine di origine è colorata, verrà convertita in scala di grigi.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Usa una tavolozza per ridurre le dimensioni dell'output.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

L'esempio seguente mostra come creare un'immagine JPEG della dimensione specificata con i parametri specificati.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine JPEG di 100x100 px.
// Usa opzioni aggiuntive per specificare i parametri dell'immagine desiderati.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// Il numero di bit per canale è 8, 8, 8 per i componenti Y, Cr, Cb di conseguenza.
createOptions.BitsPerChannel = 8;

// Imposta il tipo progressivo di compressione.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Imposta la qualità dell'immagine. È un valore compreso tra 1 e 100.
createOptions.Quality = 100;

// Imposta la risoluzione orizzontale/verticale su 96 punti per pollice.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Questa è un'opzione standard per le immagini JPEG.
// Due componenti di crominanza (Cb e Cr) possono essere ridotti, sottocampionati e compressi.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Riempi l'immagine con una sfumatura in scala di grigi
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Salva in un file.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Guarda anche

* class [JpegOptions](../../jpegoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../jpegoptions)
* assemblea [Aspose.Imaging](../../../)

---

## JpegOptions(JpegOptions) {#constructor_1}

Inizializza una nuova istanza di[`JpegOptions`](../../jpegoptions) classe.

```csharp
public JpegOptions(JpegOptions jpegOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| jpegOptions | JpegOptions | Le opzioni JPEG. |

### Guarda anche

* class [JpegOptions](../../jpegoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../jpegoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->