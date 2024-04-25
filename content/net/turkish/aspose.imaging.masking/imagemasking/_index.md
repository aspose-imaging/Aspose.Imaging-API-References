---
title: ImageMasking
second_title: Aspose.Imaging for .NET API Referansı
description: Görüntü maskeleme işlemleri sağlar
type: docs
weight: 10430
url: /tr/aspose.imaging.masking/imagemasking/
---
## ImageMasking class

Görüntü maskeleme işlemleri sağlar

```csharp
public class ImageMasking
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ImageMasking](imagemasking)(RasterImage) | Yeni bir örneğini başlatır[`ImageMasking`](../imagemasking) sınıf. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CreateSession](../../aspose.imaging.masking/imagemasking/createsession)(MaskingOptions) | Yeniden eğitme ayrıştırma işlemlerini gerçekleştirebilen maskeleme oturumunu oluşturur. |
| [Decompose](../../aspose.imaging.masking/imagemasking/decompose)(MaskingOptions) | Belirtilen maskeleme seçeneklerini kullanarak ayrıştırma işlemini gerçekleştirir |
| [DecomposeAsync](../../aspose.imaging.masking/imagemasking/decomposeasync)(MaskingOptions) | Belirtilen maskeleme seçeneklerini kullanarak eşzamansız ayrıştırma görevini oluşturur. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession#loadsession)(Stream) | Belirtilen akıştan oturumu yükleyin. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession#loadsession_1)(string) | Belirtilen dosyadan oturumu yükleyin. |
| static [ApplyMask](../../aspose.imaging.masking/imagemasking/applymask)(RasterImage, RasterImage, MaskingOptions) | Maskeyi belirtilen kaynak görüntüye uygular. |

### Örnekler

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

Uzun oturumlar için maskeleme oturumunu bir dosyaya kaydetmenin yanı sıra oturumu başka bir ortamda devam ettirme olasılığı.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// Dışa aktarma seçeneklerini maskeleme
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// GraphCut kümelemeyi kullanın.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Arka plan rengi turuncu olacaktır.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// Bir oturumu ilk kez başlatma ve bir dosyaya kaydetme
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // ImageMasking sınıfının bir örneğini oluşturun.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.CreateSession(maskingOptions))
    {
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.Decompose())
        {
            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step1.png");
            }
        }

        session.Save(sessionBackupFile);
    }
}

// Bir dosyadan maskeleme oturumunu sürdürme
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // ImageMasking sınıfının bir örneğini oluşturun.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // Görüntüyü görsel olarak analiz edin ve ayrılmış nesnelere ait noktaları ayarlayın.
        args.ObjectsPoints = new Point[][]
                                     {
                                         new Point[]
                                             {
                                                 new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                                 new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                                 new Point(3, 0), new Point(3, 1)
                                             },
                                     };
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.ImproveDecomposition(args))
        {
            // Serileştirilebilir olmadığı için dışa aktarma seçeneklerinin açık aktarımı
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.Masking](../../aspose.imaging.masking)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
