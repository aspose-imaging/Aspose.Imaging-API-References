---
title: "PathResourceConverter"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Преобразует  в  и обратно."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---
**Inheritance:**
java.lang.Object
```
public final class PathResourceConverter
```

Преобразует [PathResource](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) в [GraphicsPath](../../com.aspose.imaging/graphicspath) и обратно.
## Методы

| Метод | Описание |
| --- | --- |
| [toGraphicsPath(PathResource[] pathResources, Size imageSize)](#toGraphicsPath-com.aspose.imaging.fileformats.tiff.pathresources.PathResource---com.aspose.imaging.Size-) | Преобразует ресурсы пути в экземпляр [GraphicsPath](../../com.aspose.imaging/graphicspath). |
| [fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)](#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-) | Преобразует экземпляр [GraphicsPath](../../com.aspose.imaging/graphicspath) в ресурсы пути. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Создайте GraphicsPath, используя PathResources из TIFF‑изображения
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Нарисуйте красную линию и сохраните изображение
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
        // Создайте прямоугольную Figure для GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Создайте GraphicsPath, используя нашу Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Установите PathResources, используя GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Сохраните изображение
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


Преобразует ресурсы пути в экземпляр [GraphicsPath](../../com.aspose.imaging/graphicspath).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pathResources | [PathResource\[\]](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) | Ресурсы пути. |
| imageSize | [Size](../../com.aspose.imaging/size) | Размер изображения. |

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The [GraphicsPath](../../com.aspose.imaging/graphicspath) instance.
### fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize) {#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-}
```
public static PathResource[] fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)
```


Преобразует экземпляр [GraphicsPath](../../com.aspose.imaging/graphicspath) в ресурсы пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| graphicsPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Графический путь. |
| imageSize | [Size](../../com.aspose.imaging/size) | Размер изображения. |

**Returns:**
com.aspose.imaging.fileformats.tiff.pathresources.PathResource[] - ресурсы пути.
