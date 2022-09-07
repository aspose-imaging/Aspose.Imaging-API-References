---
title: AutoMaskingArgs
second_title: Aspose.Imaging for .NET API Referansı
description: Otomatik maskeleme yöntemleri için belirtilen bağımsız değişkenleri temsil eder
type: docs
weight: 10450
url: /tr/net/aspose.imaging.masking.options/automaskingargs/
---
## AutoMaskingArgs class

Otomatik maskeleme yöntemleri için belirtilen bağımsız değişkenleri temsil eder

```csharp
public class AutoMaskingArgs : IMaskingArgs
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [AutoMaskingArgs](automaskingargs)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [MaxIterationNumber](../../aspose.imaging.masking.options/automaskingargs/maxiterationnumber) { get; set; } | Maksimum yineleme sayısını alır veya ayarlar. |
| [NumberOfObjects](../../aspose.imaging.masking.options/automaskingargs/numberofobjects) { get; set; } | İlk görüntüyü (isteğe bağlı) ayırmak için nesnelerin sayısını alır veya ayarlar, varsayılan değer 2'dir (nesne ve arka plan). |
| [ObjectsPoints](../../aspose.imaging.masking.options/automaskingargs/objectspoints) { get; set; } | Ayrılmış nesnelere ait noktaları alır veya ayarlar (isteğe bağlı) İlk görüntünün NumberOfObjects nesnelerine ait NumberOfObjects koordinatları. Bu parametre, segmentasyon yöntemi kesinliğini artırmak için kullanılır. |
| [ObjectsRectangles](../../aspose.imaging.masking.options/automaskingargs/objectsrectangles) { get; set; } | Ayrılmış nesnelere ait nesne dikdörtgenlerini alır veya ayarlar (isteğe bağlı). Bu parametre, segmentasyon yöntemi kesinliğini artırmak için kullanılır. |
| [OrphanedPoints](../../aspose.imaging.masking.options/automaskingargs/orphanedpoints) { get; set; } | Artık herhangi bir nesneye ait olmayan noktaları alır veya ayarlar (isteğe bağlı). Bu parametre yalnızca yeniden segmentasyon durumunda kullanılır. |
| [Precision](../../aspose.imaging.masking.options/automaskingargs/precision) { get; set; } | Segmentasyon yönteminin kesinliğini alır veya ayarlar (isteğe bağlı). |

### Örnekler

Bu örnek, görüntü maskeleme ve K-ortalamalar segmentasyon algoritması kullanılarak bir raster görüntünün birden çok görüntüye nasıl ayrıştırılacağını gösterir. Görüntü maskeleme, arka planı ön plan görüntü nesnelerinden ayırmak için kullanılan bir görüntü işleme tekniğidir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Küme sayısını ayarlayın (ayrılmış nesneler). Varsayılan değer 2, ön plan nesnesi ve arka plandır.
    args.NumberOfObjects = 3;

    // Maksimum yineleme sayısını ayarlayın.
    args.MaxIterationNumber = 50;

    // Segmentasyon yönteminin kesinliğini ayarlayın (isteğe bağlı)
    args.Precision = 1;
        
    // Her küme (segment) ayrı bir PNG dosyasına kaydedilecektir.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // K-araç kümelemeyi kullan.
    // K-kümeleme, görüntünün birkaç bağımsız kümeye (segmentlere) bölünmesine izin verir.
    maskingOptions.Method = Masking.Options.SegmentationMethod.KMeans;
    maskingOptions.Decompose = true;
    maskingOptions.Args = args;
        
    // Arka plan rengi turuncu olacaktır.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // ImageMasking sınıfının bir örneğini oluşturun.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Kaynak görüntüyü birkaç kümeye (segmentlere) bölün.
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Maskeleme sonucundan görüntüler alın ve PNG'ye kaydedin.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
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

Bu örnek, segmentasyon (kümeleme) yönteminin kesinliğini geliştirmek için görüntü maskeleme algoritması için önerilerin nasıl belirleneceğini gösterir. Görüntü maskeleme, arka planı ön plan görüntü nesnelerinden ayırmak için kullanılan bir görüntü işleme tekniğidir.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Öneri #1.
    // Görüntüyü görsel olarak analiz edin ve ilgi alanını ayarlayın. Segmentasyonun sonucu, yalnızca tamamen bu alan içinde yer alacak nesneleri içerecektir.
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // Öneri #2.
    // Görüntüyü görsel olarak analiz edin ve ayrılmış nesnelere ait noktaları ayarlayın.
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // Her küme (segment) ayrı bir PNG dosyasına kaydedilecektir.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // GraphCut kümelemeyi kullanın.
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Arka plan rengi turuncu olacaktır.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // ImageMasking sınıfının bir örneğini oluşturun.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Kaynak görüntüyü birkaç kümeye (segmentlere) bölün.
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Maskeleme sonucundan görüntüler alın ve PNG'ye kaydedin.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Gorilla.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
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

* interface [IMaskingArgs](../imaskingargs)
* ad alanı [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
