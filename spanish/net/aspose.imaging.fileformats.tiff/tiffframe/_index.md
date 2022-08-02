---
title: TiffFrame
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El marco tiff.
type: docs
weight: 7870
url: /es/net/aspose.imaging.fileformats.tiff/tiffframe/
---
## TiffFrame class

El marco tiff.

```csharp
public sealed class TiffFrame : RasterCachedImage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffFrame](tiffframe#constructor_1)(RasterImage) | Inicializa una nueva instancia del[`TiffFrame`](../tiffframe) clase. |
| [TiffFrame](tiffframe#constructor_3)(Stream) | Inicializa una nueva instancia del[`TiffFrame`](../tiffframe) clase. |
| [TiffFrame](tiffframe#constructor_5)(string) | Inicializa una nueva instancia del[`TiffFrame`](../tiffframe) clase. |
| [TiffFrame](tiffframe#constructor_2)(RasterImage, TiffOptions) | Inicializa una nueva instancia del[`TiffFrame`](../tiffframe) clase. |
| [TiffFrame](tiffframe#constructor_4)(Stream, TiffOptions) | Inicializa una nueva instancia del[`TiffFrame`](../tiffframe) clase. |
| [TiffFrame](tiffframe#constructor_6)(string, TiffOptions) | Inicializa una nueva instancia del[`TiffFrame`](../tiffframe) clase. |
| [TiffFrame](tiffframe#constructor)(TiffOptions, int, int) | Inicializa una nueva instancia del[`TiffFrame`](../tiffframe) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| override [BackgroundColor](../../aspose.imaging.fileformats.tiff/tiffframe/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.tiff/tiffframe/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) contenedor. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [ExifData](../../aspose.imaging.fileformats.tiff/tiffframe/exifdata) { get; set; } | Obtiene o establece datos EXIF del marco. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Obtiene un valor de formato de archivo |
| [FrameOptions](../../aspose.imaging.fileformats.tiff/tiffframe/frameoptions) { get; } | Obtiene las opciones de creación de fotogramas. |
| override [HasAlpha](../../aspose.imaging.fileformats.tiff/tiffframe/hasalpha) { get; } | Obtiene un valor que indica si esta instancia tiene alfa. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.tiff/tiffframe/hastransparentcolor) { get; set; } | Obtiene un valor que indica si la imagen tiene color transparente. |
| override [Height](../../aspose.imaging.fileformats.tiff/tiffframe/height) { get; } | Obtiene la altura de la imagen. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.tiff/tiffframe/horizontalresolution) { get; set; } | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Obtiene la opacidad de esta imagen. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Obtiene un valor que indica si los datos de la imagen se almacenan en caché actualmente. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| [PathResources](../../aspose.imaging.fileformats.tiff/tiffframe/pathresources) { get; set; } | Obtiene o establece la ruta recursos. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Obtiene o establece un valor que indica si los componentes de la imagen se deben premultiplicar. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Obtiene o establece el convertidor de color personalizado |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Obtiene el formato de datos sin procesar. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Obtiene la configuración actual de datos sin procesar. Tenga en cuenta que al usar esta configuración, los datos se cargan sin conversión. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Obtiene o establece el índice alternativo que se utilizará cuando el índice de la paleta esté fuera de los límites |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Obtiene o establece el convertidor de color indexado |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Obtiene el tamaño de línea sin formato en bytes. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtiene el tamaño de la imagen. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Obtiene la imagen en color transparente. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Obtiene o establece un valor que indica si se deben actualizar los metadatos XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Obtiene un valor que indica si se utiliza la paleta de imágenes. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| override [VerticalResolution](../../aspose.imaging.fileformats.tiff/tiffframe/verticalresolution) { get; set; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.tiff/tiffframe/width) { get; } | Obtiene el ancho de la imagen. |
| override [XmpData](../../aspose.imaging.fileformats.tiff/tiffframe/xmpdata) { get; set; } | Obtiene o establece datos XMP del marco. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CopyFrame](../../aspose.imaging.fileformats.tiff/tiffframe/copyframe)(TiffFrame) | Copia el fotograma completo (duplica). |
| static [CreateFrameFrom](../../aspose.imaging.fileformats.tiff/tiffframe/createframefrom)(TiffFrame, TiffOptions) | Crea el marco de especificado*tiffFrame* utilizando el especificado*options* . Los datos de píxeles se conservan pero se convierten al formato deseado. |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Ajuste de un brillo para la imagen. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Contraste de imagen |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Corrección gamma de una imagen. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Corrección gamma de una imagen. |
| [AlignResolutions](../../aspose.imaging.fileformats.tiff/tiffframe/alignresolutions)() | Método auxiliar para igualar las resoluciones horizontal y vertical. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Binarización de una imagen con umbral predefinido |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Binarización de una imagen con umbral Otsu |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el servidor subyacente.[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffframe/crop#crop)(Rectangle) | Recortando la imagen. |
| virtual [Crop](../../aspose.imaging/rasterimage/crop)(int, int, int, int) | Recortar imagen con turnos. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Realiza tramado en la imagen actual. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Realiza tramado en la imagen actual. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Filtra el rectángulo especificado. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Obtiene una imagen ARGB pixel de 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Obtiene la matriz de píxeles ARGB de 32 bits predeterminada. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Obtiene la matriz de píxeles predeterminada usando un cargador de píxeles parcial. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada mediante el cargador de píxeles parciales. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Obtiene la fecha y la hora en que se modificó por última vez la imagen del recurso. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.tiff/tiffframe/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.imaging/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.imaging/image/save) método como el segundo parámetro. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Obtiene un píxel de imagen. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Obtiene el ángulo de inclinación. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de inclinación al escanear. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale)() | Transformación de una imagen a su representación en escala de grises |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Carga píxeles ARGB de 32 bits. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Carga píxeles ARGB de 64 bits. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Carga píxeles en formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Carga píxeles ARGB de 32 bits parcialmente por paquetes. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Carga píxeles parcialmente por paquetes. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Carga píxeles. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) y[`Rotate`](../../aspose.imaging/rasterimage/rotate) métodos. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)(bool, Color) | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) y[`Rotate`](../../aspose.imaging/rasterimage/rotate) métodos. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(int, byte, int) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(int) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffframe/resize#resize_2)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotar imagen alrededor del centro. |
| override [Rotate](../../aspose.imaging.fileformats.tiff/tiffframe/rotate#rotate_1)(float, bool, Color) | Rotar imagen alrededor del centro. |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea la imagen. |
| [Save](../../aspose.imaging/image/save)() | Guarda los datos de la imagen en el flujo subyacente. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| override [Save](../../aspose.imaging/image/save)(string) | Guarda la imagen en la ubicación de archivo especificada. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Guarda los píxeles ARGB de 32 bits. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Guarda los píxeles. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Guarda los píxeles. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Guarda los datos sin procesar. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Establece un píxel ARGB de 32 bits de imagen para la posición especificada. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Establece la paleta de la imagen. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Establece un píxel de imagen para la posición especificada. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Establece la resolución para este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Convierte la imagen ráster al mapa de bits. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |

### Ejemplos

Este ejemplo muestra cómo crear una imagen TIFF desde cero y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Establecer 8 bits para cada componente de color.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Establecer el orden de bytes Big Endian (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Establecer la compresión LZW.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Establecer el modelo de color RGB.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Todos los componentes de color se almacenarán en un solo plano.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Crea un Marco TIFF de 100x100 px.
// Tenga en cuenta que no tiene que desechar un marco explícitamente si está incluido en TiffImage.
// Cuando se desecha el contenedor, todos los marcos se desecharán automáticamente.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Rellena todo el cuadro con el degradado azul-amarillo.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Crea una imagen TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

### Ver también

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
