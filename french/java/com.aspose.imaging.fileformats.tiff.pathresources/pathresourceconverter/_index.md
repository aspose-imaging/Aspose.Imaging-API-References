---
title: "PathResourceConverter"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Convertit  en  et vice versa."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---
**Inheritance:**
java.lang.Object
```
public final class PathResourceConverter
```

Convertit [PathResource](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) en [GraphicsPath](../../com.aspose.imaging/graphicspath) et vice versa.
## Méthodes

| Méthode | Description |
| --- | --- |
| [toGraphicsPath(PathResource[] pathResources, Size imageSize)](#toGraphicsPath-com.aspose.imaging.fileformats.tiff.pathresources.PathResource---com.aspose.imaging.Size-) | Convertit les ressources de chemin en l'instance [GraphicsPath](../../com.aspose.imaging/graphicspath). |
| [fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)](#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-) | Convertit l'instance [GraphicsPath](../../com.aspose.imaging/graphicspath) en ressources de chemin. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Créer le GraphicsPath en utilisant PathResources à partir d'une image TIFF
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Dessiner une ligne rouge et enregistrer l'image
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
        // Créer une Figure rectangulaire pour GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Créer GraphicsPath en utilisant notre Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Définir PathResources en utilisant GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Enregistrer l'image
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


Convertit les ressources de chemin en l'instance [GraphicsPath](../../com.aspose.imaging/graphicspath).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pathResources | [PathResource\[\]](../../com.aspose.imaging.fileformats.tiff.pathresources/pathresource) | Les ressources de chemin. |
| imageSize | [Size](../../com.aspose.imaging/size) | Taille de l'image. |

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The [GraphicsPath](../../com.aspose.imaging/graphicspath) instance.
### fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize) {#fromGraphicsPath-com.aspose.imaging.GraphicsPath-com.aspose.imaging.Size-}
```
public static PathResource[] fromGraphicsPath(GraphicsPath graphicsPath, Size imageSize)
```


Convertit l'instance [GraphicsPath](../../com.aspose.imaging/graphicspath) en ressources de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| graphicsPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Le chemin graphique. |
| imageSize | [Size](../../com.aspose.imaging/size) | Taille de l'image. |

**Returns:**
com.aspose.imaging.fileformats.tiff.pathresources.PathResource[] - Les ressources de chemin.
