---
title: GetCloseImagePalette
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene la tavolozza dei colori dallimmagine raster pallettizza limmagine nel caso in cui limmagine non ne abbia una. Nel caso esista una tavolozza verrà utilizzata al posto dellesecuzione dei calcoli.
type: docs
weight: 60
url: /it/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

Ottiene la tavolozza dei colori dall'immagine raster (pallettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Nel caso esista una tavolozza, verrà utilizzata al posto dell'esecuzione dei calcoli.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine raster. |
| entriesCount | Int32 | Le voci desiderate contano. |

### Valore di ritorno

La tavolozza dei colori che inizia con i colori più frequenti del*image* e contiene*entriesCount* voci.

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

L'esempio seguente mostra come pallettizzare un'immagine BMP per ridurne le dimensioni di output.

```csharp
[C#]

// Crea un'immagine BMP 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Il gradiente lineare dall'angolo in alto a sinistra all'angolo in basso a destra dell'immagine.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Riempi l'intera immagine con il pennello gradiente lineare.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Ottieni la tavolozza dei colori a 8 bit più vicina che copre il maggior numero di pixel possibile, in modo che un'immagine palettizzata
    // è quasi visivamente indistinguibile da uno non pallettizzato.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // La tavolozza a 8 bit contiene al massimo 256 colori.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// L'output è simile a questo:
// La dimensione dell'immagine pallettizzata è 11078 byte.
// La dimensione dell'immagine non palettizzata è 40054 byte.
```

### Guarda anche

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* spazio dei nomi [Aspose.Imaging](../../colorpalettehelper)
* assemblea [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_4}

Ottiene la tavolozza dei colori dall'immagine raster (pallettizza l'immagine) nel caso in cui l'immagine non ne abbia una. La tavolozza sta per essere ottimizzata per una migliore qualità dell'immagine indicizzata o presa "COSÌ COM'È" quando viene utilizzato PaletteMiningMethod.UseCurrentPalette.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine raster. |
| entriesCount | Int32 | Le voci desiderate contano. |
| paletteMiningMethod | PaletteMiningMethod | Il metodo di estrazione della tavolozza. |

### Valore di ritorno

La tavolozza dei colori che inizia con i colori più frequenti del*image* e contiene*entriesCount* voci.

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

### Guarda anche

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* spazio dei nomi [Aspose.Imaging](../../colorpalettehelper)
* assemblea [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Ottiene la tavolozza dei colori dall'immagine raster (pallettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Nel caso esista una tavolozza, verrà utilizzata al posto dell'esecuzione dei calcoli.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine raster. |
| destBounds | Rectangle | L'immagine di destinazione delimita. |
| entriesCount | Int32 | Le voci desiderate contano. |

### Valore di ritorno

La tavolozza dei colori che inizia con i colori più frequenti del*image* e contiene*entriesCount* voci.

### Guarda anche

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* spazio dei nomi [Aspose.Imaging](../../colorpalettehelper)
* assemblea [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Ottiene la tavolozza dei colori dall'immagine raster (pallettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Nel caso esista una tavolozza, verrà utilizzata al posto dell'esecuzione dei calcoli.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine raster. |
| destBounds | Rectangle | L'immagine di destinazione delimita. |
| entriesCount | Int32 | Le voci desiderate contano. |
| useImagePalette | Boolean | Se impostato, utilizzerà la propria tavolozza di immagini, se disponibile |

### Valore di ritorno

La tavolozza dei colori che inizia con i colori più frequenti del*image* e contiene*entriesCount* voci.

### Guarda anche

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* spazio dei nomi [Aspose.Imaging](../../colorpalettehelper)
* assemblea [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

Ottiene la tavolozza dei colori dall'immagine raster (pallettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Nel caso esista una tavolozza, verrà utilizzata al posto dell'esecuzione dei calcoli.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine raster. |
| destBounds | Rectangle | L'immagine di destinazione delimita. |
| entriesCount | Int32 | Le voci desiderate contano. |
| useImagePalette | Boolean | Se impostato, utilizzerà la propria tavolozza di immagini, se disponibile |
| alphaBlendInColor | Color | Il colore da utilizzare come colore di sfondo per la sostituzione alfa semitrasparente. |

### Valore di ritorno

La tavolozza dei colori che inizia con i colori più frequenti del*image* e contiene*entriesCount* voci.

### Guarda anche

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* spazio dei nomi [Aspose.Imaging](../../colorpalettehelper)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
