---
title: Resize
second_title: Aspose.Imaging för .NET API-referens
description: Ändrar storlek på bilden.
type: docs
weight: 260
url: /sv/net/aspose.imaging.fileformats.djvu/djvuimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Ändrar storlek på bilden.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| resizeType | ResizeType | Ändra storlek. |

### Exempel

Det här exemplet laddar en DJVU-bild och ändrar storlek på den med olika storleksändringsmetoder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Skala upp 2 gånger med omsampling av närmaste granne.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Spara till PNG med standardalternativ.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Skala ner två gånger med omsampling av närmaste granne.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Spara till PNG med standardalternativ.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Skala upp 2 gånger med hjälp av bilinjär omsampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Spara till PNG med standardalternativ.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Skala ner med 2 gånger med bilinjär omsampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Spara till PNG med standardalternativ.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [DjvuImage](../../djvuimage)
* namnutrymme [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* hopsättning [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändrar storlek på bilden.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| settings | ImageResizeSettings | Ändra storleksinställningar. |

### Exempel

Det här exemplet laddar en DJVU-bild och ändrar storleken på den med olika storleksinställningar.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// Den adaptiva algoritmen baserad på viktad och blandad rationell funktion och lanczos3-interpolation.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// Det lilla rektangulära filtret
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// Antalet färger i paletten.
resizeSettings.EntriesCount = 256;

// Färgkvantiseringen används inte
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// Den euklidiska metoden
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = (Aspose.Imaging.Image)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Skala ner med 2 gånger med adaptiv resampling.
    djvuImage.Resize(image.Width / 2, image.Height / 2, resizeSettings);

    // Spara till PNG
    djvuImage.Save(dir + "downsample.adaptive.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [DjvuImage](../../djvuimage)
* namnutrymme [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
