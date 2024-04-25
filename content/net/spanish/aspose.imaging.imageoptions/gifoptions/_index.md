---
title: GifOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Las opciones de creación de formato de archivo gif.
type: docs
weight: 10000
url: /es/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

Las opciones de creación de formato de archivo gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Inicializa una nueva instancia del[`GifOptions`](../gifoptions) clase. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Inicializa una nueva instancia del[`GifOptions`](../gifoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | Obtiene o establece el color de fondo. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Obtiene o establece el índice de color de fondo del GIF. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | Obtiene o establece la resolución de color del GIF. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | Obtiene o establece un valor que indica si el GIF tiene tráiler. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen GIF tiene un color transparente. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | Verdadero si la imagen debe estar entrelazada. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | Obtiene o establece el recuento de bucles (1 bucle por defecto) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | Obtiene o establece la diferencia de píxeles máxima permitida. Si es mayor que cero, se usará compresión con pérdida. El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada. Funciona mejor cuando se introduce poca pérdida y debido a la limitación del algoritmo de compresión niveles de pérdida muy altos no darán tanta ganancia. El rango de valores permitidos es [0, 1000]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Obtiene o establece la proporción de aspecto de píxeles del GIF. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona esta instancia. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |

### Ejemplos

Este ejemplo demuestra el uso de diferentes clases del espacio de nombres SaveOptions con fines de exportación. Una imagen de tipo Gif se carga en una instancia de Imagen y luego se exporta a varios formatos.

```csharp
[C#]

string dir = "c:\\temp\\";

//Cargar una imagen existente (de tipo Gif) en una instancia de la clase Imagen
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Exportar a formato de archivo BMP utilizando las opciones predeterminadas
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //Exportar a formato de archivo JPEG usando las opciones predeterminadas
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //Exportar a formato de archivo PNG usando las opciones predeterminadas
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //Exportar a formato de archivo TIFF usando las opciones predeterminadas
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

El siguiente ejemplo muestra cómo convertir una imagen vectorial de varias páginas a formato GIF de manera general sin hacer referencia a un tipo de imagen en particular.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportar solo las dos primeras páginas. Estas páginas se presentarán como marcos animados en el GIF de salida.
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

Este ejemplo muestra cómo cargar información de píxeles en una matriz de color de tipo, manipular la matriz y volver a establecerla en la imagen. Para realizar estas operaciones, este ejemplo crea un nuevo archivo de imagen (en formato GIF) utilizando el objeto MemoryStream.

```csharp
[C#]

//Crear una instancia de MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Cree una instancia de GifOptions y configure sus diversas propiedades, incluida la propiedad Fuente
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crear una instancia de Imagen
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Obtenga los píxeles de la imagen especificando el área como límite de la imagen
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //Recorre la matriz y establece el color del píxel indexado alternativo
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Establecer el color del píxel indexado en amarillo
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Establecer el color del píxel indexado en azul
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Aplicar los cambios de píxel a la imagen
        image.SavePixels(image.Bounds, pixels);

        // guarda todos los cambios.
        image.Save();
    }

    // Escribir MemoryStream en el archivo
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
