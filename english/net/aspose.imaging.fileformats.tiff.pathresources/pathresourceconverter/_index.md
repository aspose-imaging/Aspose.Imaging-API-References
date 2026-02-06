---
title: Class PathResourceConverter
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Tiff.PathResources.PathResourceConverter class. Converts PathResource to GraphicsPath and vice versa
type: docs
weight: 7990
url: /net/aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/
---
## PathResourceConverter class

Converts [`PathResource`](../pathresource/) to [`GraphicsPath`](../../aspose.imaging/graphicspath/) and vice versa.

```csharp
public static class PathResourceConverter
```

## Methods

| Name | Description |
| --- | --- |
| static [FromGraphicsPath](../../aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/fromgraphicspath/)(GraphicsPath, Size) | Converts the [`GraphicsPath`](../../aspose.imaging/graphicspath/) instance to path resources. |
| static [ToGraphicsPath](../../aspose.imaging.fileformats.tiff.pathresources/pathresourceconverter/tographicspath/)(PathResource[], Size) | Converts path resources to the [`GraphicsPath`](../../aspose.imaging/graphicspath/) instance. |

## Examples

Create Graphics Path from Path Resources in TIFF image.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Create the GraphicsPath using PathResources from TIFF image
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Draw red line and save the image
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Create Path Resources using Graphics Path.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Create rectangular Figure for GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Create GraphicsPath using our Figure
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Set PathResources using GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Save the image
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

### See Also

* namespace [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources/)
* assembly [Aspose.Imaging](../../)


