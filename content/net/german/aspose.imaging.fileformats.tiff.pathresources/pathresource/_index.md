---
title: PathResource
second_title: Aspose.Imaging für .NET-API-Referenz
description: steht für Photoshop-Pfadressource.
type: docs
weight: 7830
url: /de/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

steht für Photoshop-Pfadressource.

```csharp
public class PathResource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PathResource](pathresource)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid) { get; set; } | Ruft die Blockkennung ab oder setzt sie. |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name) { get; set; } | Ruft den Namen ab oder legt ihn fest. |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records) { get; set; } | Ruft die Datensätze ab oder legt sie fest. |

### Beispiele

Übertragen Sie Beschneidungspfade während des Exports von TIFF- zu PSD-Bildern.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

Das folgende Beispiel zeigt, wie ein Beschneidungspfad in einem TIFF-Bild erstellt wird. Dazu müssen Sie eine Instanz der PathResource-Klasse erstellen. Der folgende Code zeigt, wie Sie einen leeren Pfad in einem TIFF-Bild erstellen können.

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

Grafikpfad aus Pfadressourcen im TIFF-Bild erstellen.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // GraphicsPath mit PathResources aus TIFF-Bild erstellen
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Rote Linie zeichnen und Bild speichern
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Erstellen Sie Pfadressourcen mithilfe von Grafikpfaden.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Rechteckige Figur für GraphicsPath erstellen
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Erstellen Sie GraphicsPath mit unserer Figur
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Setze PathResources mit GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Speichern Sie das Bild
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

Beschneidungspfad manuell erstellen.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // Block-ID gemäß Photoshop-Spezifikation
            Name = "My Clipping Path",                                               // Pfadname
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // Pfaddatensätze mit Koordinaten erstellen
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // Bezier-Datensätze mit Koordinaten erstellen

    records.Insert(0, new LengthRecord                                               // LengthRecord gemäß Photoshop-Spezifikation erforderlich
    {
        IsOpen = false,                                                              // Erstellen wir einen geschlossenen Pfad
        RecordCount = (ushort)records.Count                                          // Anzahl der Datensätze im Pfad
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

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
