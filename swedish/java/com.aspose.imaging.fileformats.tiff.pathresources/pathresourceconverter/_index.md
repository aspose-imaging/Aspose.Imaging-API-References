---
title: "PathResourceConverter"
second_title: "Aspose.Imaging för Java API-referens"
description: "Konverterar  till  och vice versa."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---
**Inheritance:**
java.lang.Object
```
public final class PathResourceConverter
```

Konverterar [PathResource](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) till [GraphicsPath](../../com.aspose.imaging/graphicspath) och vice versa.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [toGraphicsPath(PathResource[] pathResources, Size imageSize)](#toGraphicsPath-com.aspose.imaging.fileformats.tiff.pathresources.PathResource---com.aspose.imaging.Size-) | Konverterar sökvägsresurser till den [GraphicsPath](../../com.aspose.imaging/graphicspath) instansen. |
| [fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)](#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-) | Konverterar den [GraphicsPath](../../com.aspose.imaging/graphicspath) instansen till sökvägsresurser. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Skapa GraphicsPath med PathResources från TIFF-bild
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Rita en röd linje och spara bilden
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
        // Skapa rektangulär Figure för GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Skapa GraphicsPath med vår Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Ställ in PathResources med GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Spara bilden
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


Konverterar sökvägsresurser till den [GraphicsPath](../../com.aspose.imaging/graphicspath) instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pathResources | [PathResource\[\]](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) | Sökvägsresurserna. |
| imageSize | [Size](../../com.aspose.imaging/size) | Storlek på bilden. |

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The [GraphicsPath](../../com.aspose.imaging/graphicspath) instance.
### fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize) {#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-}
```
public static PathResource[] fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)
```


Konverterar den [GraphicsPath](../../com.aspose.imaging/graphicspath) instansen till sökvägsresurser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| graphicsPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Grafikvägen. |
| imageSize | [Size](../../com.aspose.imaging/size) | Storlek på bilden. |

**Returns:**
com.aspose.imaging.fileformats.tiff.pathresources.PathResource[] - sökvägsresurserna.
