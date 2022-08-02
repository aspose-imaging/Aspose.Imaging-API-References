---
title: Jpeg2000Options
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Las opciones de formato de archivo JPEG2000.
type: docs
weight: 10020
url: /es/net/aspose.imaging.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Las opciones de formato de archivo JPEG2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Inicializa una nueva instancia del[`Jpeg2000Options`](../jpeg2000options) clase. |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Inicializa una nueva instancia del[`Jpeg2000Options`](../jpeg2000options) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Codec](../../aspose.imaging.imageoptions/jpeg2000options/codec) { get; set; } | Obtiene o establece el códec JPEG2000 |
| [Comments](../../aspose.imaging.imageoptions/jpeg2000options/comments) { get; set; } | Obtiene o establece los marcadores de comentario Jpeg. |
| [CompressionRatios](../../aspose.imaging.imageoptions/jpeg2000options/compressionratios) { get; set; } | Obtiene o establece la matriz de relación de compresión. Diferentes relaciones de compresión para capas sucesivas. La tasa especificada para cada nivel de calidad es el factor de compresión deseado. Relaciones decrecientes requeridas. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [Irreversible](../../aspose.imaging.imageoptions/jpeg2000options/irreversible) { get; set; } | Obtiene o establece un valor que indica si se usa la compresión DWT 9-7 irreversible (verdadero) o se usa compresión DWT 5-3 sin pérdidas (predeterminado). |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| override [XmpData](../../aspose.imaging.imageoptions/jpeg2000options/xmpdata) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona esta instancia. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |

### Ejemplos

El siguiente ejemplo muestra cómo convertir una imagen vectorial de varias páginas al formato JPEG 2000 de manera general sin hacer referencia a un tipo de imagen en particular.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.j2k");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportar solo las dos primeras páginas. De hecho, solo se rasterizará una página porque JPEG 2000 no es un formato de varias páginas.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
