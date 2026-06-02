---
title: "TiffFrame.PathResources"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffFrame. يحصل أو يضبط موارد المسار"
type: docs
weight: 100
url: /ar/net/aspose.imaging.fileformats.tiff/tiffframe/pathresources/
---
## TiffFrame.PathResources property

يحصل أو يضبط موارد المسار.

```csharp
public List<PathResource> PathResources { get; set; }
```

### Property Value

موارد المسار.

## أمثلة

نقل مسارات القص أثناء التصدير من صورة TIFF إلى PSD.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

المثال التالي يوضح كيفية استرجاع المسارات من صورة TIFF وعرض أسمائها في وحدة التحكم.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Sample.tif"))
{
    foreach (var path in image.ActiveFrame.PathResources)
    {
        Console.WriteLine(path.Name);
    }
}
```

المثال التالي يوضح كيفية تعديل مسارات القص الموجودة بالفعل. على سبيل المثال، يمكنك الاحتفاظ بمسار قص واحد فقط في الصورة.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Sample.tif"))
{
    var paths = image.ActiveFrame.PathResources;
    image.ActiveFrame.PathResources = paths.Take(1).ToList();
    image.Save();
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

* class [PathResource](../../../aspose.imaging.fileformats.tiff.pathresources/pathresource/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


