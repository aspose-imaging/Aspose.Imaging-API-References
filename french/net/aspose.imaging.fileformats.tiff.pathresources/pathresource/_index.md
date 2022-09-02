---
title: PathResource
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Représente la ressource de chemin Photoshop.
type: docs
weight: 7830
url: /fr/net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

Représente la ressource de chemin Photoshop.

```csharp
public class PathResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PathResource](pathresource)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid) { get; set; } | Obtient ou définit l'identifiant du bloc. |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name) { get; set; } | Obtient ou définit le nom. |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records) { get; set; } | Obtient ou définit les enregistrements. |

### Exemples

Transférez les chemins de détourage lors de l'exportation d'une image TIFF vers une image PSD.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

L'exemple suivant montre comment créer un chemin de détourage dans une image TIFF. Pour ce faire, vous devez créer une instance de la classe PathResource. Le code suivant montre comment créer un chemin vide dans une image TIFF.

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

Créer un chemin graphique à partir des ressources de chemin dans l'image TIFF.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Créer le GraphicsPath en utilisant PathResources à partir de l'image TIFF
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Dessine une ligne rouge et enregistre l'image
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Créez des ressources de chemin à l'aide de Graphics Path.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Crée une figure rectangulaire pour GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Créer GraphicsPath en utilisant notre Figure
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Définir PathResources à l'aide de GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Enregistrer l'image
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

Créez manuellement un chemin de détourage.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // Id de bloc selon les spécifications de Photoshop
            Name = "My Clipping Path",                                               // Nom du chemin
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // Créer des enregistrements de chemin à l'aide de coordonnées
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // Crée des enregistrements de Bézier à l'aide de coordonnées

    records.Insert(0, new LengthRecord                                               // LengthRecord requis par la spécification Photoshop
    {
        IsOpen = false,                                                              // Permet de créer un chemin fermé
        RecordCount = (ushort)records.Count                                          // Nombre d'enregistrements dans le chemin
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

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
