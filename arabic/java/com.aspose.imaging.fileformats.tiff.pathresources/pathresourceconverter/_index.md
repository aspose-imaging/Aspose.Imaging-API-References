---
title: "PathResourceConverter"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحول  إلى  والعكس بالعكس."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---
**Inheritance:**
java.lang.Object
```
public final class PathResourceConverter
```

يحول [PathResource](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) إلى [GraphicsPath](../../com.aspose.imaging/graphicspath) والعكس بالعكس.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [toGraphicsPath(PathResource[] pathResources, Size imageSize)](#toGraphicsPath-com.aspose.imaging.fileformats.tiff.pathresources.PathResource---com.aspose.imaging.Size-) | يحول موارد المسار إلى مثيل [GraphicsPath](../../com.aspose.imaging/graphicspath). |
| [fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)](#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-) | يحول مثيل [GraphicsPath](../../com.aspose.imaging/graphicspath) إلى موارد المسار. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // إنشاء GraphicsPath باستخدام PathResources من صورة TIFF
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // ارسم خطًا أحمر واحفظ الصورة
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // إنشاء Figure مستطيلة لـ GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // إنشاء GraphicsPath باستخدام Figure الخاص بنا
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // تعيين PathResources باستخدام GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // احفظ الصورة
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### toGraphicsPath(PathResource[] pathResources, Size imageSize) {#toGraphicsPath-com.aspose.imaging.fileformats.tiff.pathresources.PathResource---com.aspose.imaging.Size-}
```
public static GraphicsPath toGraphicsPath(PathResource[] pathResources, Size imageSize)
```


يحول موارد المسار إلى مثيل [GraphicsPath](../../com.aspose.imaging/graphicspath).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pathResources | [PathResource\[\]](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) | موارد المسار. |
| imageSize | [Size](../../com.aspose.imaging/size) | حجم الصورة. |

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The [GraphicsPath](../../com.aspose.imaging/graphicspath) instance.
### fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize) {#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-}
```
public static PathResource[] fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)
```


يحول مثيل [GraphicsPath](../../com.aspose.imaging/graphicspath) إلى موارد المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| graphicsPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | مسار الرسومات. |
| imageSize | [Size](../../com.aspose.imaging/size) | حجم الصورة. |

**Returns:**
com.aspose.imaging.fileformats.tiff.pathresources.PathResource[] - موارد المسار.
