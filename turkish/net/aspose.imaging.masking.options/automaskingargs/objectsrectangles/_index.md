---
title: ObjectsRectangles
second_title: Aspose.Imaging for .NET API Referansı
description: Ayrılmış nesnelere ait nesne dikdörtgenlerini alır veya ayarlar isteğe bağlı. Bu parametre segmentasyon yöntemi kesinliğini artırmak için kullanılır.
type: docs
weight: 50
url: /tr/net/aspose.imaging.masking.options/automaskingargs/objectsrectangles/
---
## AutoMaskingArgs.ObjectsRectangles property

Ayrılmış nesnelere ait nesne dikdörtgenlerini alır veya ayarlar (isteğe bağlı). Bu parametre, segmentasyon yöntemi kesinliğini artırmak için kullanılır.

```csharp
public Rectangle[] ObjectsRectangles { get; set; }
```

### Mülk değeri

Nesneler dikdörtgenler.

### Örnekler

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

### Ayrıca bakınız

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [AutoMaskingArgs](../../automaskingargs)
* ad alanı [Aspose.Imaging.Masking.Options](../../automaskingargs)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
