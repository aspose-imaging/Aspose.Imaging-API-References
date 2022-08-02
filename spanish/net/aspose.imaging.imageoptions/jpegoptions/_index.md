---
title: JpegOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Las opciones de creación de formato de archivo jpeg.
type: docs
weight: 10030
url: /es/net/aspose.imaging.imageoptions/jpegoptions/
---
## JpegOptions class

Las opciones de creación de formato de archivo jpeg.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [JpegOptions](jpegoptions#constructor)() | Inicializa una nueva instancia del[`JpegOptions`](../jpegoptions) clase. |
| [JpegOptions](jpegoptions#constructor_1)(JpegOptions) | Inicializa una nueva instancia del[`JpegOptions`](../jpegoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitsPerChannel](../../aspose.imaging.imageoptions/jpegoptions/bitsperchannel) { get; set; } | Obtiene o establece bits por canal para una imagen jpeg sin pérdidas. Ahora admitimos de 2 a 8 bits por canal. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [CmykColorProfile](../../aspose.imaging.imageoptions/jpegoptions/cmykcolorprofile) { get; set; } | El perfil de color CMYK de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar en pareja con RGBColorProfile para una conversión de color correcta. |
| [ColorType](../../aspose.imaging.imageoptions/jpegoptions/colortype) { get; set; } | Obtiene o establece el tipo de color para la imagen jpeg. |
| [Comment](../../aspose.imaging.imageoptions/jpegoptions/comment) { get; set; } | Obtiene o establece el comentario del archivo jpeg. |
| [CompressionType](../../aspose.imaging.imageoptions/jpegoptions/compressiontype) { get; set; } | Obtiene o establece el tipo de compresión. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [ExifData](../../aspose.imaging.imageoptions/jpegoptions/exifdata) { get; set; } | Obtener o configurar el contenedor de datos exif |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [HorizontalSampling](../../aspose.imaging.imageoptions/jpegoptions/horizontalsampling) { get; set; } | Obtiene o establece los submuestreos horizontales para cada componente. |
| [Jfif](../../aspose.imaging.imageoptions/jpegoptions/jfif) { get; set; } | Obtiene o establece el jfif. |
| [JpegLsAllowedLossyError](../../aspose.imaging.imageoptions/jpegoptions/jpeglsallowedlossyerror) { get; set; } | Obtiene o establece el límite de diferencia de JPEG-LS para la codificación casi sin pérdidas (parámetro NEAR de la especificación JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.imaging.imageoptions/jpegoptions/jpeglsinterleavemode) { get; set; } | Obtiene o establece el modo de intercalado JPEG-LS. |
| [JpegLsPreset](../../aspose.imaging.imageoptions/jpegoptions/jpeglspreset) { get; set; } | Obtiene o establece los parámetros predeterminados de JPEG-LS. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [PreblendAlphaIfPresent](../../aspose.imaging.imageoptions/jpegoptions/preblendalphaifpresent) { get; set; } | Obtiene o establece un valor que indica si los componentes rojo, verde y azul se deben mezclar con un color de fondo, si el canal alfa está presente. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| [Quality](../../aspose.imaging.imageoptions/jpegoptions/quality) { get; set; } | Obtiene o establece la calidad de la imagen. |
| [RdOptSettings](../../aspose.imaging.imageoptions/jpegoptions/rdoptsettings) { get; set; } | Obtiene o establece la configuración del optimizador de Escritorio remoto. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/jpegoptions/resolutionunit) { get; set; } | Obtiene o establece la unidad de resolución. |
| [RgbColorProfile](../../aspose.imaging.imageoptions/jpegoptions/rgbcolorprofile) { get; set; } | El perfil de color RGB de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar en pareja con CMYKColorProfile para una conversión de color correcta. |
| [SampleRoundingMode](../../aspose.imaging.imageoptions/jpegoptions/sampleroundingmode) { get; set; } | Obtiene o establece el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits.BitsPerChannel |
| [ScaledQuality](../../aspose.imaging.imageoptions/jpegoptions/scaledquality) { get; } | La calidad escalada. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| [VerticalSampling](../../aspose.imaging.imageoptions/jpegoptions/verticalsampling) { get; set; } | Obtiene o establece los submuestreos verticales para cada componente. |
| override [XmpData](../../aspose.imaging.imageoptions/jpegoptions/xmpdata) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona esta instancia. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |

### Ejemplos

Este ejemplo demuestra el uso de System.IO.Stream para crear un nuevo archivo de imagen (un tipo JPEG)

```csharp
[C#]

//Crea una instancia de JpegOptions y establece sus diversas propiedades
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//Crear una instancia de System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//Definir la propiedad de origen para la instancia de JpegOptions
//El segundo parámetro booleano determina si el Stream se elimina una vez que sale del alcance
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//Crea una instancia de Image y llama al método Create con JpegOptions como parámetro para inicializar el objeto Image   
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //hacer un poco de procesamiento de imagen
}
```

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

El siguiente ejemplo muestra cómo convertir una imagen vectorial de varias páginas a formato JPEG de manera general sin hacer referencia a un tipo de imagen en particular.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.jpeg");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportar solo las dos primeras páginas. De hecho, solo se rasterizará una página porque JPEG no es un formato de varias páginas.
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
