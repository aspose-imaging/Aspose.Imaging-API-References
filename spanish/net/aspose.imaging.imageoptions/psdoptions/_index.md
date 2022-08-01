---
title: PsdOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Las opciones de creación de formato de archivo psd.
type: docs
weight: 10140
url: /es/net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

Las opciones de creación de formato de archivo psd.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | Inicializa una nueva instancia del[`PsdOptions`](../psdoptions) clase. |
| [PsdOptions](psdoptions#constructor_1)(PsdOptions) | Inicializa una nueva instancia del[`PsdOptions`](../psdoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount) { get; set; } | Obtiene o establece el número de bits por canal de color. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount) { get; set; } | Obtiene o establece el recuento de canales de color. |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode) { get; set; } | Obtiene o establece el modo de color psd. |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod) { get; set; } | Obtiene o establece el método de compresión psd. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion) { get; set; } | Obtiene o establece la versión del formato del archivo. Puede ser PSD o PSB. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | Obtiene o establece un valor que indica si [actualizar datos de vista previa de la imagen]: opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD. Tenga en cuenta que las capas de texto dibujadas en el diseño final no son compatibles con la plataforma Compact Framework |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | Obtiene o establece un valor que indica si - Quitar el recurso del motor de texto global - Se utiliza para algunos archivos psd con capas de texto, en el único caso, cuando no se pueden abrir en Adobe Photoshop después del procesamiento (principalmente para las capas de texto de fuentes ausentes relacionadas). Después de usar esta opción, el usuario debe hacer lo siguiente en abrir un archivo de Photoshop: Menú "Texto" -&gt; "Procesar fuentes ausentes". Después de esa operación, todo el texto volverá a aparecer. Tenga en cuenta que esta operación puede causar algunos cambios en el diseño final. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions) { get; set; } | Obtiene o establece las opciones de vectorización PSD. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version) { get; set; } | Obtiene o establece la versión del archivo psd. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata) { get; set; } | Obtener o establecer contenedor de datos XMP |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona esta instancia. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |

### Ejemplos

Este ejemplo demuestra el uso de Aspsoe.Imaging for .Net API para convertir imágenes a formato PSD. Para lograr este objetivo, este ejemplo carga una imagen existente y luego la guarda de nuevo en formato PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

//Crea una instancia de la clase de imagen y la inicializa con un archivo existente a través de la ruta del archivo
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Crear una instancia de la clase PsdOptions
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //Establecer el método de compresión como RLE
    //Nota: Otro CompressionMethod admitido es CompressionMethod.RAW [Sin compresión]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    // Establezca el modo de color en escala de grises
    //Nota: Otros ColorModes admitidos son ColorModes.Bitmap y ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //Guarde la imagen en la ubicación del disco con la configuración de PsdOptions suministrada
    image.Save(dir + "output.psd", psdOptions);
}
```

El siguiente ejemplo muestra cómo convertir una imagen vectorial de varias páginas a formato PSD de manera general sin hacer referencia a un tipo de imagen en particular.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportar solo las dos primeras páginas. Estas páginas se presentarán como capas en el PSD de salida.
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
