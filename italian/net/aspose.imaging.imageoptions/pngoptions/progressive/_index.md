---
title: Progressive
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta un valore che indica se questoPngOptionsaspose.imaging.imageoptions/pngoptions è progressivo.
type: docs
weight: 60
url: /it/net/aspose.imaging.imageoptions/pngoptions/progressive/
---
## PngOptions.Progressive property

Ottiene o imposta un valore che indica se questo[`PngOptions`](../../pngoptions) è progressivo.

```csharp
public bool Progressive { get; set; }
```

### Valore della proprietà

`VERO` se progressivo; altrimenti,`falso` .

### Esempi

L'esempio seguente mostra come comprimere un'immagine PNG, utilizzando il colore indicizzato con la tavolozza più adatta

```csharp
[C#]

// Carica l'immagine png        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Usa il tipo di colore indicizzato
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Usa la compressione massima
         CompressionLevel = 9,
      // Ottieni la tavolozza dei colori a 8 bit più vicina che copre il maggior numero di pixel possibile, in modo che un'immagine palettizzata
         // è quasi visivamente indistinguibile da uno non pallettizzato.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // La dimensione del file di output dovrebbe essere notevolmente ridotta
```

Questo esempio mostra come creare un'immagine PNG con le opzioni specificate, riempirla con colori sfumati lineari e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// Il numero di bit per canale colore
createOptions.BitDepth = 8;

// Ogni pixel è una tripla (rossa, verde, blu) seguita dalla componente alfa.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// Il livello massimo di compressione.
createOptions.CompressionLevel = 9;

// L'uso dei filtri consente di comprimere le immagini tonali continue in modo più efficace.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Usa il caricamento progressivo
createOptions.Progressive = true;

// Crea un'immagine PNG con parametri personalizzati.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Riempi l'immagine con un gradiente semitrasparente.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Salva in un file.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

L'esempio seguente mostra come salvare un'immagine in formato PNG utilizzando varie opzioni.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un'immagine PNG di 100x100 px.
// Puoi anche caricare un'immagine di qualsiasi formato supportato da un file o da un flusso.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Riempi l'immagine con il gradiente blu-trasparente.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // Caricamento progressivo.
    saveOptions.Progressive = true;

    // Imposta la risoluzione orizzontale e verticale su 96 pixel per pollice.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // Ogni pixel è una tripla (rossa, verde, blu) seguita da alfa.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // Imposta il livello massimo di compressione.
    saveOptions.CompressionLevel = 9;

    // Questa è la compressione migliore, ma il tempo di esecuzione più lento.
    // Il filtro adattivo significa che il processo di salvataggio sceglierà il filtro più adatto per ogni riga di dati.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // Il numero di bit per canale.
    saveOptions.BitDepth = 8;

    // Salva in un file.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### Guarda anche

* class [PngOptions](../../pngoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../pngoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
