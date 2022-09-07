---
title: DefaultObjectsRectangles
second_title: Aspose.Imaging for .NET API Referansı
description: Varsayılan nesne dikdörtgenlerini alır.
type: docs
weight: 60
url: /tr/net/aspose.imaging.masking.options/automaskinggraphcutoptions/defaultobjectsrectangles/
---
## AutoMaskingGraphCutOptions.DefaultObjectsRectangles property

Varsayılan nesne dikdörtgenlerini alır.

```csharp
public Rectangle[] DefaultObjectsRectangles { get; }
```

### Örnekler

Görüntü boyutuna dayalı geçiş yumuşatma ile görüntü maskeleme sonucunu kaydetme ve yeni maskeleme yinelemesi için maskeleme seçeneklerini yeniden kullanma. Görüntü maskeleme, otomatik olarak hesaplanan varsayılan vuruşlar kullanılarak gerçekleştirilir. Ek olarak, varsayılan iki nesnenin verileri de AutoMaskingGraphCutOptions'ın AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucunu aldıktan sonra, uygulanan arka plan/ön plan vuruşları değiştirilir ve başka bir maskeleme yinelemesi gerçekleştirilir.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;
using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// Bu noktada uygulanan ön/arka plan vuruşları analiz edilebilir ve buna bağlı olarak ek 
// ön plan/arka plan vuruşları manuel olarak sağlanabilir.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    // AutoMaskingGraphCutOptions'ı yeniden kullanarak, varsayılan vuruş hesaplamalarını ikinci kez gerçekleştirmeye gerek yoktur.
    options.CalculateDefaultStrokes = false;
    // AutoMaskingArgs'ın Args özelliğinde hem varsayılan konturlar hem de ObjectsPoints sağlandığında, Point dizileri birleştirilir.
    // İlk ObjectsPoints dizisi, arka plan noktaları dizisi olarak kabul edilir ve 
    // ikinci ObjectsPoints dizisi, bir ön plan noktaları dizisi olarak kabul edilir.
    // AutoMaskingArgs'ın Args özelliğinde hem DefaultObjectsRectangles hem de ObjectsRectangles sağlandığında, 
    // sadece Args'den gelen dizi kullanılıyor.
    options.Args = new AutoMaskingArgs()
                        {
                            ObjectsPoints = new Point[][]
                                                {
                                                    new Point[] { new Point(100, 100), new Point(150, 100) }, 
                                                    new Point[] { new Point(500, 200) }, 
                                                },
                            ObjectsRectangles = new Rectangle[]
                                                    {
                                                        new Rectangle(100, 100, 300, 300), 
                                                    }
                        };
    results = new ImageMasking(image).Decompose(options);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

Görüntü boyutuna dayalı geçiş yumuşatma ile görüntü maskeleme sonucunu kaydetme, elde edilen varsayılan konturları değiştirme ve bunu yeni maskeleme yinelemesi için kullanma. Görüntü maskeleme, otomatik olarak hesaplanan varsayılan vuruşlar kullanılarak gerçekleştirilir. Ek olarak, varsayılan iki nesnenin verileri de AutoMaskingGraphCutOptions'ın AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucunu aldıktan sonra, uygulanan arka plan/ön plan vuruşları değiştirilir ve yeni GraphCutMaskingOptions örneği kullanılarak başka bir maskeleme yinelemesi gerçekleştirilir.

```csharp
[C#]

List<AssumedObjectData> assumedObjects = new List<AssumedObjectData>();
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.Add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options;

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    options = new AutoMaskingGraphCutOptions
                    {
                        AssumedObjects = assumedObjects,
                        CalculateDefaultStrokes = true,
                        FeatheringRadius = 3,
                        Method = SegmentationMethod.GraphCut,
                        Decompose = false,
                        ExportOptions =
                            new PngOptions()
                                {
                                    ColorType = PngColorType.TruecolorWithAlpha,
                                    Source = new FileCreateSource("tempFile")
                                },
                        BackgroundReplacementColor = Color.Transparent
                    };

    results = new ImageMasking(image).Decompose(options);
}

// Bu noktada uygulanan ön/arka plan vuruşları analiz edilebilir ve buna bağlı olarak ek 
// ön plan/arka plan vuruşları manuel olarak sağlanabilir.
Point[] appliedBackgroundStrokes = options.DefaultBackgroundStrokes;
Point[] appliedForegroundStrokes = options.DefaultForegroundStrokes;
Rectangle[] appliedObjectRectangles = options.DefaultObjectsRectangles;
using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

using (RasterImage image = (RasterImage)Image.Load("input.jpg"))
{
    GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions()
                                                    {
                                                        FeatheringRadius = 3,
                                                        Method = SegmentationMethod.GraphCut,
                                                        Decompose = false,
                                                        ExportOptions = new PngOptions()
                                                                            {
                                                                                ColorType = PngColorType.TruecolorWithAlpha,
                                                                                Source = new FileCreateSource("tempFile")
                                                                            },
                                                        BackgroundReplacementColor = Color.Transparent,
                                                        Args = new AutoMaskingArgs()
                                                                {
                                                                    ObjectsPoints = new Point[][]
                                                                                        {
                                                                                            appliedBackgroundStrokes,
                                                                                            appliedForegroundStrokes
                                                                                        },
                                                                    ObjectsRectangles = appliedObjectRectangles
                                                                }
                                                    };
    results = new ImageMasking(image).Decompose(graphCutOptions);
}

using (RasterImage resultImage = (RasterImage)results[1].GetImage())
{
    resultImage.Save("output.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ayrıca bakınız

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [AutoMaskingGraphCutOptions](../../automaskinggraphcutoptions)
* ad alanı [Aspose.Imaging.Masking.Options](../../automaskinggraphcutoptions)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
