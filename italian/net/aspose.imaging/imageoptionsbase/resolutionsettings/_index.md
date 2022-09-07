---
title: ResolutionSettings
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta le impostazioni di risoluzione.
type: docs
weight: 60
url: /it/net/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

Ottiene o imposta le impostazioni di risoluzione.

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

### Esempi

L'esempio seguente carica un'immagine BMP e la salva di nuovo in BMP utilizzando varie opzioni di salvataggio.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Crea BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Usa 8 bit per pixel per ridurre le dimensioni dell'immagine di output.
    saveOptions.BitsPerPixel = 8;

    // Imposta la tavolozza dei colori a 8 bit più vicina che copre il numero massimo di pixel dell'immagine, in modo che un'immagine
    // è quasi visivamente indistinguibile da uno non pallettizzato.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Salva senza compressione.
    // Puoi anche usare la compressione RLE-8 per ridurre le dimensioni dell'immagine di output.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Imposta la risoluzione orizzontale e verticale su 96 dpi.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

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

L'esempio seguente crea un'immagine BMP in scala di grigi con palettizzazione e quindi la salva in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// Salva in un file
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// Usa 8 bit per pixel per ridurre le dimensioni dell'immagine di output.
createOptions.BitsPerPixel = 8;

// Imposta la tavolozza dei colori standard in scala di grigi a 8 bit che copre tutti i colori in scala di grigi.
// Se l'immagine elaborata contiene solo colori in scala di grigi, allora la sua versione con palettizzazione
// è visivamente indistinguibile da uno non pallettizzato.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// Salva senza compressione.
// Puoi anche usare la compressione RLE-8 per ridurre le dimensioni dell'immagine di output.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// Imposta la risoluzione orizzontale e verticale su 96 dpi.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// Crea un'immagine BMP di 100 x 100 px e salvala in un file.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // Riempi l'immagine con una sfumatura in scala di grigi
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
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

* class [ResolutionSetting](../../resolutionsetting)
* class [ImageOptionsBase](../../imageoptionsbase)
* spazio dei nomi [Aspose.Imaging](../../imageoptionsbase)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
