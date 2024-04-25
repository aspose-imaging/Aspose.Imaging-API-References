---
title: GetCloseImagePalette
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Farbpalette vom Rasterbild ab palettiert das Bild falls das Bild keine hat. Falls eine Palette vorhanden ist wird sie verwendet anstatt Berechnungen durchzuführen.
type: docs
weight: 60
url: /de/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

Ruft die Farbpalette vom Rasterbild ab (palettiert das Bild), falls das Bild keine hat. Falls eine Palette vorhanden ist, wird sie verwendet, anstatt Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| entriesCount | Int32 | Es zählen die gewünschten Einträge. |

### Rückgabewert

Die Farbpalette, die mit den häufigsten Farben aus dem beginnt*image* und enthält*entriesCount* Einträge.

### Beispiele

Das folgende Beispiel lädt ein BMP-Bild und speichert es mit verschiedenen Speicheroptionen wieder in BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // BmpOptions erstellen
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Verwenden Sie 8 Bit pro Pixel, um die Größe des Ausgabebilds zu reduzieren.
    saveOptions.BitsPerPixel = 8;

    // Legen Sie die nächste 8-Bit-Farbpalette fest, die die maximale Anzahl von Bildpixeln abdeckt, sodass ein palettisiertes Bild entsteht
    // ist optisch kaum von einem nicht palettierten zu unterscheiden.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Ohne Komprimierung speichern.
    // Sie können auch die RLE-8-Komprimierung verwenden, um die Größe des Ausgabebilds zu reduzieren.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Legen Sie die horizontale und vertikale Auflösung auf 96 dpi fest.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

Das folgende Beispiel zeigt, wie ein BMP-Bild palettiert wird, um seine Ausgabegröße zu reduzieren.

```csharp
[C#]

// Erstellen Sie ein BMP-Bild 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Füllen Sie das gesamte Bild mit dem linearen Verlaufspinsel.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Holen Sie sich die nächste 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, um ein palettisiertes Bild zu erhalten
    // ist optisch kaum von einem nicht palettierten zu unterscheiden.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8-Bit-Palette enthält höchstens 256 Farben.
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

// Die Ausgabe sieht so aus:
// Die palettierte Bildgröße beträgt 11078 Bytes.
// Die nicht palettierte Bildgröße beträgt 40054 Byte.
```

### Siehe auch

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namensraum [Aspose.Imaging](../../colorpalettehelper)
* Montage [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_4}

Ruft die Farbpalette vom Rasterbild ab (palettiert das Bild), falls das Bild keine hat. Die Palette wird gerade für eine bessere indizierte Bildqualität optimiert oder "WIE BESEHEN" übernommen, wenn PaletteMiningMethod.UseCurrentPalette verwendet wird.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| entriesCount | Int32 | Es zählen die gewünschten Einträge. |
| paletteMiningMethod | PaletteMiningMethod | Die Palette-Mining-Methode. |

### Rückgabewert

Die Farbpalette, die mit den häufigsten Farben aus dem beginnt*image* und enthält*entriesCount* Einträge.

### Beispiele

Das folgende Beispiel zeigt, wie Sie ein PNG-Bild komprimieren, indem Sie indizierte Farben mit der Palette „Best Fit“ verwenden

```csharp
[C#]

// PNG-Bild wird geladen        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Indizierten Farbtyp verwenden
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Maximale Komprimierung verwenden
         CompressionLevel = 9,
      // Holen Sie sich die nächste 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, um ein palettisiertes Bild zu erhalten
         // ist optisch kaum von einem nicht palettierten zu unterscheiden.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // Die Größe der Ausgabedatei sollte erheblich reduziert werden
```

### Siehe auch

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namensraum [Aspose.Imaging](../../colorpalettehelper)
* Montage [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Ruft die Farbpalette vom Rasterbild ab (palettiert das Bild), falls das Bild keine hat. Falls eine Palette vorhanden ist, wird sie verwendet, anstatt Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| destBounds | Rectangle | Die Zielbildgrenzen. |
| entriesCount | Int32 | Es zählen die gewünschten Einträge. |

### Rückgabewert

Die Farbpalette, die mit den häufigsten Farben aus dem beginnt*image* und enthält*entriesCount* Einträge.

### Siehe auch

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namensraum [Aspose.Imaging](../../colorpalettehelper)
* Montage [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Ruft die Farbpalette vom Rasterbild ab (palettiert das Bild), falls das Bild keine hat. Falls eine Palette vorhanden ist, wird sie verwendet, anstatt Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| destBounds | Rectangle | Die Zielbildgrenzen. |
| entriesCount | Int32 | Es zählen die gewünschten Einträge. |
| useImagePalette | Boolean | Wenn gesetzt, wird eine eigene Bildpalette verwendet, falls verfügbar |

### Rückgabewert

Die Farbpalette, die mit den häufigsten Farben aus dem beginnt*image* und enthält*entriesCount* Einträge.

### Siehe auch

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namensraum [Aspose.Imaging](../../colorpalettehelper)
* Montage [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

Ruft die Farbpalette vom Rasterbild ab (palettiert das Bild), falls das Bild keine hat. Falls eine Palette vorhanden ist, wird sie verwendet, anstatt Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| destBounds | Rectangle | Die Zielbildgrenzen. |
| entriesCount | Int32 | Es zählen die gewünschten Einträge. |
| useImagePalette | Boolean | Wenn gesetzt, wird eine eigene Bildpalette verwendet, falls verfügbar |
| alphaBlendInColor | Color | Die Farbe, die als Hintergrundfarbe für den halbtransparenten Alpha-Ersatz verwendet werden soll. |

### Rückgabewert

Die Farbpalette, die mit den häufigsten Farben aus dem beginnt*image* und enthält*entriesCount* Einträge.

### Siehe auch

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namensraum [Aspose.Imaging](../../colorpalettehelper)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
