---
title: PathResource
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Representa el recurso de ruta de Photoshop.
type: docs
weight: 7830
url: /es/net/aspose.imaging.fileformats.tiff.pathresources/pathresource/
---
## PathResource class

Representa el recurso de ruta de Photoshop.

```csharp
public class PathResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PathResource](pathresource)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BlockId](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/blockid) { get; set; } | Obtiene o establece el identificador del bloque. |
| [Name](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/name) { get; set; } | Obtiene o establece el nombre. |
| [Records](../../aspose.imaging.fileformats.tiff.pathresources/pathresource/records) { get; set; } | Obtiene o establece los registros. |

### Ejemplos

Transferir trazados de recorte durante la exportación de imagen TIFF a PSD.

```csharp
[C#]

using (var image = Image.Load("Sample.tif"))
{
    image.Save("SampleWithPaths.psd", new PsdOptions());
}
```

El siguiente ejemplo muestra cómo crear Clipping Path en una imagen TIFF. Para hacerlo, debe crear una instancia de la clase PathResource. El siguiente código demuestra la forma en que puede crear una ruta vacía en una imagen TIFF.

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

Cree una ruta de gráficos a partir de recursos de ruta en una imagen TIFF.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Crea GraphicsPath usando PathResources desde una imagen TIFF
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Dibujar línea roja y guardar la imagen
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Cree recursos de ruta utilizando la ruta de gráficos.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Crear figura rectangular para GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Crear GraphicsPath usando nuestra Figura
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Establecer PathResources usando GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Guarda la imagen
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

Crear ruta de recorte manualmente.

```csharp
[C#]

static void Main()
{
    using (var image = (TiffImage)Image.Load("Sample.tif"))
    {
        image.ActiveFrame.PathResources = new List<PathResource> { new PathResource
        {
            BlockId = 2000,                                                          // ID de bloque según la especificación de Photoshop
            Name = "My Clipping Path",                                               // nombre de ruta
            Records = CreateRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)  // Crear registros de ruta usando coordenadas
        }};

        image.Save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> CreateRecords(params float[] coordinates)
{
    var records = CreateBezierRecords(coordinates);                                  // Crear registros Bezier usando coordenadas

    records.Insert(0, new LengthRecord                                               // Registro de longitud requerido por la especificación de Photoshop
    {
        IsOpen = false,                                                              // Vamos a crear una ruta cerrada
        RecordCount = (ushort)records.Count                                          // Conteo de registros en la ruta
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

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Tiff.PathResources](../../aspose.imaging.fileformats.tiff.pathresources)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
