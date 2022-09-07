---
title: PathResource
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rappresenta la risorsa del percorso di Photoshop.
type: docs
weight: 7830
url: /it/net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

Rappresenta la risorsa del percorso di Photoshop.

```csharp
public class PathResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PathResource](pathresource)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid) { get; set; } | Ottiene o imposta l'identificatore di blocco. |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name) { get; set; } | Ottiene o imposta il nome. |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records) { get; set; } | Ottiene o imposta i record. |

### Esempi

Trasferisci tracciati di ritaglio durante l'esportazione da un'immagine TIFF a PSD.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

L'esempio seguente mostra come creare un tracciato di ritaglio nell'immagine TIFF. Per fare ciò è necessario creare un'istanza della classe PathResource. Il codice seguente mostra come creare un percorso vuoto nell'immagine TIFF.

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

Crea percorso grafico dalle risorse del percorso nell'immagine TIFF.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Crea il GraphicsPath usando PathResources dall'immagine TIFF
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Disegna una linea rossa e salva l'immagine
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Crea risorse di percorso usando il percorso grafico.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Crea una figura rettangolare per GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Crea GraphicsPath usando la nostra figura
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Imposta PathResources usando GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Salva l'immagine
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

Crea tracciato di ritaglio manualmente.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // ID blocco secondo le specifiche di Photoshop
            Name = "My Clipping Path",                                               // Nome del percorso
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // Crea record di percorso usando le coordinate
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // Crea record Bezier usando le coordinate

    records.Insert(0, new LengthRecord                                               // LengthRecord richiesto dalle specifiche di Photoshop
    {
        IsOpen = false,                                                              // Creiamo un percorso chiuso
        RecordCount = (ushort)records.Count                                          // Conteggio record nel percorso
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

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
