---
title: "PathResourceConverter"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Konvertiert  zu  und umgekehrt."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---
**Inheritance:**
java.lang.Object
```
public final class PathResourceConverter
```

Konvertiert [PathResource](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) zu [GraphicsPath](../../com.aspose.imaging/graphicspath) und umgekehrt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [toGraphicsPath(PathResource[] pathResources, Size imageSize)](#toGraphicsPath-com.aspose.imaging.fileformats.tiff.pathresources.PathResource---com.aspose.imaging.Size-) | Konvertiert Pfadressourcen in die [GraphicsPath](../../com.aspose.imaging/graphicspath) Instanz. |
| [fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)](#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-) | Konvertiert die [GraphicsPath](../../com.aspose.imaging/graphicspath) Instanz zu Pfadressourcen. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Erstellen Sie den GraphicsPath mithilfe von PathResources aus einem TIFF-Bild
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Zeichnen Sie eine rote Linie und speichern Sie das Bild
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
        // Erstellen Sie eine rechteckige Figure für den GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Erstellen Sie den GraphicsPath mithilfe unserer Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Setzen Sie PathResources mithilfe des GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Speichern Sie das Bild
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


Konvertiert Pfadressourcen in die [GraphicsPath](../../com.aspose.imaging/graphicspath) Instanz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pathResources | [PathResource\[\]](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) | Die Pfadressourcen. |
| imageSize | [Size](../../com.aspose.imaging/size) | Größe des Bildes. |

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The [GraphicsPath](../../com.aspose.imaging/graphicspath) instance.
### fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize) {#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-}
```
public static PathResource[] fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)
```


Konvertiert die [GraphicsPath](../../com.aspose.imaging/graphicspath) Instanz zu Pfadressourcen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| graphicsPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der Grafikpfad. |
| imageSize | [Size](../../com.aspose.imaging/size) | Größe des Bildes. |

**Returns:**
com.aspose.imaging.fileformats.tiff.pathresources.PathResource[] - Die Pfadressourcen.
