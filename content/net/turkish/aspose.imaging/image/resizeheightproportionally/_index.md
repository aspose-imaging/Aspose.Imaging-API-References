---
title: ResizeHeightProportionally
second_title: Aspose.Imaging for .NET API Referansı
description: Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır.
type: docs
weight: 210
url: /tr/aspose.imaging/image/resizeheightproportionally/
---
## ResizeHeightProportionally(int) {#resizeheightproportionally}

Yüksekliği orantılı olarak yeniden boyutlandırır. VarsayılanNearestNeighbourResample kullanılır.

```csharp
public void ResizeHeightProportionally(int newHeight)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newHeight | Int32 | Yeni yükseklik. |

### Ayrıca bakınız

* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ResizeType) {#resizeheightproportionally_2}

Yüksekliği orantılı olarak yeniden boyutlandırır.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newHeight | Int32 | Yeni yükseklik. |
| resizeType | ResizeType | Yeniden boyutlandırma türü. |

### Örnekler

Bu örnek, bir görüntüyü yükler ve çeşitli yeniden boyutlandırma yöntemlerini kullanarak orantılı olarak yeniden boyutlandırır. Yalnızca yükseklik belirtilir, genişlik otomatik olarak hesaplanır.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // En Yakın Komşu yeniden örneklemeyi kullanarak 2 kat büyütün.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // En Yakın Komşu yeniden örneklemeyi kullanarak 2 kat küçült.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Bilinear yeniden örneklemeyi kullanarak 2 kez ölçeklendirin.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Bilineer yeniden örneklemeyi kullanarak 2 kat küçültün.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
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

## ResizeHeightProportionally(int, ImageResizeSettings) {#resizeheightproportionally_1}

Yüksekliği orantılı olarak yeniden boyutlandırır.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newHeight | Int32 | Yeni yükseklik. |
| settings | ImageResizeSettings | Görüntü yeniden boyutlandırma ayarları. |

### Ayrıca bakınız

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
