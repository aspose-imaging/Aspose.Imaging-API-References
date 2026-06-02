---
title: "الفئة PathResource"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Tiff.PathResources.PathResource. تمثل مورد مسار Photoshop"
type: docs
weight: 7980
url: /ar/net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

يمثل Photoshop Path Resource.

```csharp
public class PathResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PathResource](pathresource/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid/) { get; set; } | يحصل أو يعيّن معرف الكتلة. |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name/) { get; set; } | يحصل أو يعيّن الاسم. |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records/) { get; set; } | يحصل أو يعيّن السجلات. |

## أمثلة

نقل مسارات القص أثناء التصدير من صورة TIFF إلى PSD.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

المثال التالي يوضح كيفية إنشاء مسار قص في صورة TIFF. للقيام بذلك تحتاج إلى إنشاء مثال من الفئة PathResource. يوضح الشيفرة التالية الطريقة التي يمكنك من خلالها إنشاء مسار فارغ في صورة TIFF.

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

إنشاء مسار رسومي من موارد المسار في صورة TIFF.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // إنشاء GraphicsPath باستخدام PathResources من صورة TIFF
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // ارسم خطًا أحمر واحفظ الصورة
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

إنشاء موارد المسار باستخدام Graphics Path.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // إنشاء شكل مستطيل لـ GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // إنشاء GraphicsPath باستخدام الشكل الخاص بنا
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // تعيين PathResources باستخدام GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // حفظ الصورة
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

إنشاء مسار قص يدويًا.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // Block Id according to Photoshop specification
            Name = "My Clipping Path",                                               // Path name
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // Create path records using coordinates
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // Create Bezier records using coordinates

    records.Insert(0, new LengthRecord                                               // LengthRecord required by Photoshop specification
    {
        IsOpen = false,                                                              // Lets create closed path
        RecordCount = (ushort)records.Count                                          // Record count in the path
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

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources/)
* assembly [Aspose.Imaging](../../)


