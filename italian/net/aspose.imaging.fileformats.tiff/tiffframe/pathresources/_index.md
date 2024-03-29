---
title: PathResources
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta le risorse del percorso.
type: docs
weight: 120
url: /it/net/aspose.imaging.fileformats.tiff/tiffframe/pathresources/
---
## TiffFrame.PathResources property

Ottiene o imposta le risorse del percorso.

```csharp
public List<PathResource> PathResources { get; set; }
```

### Valore della proprietà

Le risorse del percorso.

### Esempi

Trasferisci tracciati di ritaglio durante l'esportazione da un'immagine TIFF a PSD.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

L'esempio seguente mostra come recuperare i percorsi dall'immagine TIFF e visualizzarne i nomi nella console.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Sample.tif"))
{
    foreach (var path in image.ActiveFrame.PathResources)
    {
        Console.WriteLine(path.Name);
    }
}
```

L'esempio seguente mostra come modificare i tracciati di ritaglio già esistenti. Ad esempio, puoi mantenere un solo tracciato di ritaglio nell'immagine.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Sample.tif"))
{
    var paths = image.ActiveFrame.PathResources;
    image.ActiveFrame.PathResources = paths.Take(1).ToList();
    image.Save();
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

* class [PathResource](../../../aspose.imaging.fileformats.tiff.pathresources/pathresource)
* class [TiffFrame](../../tiffframe)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
