---
title: Resize
second_title: Aspose.Imaging för .NET API-referens
description: Ändrar storlek på bilden.
type: docs
weight: 200
url: /sv/aspose.imaging/image/resize/
---
## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändrar storlek på bilden.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| settings | ImageResizeSettings | Ändra storleksinställningar. |

### Exempel

Ändra storlek på bild med hjälp av specifik storleksändringstyp.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Det här exemplet läser in en bild och ändrar storlek på den med hjälp av olika storleksinställningar.

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

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Skala ner med 2 gånger med adaptiv resampling.
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.gif");
}
```

### Se även

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Ändrar storlek på bilden.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| resizeType | ResizeType | Storleksändringstypen. |

### Exempel

Ändra storlek på bild med hjälp av specifik storleksändringstyp.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Det här exemplet läser in en bild och ändrar storlek på den med olika storleksändringsmetoder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Skala upp 2 gånger med omsampling av närmaste granne.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Skala ner två gånger med omsampling av närmaste granne.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Skala upp 2 gånger med hjälp av bilinjär omsampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Skala ner med 2 gånger med bilinjär omsampling.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
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

## Resize(int, int) {#resize}

Ändrar storleken på bilden. StandardenNearestNeighbourResample används.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |

### Exempel

Följande exempel visar hur man ändrar storlek på en metafil (WMF och EMF).

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string[] fileNames = new[] { "image3.emf", "image4.wmf" };
foreach (string fileName in fileNames)
{
    string inputFilePath = dir + fileName;
    string outputFilePath = dir + "Downscale_" + fileName;

    using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
    {
        image.Resize(image.Width / 4, image.Height / 4);
        image.Save(outputFilePath);
    }
}
```

Följande exempel visar hur du ändrar storlek på SVG-bild och sparar den i PNG.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\net\\issues\\3549";
string[] fileNames = new string[]
{
    "Logotype.svg",
    "sample_car.svg",
    "rg1024_green_grapes.svg",
    "MidMarkerFigure.svg",
    "embeddedFonts.svg"
};

Aspose.Imaging.PointF[] scales = new Aspose.Imaging.PointF[]
{
    new Aspose.Imaging.PointF(0.5f, 0.5f),
    new Aspose.Imaging.PointF(1f, 1f),
    new Aspose.Imaging.PointF(2f, 2f),
    new Aspose.Imaging.PointF(3.5f, 9.2f),
};

foreach (string inputFile in fileNames)
{
    foreach (Aspose.Imaging.PointF scale in scales)
    {
        string outputFile = string.Format("{0}_{1}_{2}.png", inputFile, scale.X.ToString(System.Globalization.CultureInfo.InvariantCulture), scale.Y.ToString(System.Globalization.CultureInfo.InvariantCulture));
        using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(System.IO.Path.Combine(dir, inputFile)))
        {
            image.Resize((int)(image.Width * scale.X), (int)(image.Height * scale.Y));
            image.Save(System.IO.Path.Combine(dir, outputFile), new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Se även

* class [Image](../../image)
* namnutrymme [Aspose.Imaging](../../image)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
