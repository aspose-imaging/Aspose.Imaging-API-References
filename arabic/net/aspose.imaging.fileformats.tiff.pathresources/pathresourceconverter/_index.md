---
title: "الفئة PathResourceConverter"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Tiff.PathResources.PathResourceConverter. تقوم بتحويل PathResource إلى GraphicsPath والعكس"
type: docs
weight: 7990
url: /ar/net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---
## PathResourceConverter class

يقوم بتحويل [`PathResource`](../pathresource/) إلى [`GraphicsPath`](../../aspose.imaging/graphicspath/) والعكس.

```csharp
public static class PathResourceConverter
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromGraphicsPath](../../aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/fromgraphicspath/)(GraphicsPath, Size) | يقوم بتحويل المثيل [`GraphicsPath`](../../aspose.imaging/graphicspath/) إلى موارد المسار. |
| static [ToGraphicsPath](../../aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/tographicspath/)(PathResource[], Size) | يقوم بتحويل موارد المسار إلى المثيل [`GraphicsPath`](../../aspose.imaging/graphicspath/). |

## أمثلة

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

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources/)
* assembly [Aspose.Imaging](../../)


