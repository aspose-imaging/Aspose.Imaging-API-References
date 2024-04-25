---
title: PathResource
second_title: Aspose.Imaging لمرجع NET API
description: يمثل مورد مسار Photoshop .
type: docs
weight: 7830
url: /ar/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

يمثل مورد مسار Photoshop .

```csharp
public class PathResource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PathResource](pathresource)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid) { get; set; } | الحصول على أو تحديد معرف الكتلة. |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name) { get; set; } | الحصول على الاسم أو تعيينه . |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records) { get; set; } | الحصول على السجلات أو تعيينها. |

### أمثلة

انقل مسارات القطع أثناء التصدير من TIFF إلى صورة PSD.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

يوضح المثال التالي كيفية إنشاء مسار القطع في صورة TIFF. للقيام بذلك ، تحتاج إلى إنشاء مثيل لفئة PathResource. يوضح الكود التالي الطريقة التي يمكنك من خلالها إنشاء مسار فارغ في صورة TIFF.

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

قم بإنشاء مسار رسومي من Path Resources في صورة TIFF.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // أنشئ مسار الرسومات باستخدام PathResources من صورة TIFF
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // ارسم خطًا أحمر واحفظ الصورة
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

إنشاء مسار الموارد باستخدام مسار الرسومات.

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

        // احفظ الصورة
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

قم بإنشاء مسار القطع يدويًا.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // Block Id وفقًا لمواصفات Photoshop
            Name = "My Clipping Path",                                               // اسم المسار
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // إنشاء سجلات المسار باستخدام الإحداثيات
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // إنشاء سجلات بيزير باستخدام الإحداثيات

    records.Insert(0, new LengthRecord                                               // LengthRecord مطلوبة بمواصفات Photoshop
    {
        IsOpen = false,                                                              // يتيح إنشاء مسار مغلق
        RecordCount = (ushort)records.Count                                          // سجل العد في المسار
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

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
