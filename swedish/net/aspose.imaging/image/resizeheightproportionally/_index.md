---
title: ResizeHeightProportionally
second_title: Aspose.Imaging för .NET API-referens
description: Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används.
type: docs
weight: 210
url: /sv/net/aspose.imaging/image/resizeheightproportionally/
---
## ResizeHeightProportionally(int) {#resizeheightproportionally}

Ändrar storleken på höjden proportionellt. StandardenNearestNeighbourResample används.

```csharp
public void ResizeHeightProportionally(int newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | Int32 | Den nya höjden. |

### Se även

* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ResizeType) {#resizeheightproportionally_2}

Ändrar storleken på höjden proportionellt.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | Int32 | Den nya höjden. |
| resizeType | ResizeType | Typ av storleksändring. |

### Exempel

Det här exemplet läser in en bild och ändrar storlek på den proportionellt med olika storleksändringsmetoder. Endast höjden anges, bredden beräknas automatiskt.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Skala upp 2 gånger med omsampling av närmaste granne.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Skala ner två gånger med omsampling av närmaste granne.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Skala upp 2 gånger med hjälp av bilinjär omsampling.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Skala ner med 2 gånger med bilinjär omsampling.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

Använda en segmentmask för att påskynda segmenteringsprocessen

```csharp
[C#]

// Maskering av exportalternativ
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Använd GraphCut-klustring.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Bakgrundsfärgen kommer att vara transparent.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Minska bildstorleken för att påskynda segmenteringsprocessen
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Skapa en instans av klassen ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Får förgrundsmasken
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Öka storleken på masken till storleken på originalbilden
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Applicera masken på originalbilden för att få ett förgrundssegment
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### Se även

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ImageResizeSettings) {#resizeheightproportionally_1}

Ändrar storleken på höjden proportionellt.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newHeight | Int32 | Den nya höjden. |
| settings | ImageResizeSettings | Inställningarna för storleksändring av bilden. |

### Se även

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
