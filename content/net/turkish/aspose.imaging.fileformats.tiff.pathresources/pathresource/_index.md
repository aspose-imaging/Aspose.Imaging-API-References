---
title: PathResource
second_title: Aspose.Imaging for .NET API Referansı
description: Photoshop Yol Kaynağını temsil eder.
type: docs
weight: 7830
url: /tr/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

Photoshop Yol Kaynağını temsil eder.

```csharp
public class PathResource
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PathResource](pathresource)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid) { get; set; } | Blok tanımlayıcısını alır veya ayarlar. |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name) { get; set; } | Adı alır veya ayarlar. |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records) { get; set; } | Kayıtları alır veya ayarlar. |

### Örnekler

TIFF'den PSD görüntüsüne dışa aktarma sırasında Kırpma Yollarını aktarın.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

Aşağıdaki örnek, TIFF görüntüsünde Kırpma Yolunun nasıl oluşturulacağını gösterir. Bunu yapmak için PathResource sınıfının bir örneğini oluşturmanız gerekir. Aşağıdaki kod, TIFF görüntüsünde nasıl boş bir yol oluşturabileceğinizi gösterir.

```csharp
[C#]

var options = new TiffOptions(TiffExpectedFormat.Default);
var frame = new TiffFrame(options, 800, 600);

using (var image = new TiffImage(frame))
{
    image.ActiveFrame.PathResources = new List<PathResource>
    {
        new PathResource
        {
            BlockId = 2000,
            Name = "My Clipping Path",
            Records = new List<VectorPathRecord>()
        }
    };

    image.Save("ImageWithEmptyPath.tiff");
}
```

TIFF görüntüsünde Yol Kaynaklarından Grafik Yolu oluşturun.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // TIFF görüntüsünden PathResources kullanarak GraphicsPath'i oluşturun
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Kırmızı çizgi çiz ve görüntüyü kaydet
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Grafik Yolu kullanarak Yol Kaynakları oluşturun.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // GraphicsPath için dikdörtgen Şekil oluştur
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Figürümüzü kullanarak GraphicsPath oluşturun
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // GraphicsPath kullanarak PathResources'u ayarlayın
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Resmi kaydet
        image.Save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape CreateBezierShape(params float[] coordinates)
{
    var bezierPoints = CoordinatesToBezierPoints(coordinates).ToArray();
    return new BezierShape(bezierPoints, true);
}

private static IEnumerable<PointF> CoordinatesToBezierPoints(float[] coordinates)
{
    for (var coordinateIndex = 0; coordinateIndex < coordinates.Length; coordinateIndex += 2)
        for (var index = 0; index < 3; index++)
            yield return new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
}
```

El ile Kırpma Yolu oluşturun.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // Photoshop özelliklerine göre kimliği engelle
            Name = "My Clipping Path",                                               // Yol adı
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // Koordinatları kullanarak yol kayıtları oluşturun
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // Koordinatları kullanarak Bezier kayıtları oluşturun

    records.Insert(0, new LengthRecord                                               // Photoshop spesifikasyonu tarafından gerekli olan Uzunluk Kaydı
    {
        IsOpen = false,                                                              // Kapalı yol oluşturalım
        RecordCount = (ushort)records.Count                                          // Yoldaki kayıt sayısı
    });

    return records;
}

private static List<VectorPathRecord> CreateBezierRecords(float[] coordinates)
{
    return CoordinatesToPoints(coordinates)
        .Select(CreateBezierRecord)
        .ToList();
}

private static IEnumerable<PointF> CoordinatesToPoints(float[] coordinates)
{
    for (var index = 0; index < coordinates.Length; index += 2)
        yield return new PointF(coordinates[index], coordinates[index + 1]);
}

private static VectorPathRecord CreateBezierRecord(PointF point)
{
    return new BezierKnotRecord { PathPoints = new[] { point, point, point } };
}
```

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
