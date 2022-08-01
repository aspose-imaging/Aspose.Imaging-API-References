---
title: TiffOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Las opciones de formato de archivo tiff. Tenga en cuenta que las etiquetas de ancho y alto se sobrescribirán en la creación de la imagen por los parámetros de ancho y alto por lo que no es necesario especificarlas directamente. Tenga en cuenta que muchas opciones devuelven un valor predeterminado pero eso no significa que esta opción se establece explícitamente como un valor de etiqueta. Para verificar que la etiqueta está presente use la propiedad Tags o el método IsTagPresent correspondiente.
type: docs
weight: 10220
url: /es/net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

Las opciones de formato de archivo tiff. Tenga en cuenta que las etiquetas de ancho y alto se sobrescribirán en la creación de la imagen por los parámetros de ancho y alto, por lo que no es necesario especificarlas directamente. Tenga en cuenta que muchas opciones devuelven un valor predeterminado, pero eso no significa que esta opción se establece explícitamente como un valor de etiqueta. Para verificar que la etiqueta está presente, use la propiedad Tags o el método IsTagPresent correspondiente.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Inicializa una nueva instancia del[`TiffOptions`](../tiffoptions) clase. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Inicializa una nueva instancia del[`TiffOptions`](../tiffoptions)clase. Por defecto se usa la convención little endian. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Inicializa una nueva instancia del[`TiffOptions`](../tiffoptions) clase. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Inicializa una nueva instancia del[`TiffOptions`](../tiffoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | Obtiene o establece la opción de almacenamiento alfa. Opciones distintas aUnspecified se utilizan cuando hay más de 3[`SamplesPerPixel`](./samplesperpixel) definido. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | Obtiene o establece el artista. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | Obtiene los bits por píxel. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | Obtiene o establece los bits por muestra. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | Obtiene o establece un valor que indica el orden de bytes tiff. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | Obtiene o establece el mapa de colores. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | Obtiene o establece la calidad de la imagen comprimida. Se utiliza con la compresión Jpeg. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | Obtiene o establece la compresión. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | Obtiene o establece el copyright. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | Obtiene o establece la fecha y la hora. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | Obtiene o establece un valor que indica si la exportación del perfil ICC está deshabilitada (el perfil ICC se aplica a los píxeles de origen de antemano). |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | Obtiene o establece el nombre del documento. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | Obtiene o establece el puntero a EXIF IFD. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | Obtiene los valores de muestras adicionales. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | Obtiene o establece las opciones de fax t4. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | Obtiene o establece el archivo TIFF estándar. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | Obtiene o establece el orden de llenado de bits de byte. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | Obtiene o establece las sugerencias de medios tonos. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | Obtiene o establece el flujo de perfil Icc. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | Obtiene o establece la descripción de la imagen. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | Obtiene o establece la longitud de la imagen. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | Obtiene o establece el ancho de la imagen. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | Obtiene o establece los nombres de las tintas. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Obtiene un valor que indica si las muestras adicionales están presentes. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | Obtiene un valor que indica si la imagen está en mosaico. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | Obtiene un valor que indica si el[`TiffOptions`](../tiffoptions) han sido configurados correctamente. Utilice el método Validate para encontrar el motivo del error. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Obtiene o establece el valor de muestra máximo. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Obtiene o establece el valor de muestra mínimo. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | Obtiene o establece la orientación. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | Obtiene o establece el nombre de la página. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | Obtiene o establece la etiqueta del número de página. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | Obtiene o establece la fotométrica. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Obtiene o establece la configuración planar. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | Obtiene o establece el predictor para la compresión LZW. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Obtiene o establece un valor que indica si los componentes se deben premultiplicar. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | Obtiene o establece la unidad de resolución. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Obtiene o establece las filas por tira. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | Obtiene o establece el formato de muestra. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | Obtiene las muestras por píxel. Para cambiar el valor de esta propiedad utilice el[`BitsPerSample`](./bitspersample) establecedor de propiedades. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Obtiene o establece el fabricante del escáner. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | Obtiene o establece el modelo de escáner. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Obtiene o establece el valor de muestra máximo. El valor tiene un tipo de campo que coincide mejor con los datos de muestra (tipo Byte, Corto o Largo). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Obtiene o establece el valor de muestra mínimo. El valor tiene un tipo de campo que coincide mejor con los datos de muestra (tipo Byte, Corto o Largo). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | Obtiene o establece el tipo de software. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Obtiene o establece los recuentos de bytes de tira. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | Obtiene o establece los desplazamientos de la tira. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | Obtiene o establece una indicación general del tipo de datos contenidos en este subfile. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | Obtiene o establece las etiquetas. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | Obtiene o establece la impresora de destino. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | Obtiene o establece el umbral. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Obtiene o establece los recuentos de bytes de mosaico. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | Obtiene ot establece la longitud del mosaico. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | Obtiene o establece los desplazamientos de mosaico. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | Obtiene ot establece el ancho del mosaico. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | Obtiene el total de páginas. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | Obtiene el recuento de etiquetas válidas. Este no es el recuento total de etiquetas, sino el número de etiquetas que se pueden conservar. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | Obtiene o establece el autor de la imagen, que utiliza Windows Explorer. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | Obtiene o establece un comentario en la imagen, que utiliza Windows Explorer. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | Obtiene o establece la imagen del sujeto, que utiliza Windows Explorer. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | Obtiene o establece la posición x. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | Obtiene o establece información sobre la imagen, que utiliza Windows Explorer. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | Obtiene o establece información sobre la imagen, que utiliza Windows Explorer. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | Obtiene o establece la resolución x. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Obtiene o establece los Coeficientes YCbCr. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Obtiene o establece los factores de submuestreo para el fotométrico YCbCr. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | Obtiene o establece la posición y. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | Obtiene o establece la resolución y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | Agrega una nueva etiqueta. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Agrega las etiquetas. |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona esta instancia. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Obtiene la instancia de la etiqueta por tipo. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | Determina si la etiqueta está presente en las opciones o no. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | Elimina la etiqueta. |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | Valida si las opciones tienen una combinación válida de etiquetas |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Obtiene el recuento de etiquetas válidas. |

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

El siguiente ejemplo muestra cómo convertir una imagen vectorial de varias páginas a formato TIFF de manera general sin hacer referencia a un tipo de imagen en particular.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportar solo las dos primeras páginas. Estas páginas se presentarán como marcos en el TIFF de salida.
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

Estos ejemplos hacen uso de las clases GraphicsPath y Graphics para crear y manipular figuras en una superficie de imagen. El ejemplo crea una nueva imagen (de tipo Tiff), limpia la superficie y dibuja rutas con la ayuda de la clase GraphicsPath. Al final, se llama al método DrawPath expuesto por la clase Graphics para representar las rutas en la superficie.

```csharp
[C#]

//Crear una instancia de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Crear una instancia de TiffOptions y establecer sus diversas propiedades
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Establecer el origen de la instancia de ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crear una instancia de Imagen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Crear e inicializar una instancia de la clase Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Borrar superficie gráfica
        graphics.Clear(Color.Wheat);

        //Crear una instancia de la clase GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Crear una instancia de la clase Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Agregar formas al objeto Figura
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Agregar objeto Figura a GraphicsPath
        graphicspath.AddFigure(figure);

        //Dibujar ruta con objeto Pluma de color Negro
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // guarda todos los cambios.
        image.Save();
    }
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
