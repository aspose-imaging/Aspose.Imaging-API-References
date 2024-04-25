---
title: GetCloseImagePalette
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar färgpalett från rasterbild palleterar bild om bilden inte har någon. Om palett finns kommer den att användas istället för att utföra beräkningar.
type: docs
weight: 60
url: /sv/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

Hämtar färgpalett från rasterbild (palleterar bild) om bilden inte har någon. Om palett finns kommer den att användas istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Rasterbilden. |
| entriesCount | Int32 | De önskade posterna räknas. |

### Returvärde

Färgpaletten som börjar med de vanligaste färgerna från*image* och innehåller*entriesCount* poster.

### Exempel

Följande exempel laddar en BMP-bild och sparar den tillbaka till BMP med hjälp av olika sparalternativ.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Skapa BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Använd 8 bitar per pixel för att minska storleken på utdatabilden.
    saveOptions.BitsPerPixel = 8;

    // Ställ in den närmaste 8-bitars färgpalett som täcker det maximala antalet bildpixlar, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palletiserad.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Spara utan komprimering.
    // Du kan också använda RLE-8-komprimering för att minska storleken på den utgående bilden.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Ställ in den horisontella och vertikala upplösningen till 96 dpi.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

Följande exempel visar hur man palleterar en BMP-bild för att minska dess utdatastorlek.

```csharp
[C#]

// Skapa en BMP-bild 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Den linjära gradienten från bildens övre vänstra hörn till det nedre högra hörnet.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fyll hela bilden med den linjära gradientpenseln.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Få den närmaste 8-bitars färgpalett som täcker så många pixlar som möjligt, så att en palettiserad bild
    // är nästan visuellt omöjlig att skilja från en icke-palletiserad.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8-bitars palett innehåller högst 256 färger.
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

// Utgången ser ut så här:
// Den palettiserade bildstorleken är 11078 byte.
// Den icke-palettiserade bildstorleken är 40054 byte.
```

### Se även

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namnutrymme [Aspose.Imaging](../../colorpalettehelper)
* hopsättning [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_4}

Hämtar färgpalett från rasterbild (palleterar bild) om bilden inte har någon. Palette är på väg att optimeras för bättre indexerad bildkvalitet eller tas "AS IS" när PaletteMiningMethod.UseCurrentPalette används.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Rasterbilden. |
| entriesCount | Int32 | De önskade posterna räknas. |
| paletteMiningMethod | PaletteMiningMethod | Palettbrytningsmetoden. |

### Returvärde

Färgpaletten som börjar med de vanligaste färgerna från*image* och innehåller*entriesCount* poster.

### Exempel

Följande exempel visar hur man komprimerar en PNG-bild med hjälp av indexerad färg med palett som passar bäst

```csharp
[C#]

// Laddar png-bild        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Använd indexerad färgtyp
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Använd maximal komprimering
         CompressionLevel = 9,
      // Få den närmaste 8-bitars färgpalett som täcker så många pixlar som möjligt, så att en palettiserad bild
         // är nästan visuellt omöjlig att skilja från en icke-palletiserad.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // Utdatafilens storlek bör minskas avsevärt
```

### Se även

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namnutrymme [Aspose.Imaging](../../colorpalettehelper)
* hopsättning [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Hämtar färgpalett från rasterbild (palleterar bild) om bilden inte har någon. Om palett finns kommer den att användas istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Rasterbilden. |
| destBounds | Rectangle | Målbilden gränsar. |
| entriesCount | Int32 | De önskade posterna räknas. |

### Returvärde

Färgpaletten som börjar med de vanligaste färgerna från*image* och innehåller*entriesCount* poster.

### Se även

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namnutrymme [Aspose.Imaging](../../colorpalettehelper)
* hopsättning [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Hämtar färgpalett från rasterbild (palleterar bild) om bilden inte har någon. Om palett finns kommer den att användas istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Rasterbilden. |
| destBounds | Rectangle | Målbilden gränsar. |
| entriesCount | Int32 | De önskade posterna räknas. |
| useImagePalette | Boolean | Om den är inställd kommer den att använda sin egen bildpalett om tillgänglig |

### Returvärde

Färgpaletten som börjar med de vanligaste färgerna från*image* och innehåller*entriesCount* poster.

### Se även

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namnutrymme [Aspose.Imaging](../../colorpalettehelper)
* hopsättning [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

Hämtar färgpalett från rasterbild (palleterar bild) om bilden inte har någon. Om palett finns kommer den att användas istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Rasterbilden. |
| destBounds | Rectangle | Målbilden gränsar. |
| entriesCount | Int32 | De önskade posterna räknas. |
| useImagePalette | Boolean | Om den är inställd kommer den att använda sin egen bildpalett om tillgänglig |
| alphaBlendInColor | Color | Färgen som ska användas som bakgrundsfärg för halvtransparent alfaersättning. |

### Returvärde

Färgpaletten som börjar med de vanligaste färgerna från*image* och innehåller*entriesCount* poster.

### Se även

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namnutrymme [Aspose.Imaging](../../colorpalettehelper)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
