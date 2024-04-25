---
title: PathResource
second_title: Aspose.Imaging för .NET API-referens
description: Representerar Photoshop Path Resource.
type: docs
weight: 7830
url: /sv/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

Representerar Photoshop Path Resource.

```csharp
public class PathResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PathResource](pathresource)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid) { get; set; } | Hämtar eller ställer in blockidentifieraren. |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name) { get; set; } | Hämtar eller ställer in namnet. |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records) { get; set; } | Hämtar eller sätter rekord. |

### Exempel

Överför urklippsbanor under export från TIFF till PSD-bild.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

Följande exempel visar hur man skapar urklippsbana i TIFF-bild. För att göra det måste du skapa en instans av PathResource-klassen. Följande kod visar hur du kan skapa en tom sökväg i TIFF-bilden.

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

Skapa grafiksökväg från sökvägsresurser i TIFF-bild.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Skapa GraphicsPath med PathResources från TIFF-bilden
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Rita röd linje och spara bilden
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Skapa sökvägsresurser med hjälp av grafisk sökväg.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Skapa rektangulär figur för GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Skapa GraphicsPath med vår figur
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Ställ in PathResources med GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Spara bilden
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

Skapa urklippsbana manuellt.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // Block-ID enligt Photoshop-specifikationen
            Name = "My Clipping Path",                                               // Sökvägsnamn
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // Skapa sökvägsposter med hjälp av koordinater
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // Skapa Bezier-poster med hjälp av koordinater

    records.Insert(0, new LengthRecord                                               // LengthRecord krävs enligt Photoshop-specifikationen
    {
        IsOpen = false,                                                              // Låt oss skapa en stängd väg
        RecordCount = (ushort)records.Count                                          // Rekordräkning i sökvägen
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

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
