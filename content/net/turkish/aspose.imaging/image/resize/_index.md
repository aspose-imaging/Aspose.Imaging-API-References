---
title: Resize
second_title: Aspose.Imaging for .NET API Referansı
description: Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır.
type: docs
weight: 200
url: /tr/aspose.imaging/image/resize/
---
## Resize(int, int) {#resize}

Resmi yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |

### Örnekler

Aşağıdaki örnek, bir meta dosyasının (WMF ve EMF) nasıl yeniden boyutlandırılacağını gösterir.

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

Aşağıdaki örnek, SVG görüntüsünün nasıl yeniden boyutlandırılacağını ve PNG'ye nasıl kaydedileceğini gösterir.

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

### Ayrıca bakınız

* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Resmi yeniden boyutlandırır.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| resizeType | ResizeType | Yeniden boyutlandırma türü. |

### Örnekler

Belirli Yeniden Boyutlandırma Türünü kullanarak görüntüyü yeniden boyutlandırın.

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

Bu örnek, bir görüntüyü yükler ve çeşitli yeniden boyutlandırma yöntemlerini kullanarak yeniden boyutlandırır.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // En Yakın Komşu yeniden örneklemeyi kullanarak 2 kat büyütün.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // En Yakın Komşu yeniden örneklemeyi kullanarak 2 kat küçült.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Bilinear yeniden örneklemeyi kullanarak 2 kez ölçeklendirin.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Bilineer yeniden örneklemeyi kullanarak 2 kat küçültün.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

Segmentasyon sürecini hızlandırmak için segment maskesi kullanma

```csharp
[C#]

// Dışa aktarma seçeneklerini maskeleme
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// GraphCut kümelemeyi kullanın.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Arka plan rengi şeffaf olacaktır.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Segmentasyon sürecini hızlandırmak için görüntü boyutunu küçültme
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // ImageMasking sınıfının bir örneğini oluşturun.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Kaynak görüntüyü birkaç kümeye (segmentlere) bölün.
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Ön plan maskesinin alınması
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Maskenin boyutunu orijinal görüntünün boyutuna yükseltin
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Bir ön plan segmenti elde etmek için maskeyi orijinal görüntüye uygulamak
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### Ayrıca bakınız

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Resmi yeniden boyutlandırır.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| settings | ImageResizeSettings | Yeniden boyutlandırma ayarları. |

### Örnekler

Belirli Yeniden Boyutlandırma Türünü kullanarak görüntüyü yeniden boyutlandırın.

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

Bu örnek, bir görüntüyü yükler ve çeşitli yeniden boyutlandırma ayarlarını kullanarak yeniden boyutlandırır.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// Ağırlıklı ve harmanlanmış rasyonel fonksiyona ve lanczos3 enterpolasyonuna dayalı uyarlanabilir algoritma.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// Küçük dikdörtgen filtre
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// Paletteki renk sayısı.
resizeSettings.EntriesCount = 256;

// Renk niceleme kullanılmaz
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// Öklid yöntemi
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Uyarlanabilir yeniden örneklemeyi kullanarak 2 kat küçültün.
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.gif");
}
```

### Ayrıca bakınız

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
