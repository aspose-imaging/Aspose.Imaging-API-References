---
title: Resize
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet.
type: docs
weight: 200
url: /de/aspose.imaging/image/resize/
---
## Resize(int, int) {#resize}

Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |

### Beispiele

Das folgende Beispiel zeigt, wie die Größe einer Metadatei (WMF und EMF) geändert wird.

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

Das folgende Beispiel zeigt, wie Sie die Größe eines SVG-Bildes ändern und es als PNG speichern.

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

### Siehe auch

* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Ändert die Bildgröße.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| resizeType | ResizeType | Der Größenänderungstyp. |

### Beispiele

Ändern Sie die Bildgröße mit einem bestimmten Größenänderungstyp.

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

In diesem Beispiel wird ein Bild geladen und mithilfe verschiedener Methoden zur Größenänderung in der Größe geändert.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Auf das Zweifache skalieren mit Nearest Neighbor Resampling.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Mit Nearest Neighbor Resampling um das Zweifache herunterskalieren.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Mit bilinearem Resampling um das Zweifache hochskalieren.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Mit bilinearem Resampling um das Zweifache herunterskalieren.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

Verwenden einer Segmentmaske, um den Segmentierungsprozess zu beschleunigen

```csharp
[C#]

// Exportoptionen maskieren
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// GraphCut-Clustering verwenden.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Die Hintergrundfarbe wird transparent sein.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Reduzieren der Bildgröße, um den Segmentierungsprozess zu beschleunigen
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Erstellen Sie eine Instanz der ImageMasking-Klasse.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Erhalte die Vordergrundmaske
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Erhöhen Sie die Größe der Maske auf die Größe des Originalbildes
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Anwenden der Maske auf das Originalbild, um ein Vordergrundsegment zu erhalten
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### Siehe auch

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändert die Bildgröße.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| settings | ImageResizeSettings | Die Größenänderungseinstellungen. |

### Beispiele

Ändern Sie die Bildgröße mit einem bestimmten Größenänderungstyp.

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

In diesem Beispiel wird ein Bild geladen und mithilfe verschiedener Größenanpassungseinstellungen in der Größe geändert.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// Der adaptive Algorithmus basiert auf gewichteter und gemischter rationaler Funktion und Lanczos3-Interpolation.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// Der kleine rechteckige Filter
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// Die Anzahl der Farben in der Palette.
resizeSettings.EntriesCount = 256;

// Die Farbquantisierung wird nicht verwendet
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// Die euklidische Methode
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Mit adaptivem Resampling um das Zweifache herunterskalieren.
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.gif");
}
```

### Siehe auch

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
