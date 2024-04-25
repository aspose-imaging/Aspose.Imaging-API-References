---
title: GifImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Una imagen gif.
type: docs
weight: 6700
url: /es/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

Una imagen gif.

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GifImage](gifimage#constructor)(GifFrameBlock) | Inicializa una nueva instancia del[`GifImage`](../gifimage) clase. |
| [GifImage](gifimage#constructor_1)(GifFrameBlock, IColorPalette) | Inicializa una nueva instancia del[`GifImage`](../gifimage) clase. |
| [GifImage](gifimage#constructor_2)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | Inicializa una nueva instancia del[`GifImage`](../gifimage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe) { get; set; } | Obtiene o establece el marco activo. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor) { get; set; } | Obtiene o establece el color de fondo. |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex) { get; set; } | Obtiene o establece el índice de color de fondo. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks) { get; } | Obtiene los bloques GIF. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) contenedor. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat) { get; } | Obtiene un valor de formato de archivo |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Obtiene un valor que indica si esta instancia tiene alfa. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor) { get; } | Obtiene un valor que indica si la imagen tiene color de fondo. |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer) { get; set; } | Obtiene o establece un valor que indica si el GIF tiene tráiler. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor) { get; set; } | Obtiene un valor que indica si el marco activo tiene color transparente. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Obtiene la altura de la imagen. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity) { get; } | Obtiene la opacidad de esta imagen (fotograma activo). |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Obtiene un valor que indica si los datos de la imagen se almacenan en caché actualmente. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced) { get; } | Obtiene un valor que indica si esta instancia de imagen está entrelazada. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted) { get; set; } | Obtiene o establece un valor que indica si la paleta está ordenada. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount) { get; set; } | Obtiene el recuento de bucles (si la imagen gif contiene información sobre bucles) |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount) { get; } | Obtiene el número de páginas. |
| override [PageExportingAction](../../aspose.imaging.fileformats.gif/gifimage/pageexportingaction) { get; set; } | Obtiene o establece la acción de exportación de la página. Tenga en cuenta que configurar este método liberará automáticamente los recursos de la página después de ejecutarlo. Se ejecutará justo antes de que se guarde cada página. |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages) { get; } | Obtiene las páginas. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits) { get; set; } | Obtiene o establece los bits de resolución de color de la paleta. |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio) { get; set; } | Obtiene o establece la relación de aspecto de píxeles. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Obtiene o establece un valor que indica si los componentes de la imagen se deben premultiplicar. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Obtiene o establece el convertidor de color personalizado |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Obtiene el formato de datos sin procesar. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Obtiene la configuración actual de datos sin procesar. Tenga en cuenta que al usar esta configuración, los datos se cargan sin conversión. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Obtiene o establece el índice alternativo que se utilizará cuando el índice de la paleta esté fuera de los límites |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Obtiene o establece el convertidor de color indexado |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Obtiene el tamaño de línea sin formato en bytes. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtiene el tamaño de la imagen. |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor) { get; } | Obtiene el color transparente del cuadro activo. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Obtiene o establece un valor que indica si se deben actualizar los metadatos XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Obtiene un valor que indica si se utiliza la paleta de imágenes. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Obtiene el ancho de la imagen. |
| override [XmpData](../../aspose.imaging.fileformats.gif/gifimage/xmpdata) { get; set; } | Obtiene o establece los metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock)(IGifBlock) | Agrega un nuevo bloque GIF. |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage)(RasterImage) | Agrega página a la imagen. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness)(int) | Ajuste de un*brightness* para imagen. |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast)(float) | Ajusta el contraste. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma)(float) | Corrección gamma de una imagen. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma_1)(float, float, float) | Corrección gamma de una imagen. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley#binarizebradley)(double) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double, int) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed)(byte) | Binarización de una imagen con umbral predefinido |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu)() | Binarización de una imagen con umbral Otsu |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Guarda en caché los datos privados. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks)() | Borra todos los bloques GIF. |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop#crop)(Rectangle) | Recortando la imagen. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop)(int, int, int, int) | Recortar imagen con turnos. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Realiza tramado en la imagen actual. |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Realiza tramado en la imagen actual. |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter)(Rectangle, FilterOptionsBase) | Filtra el rectángulo especificado. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Obtiene una imagen ARGB pixel de 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Obtiene la matriz de píxeles ARGB de 32 bits predeterminada. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Obtiene la matriz de píxeles predeterminada usando un cargador de píxeles parcial. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada mediante el cargador de píxeles parciales. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Obtiene la fecha y la hora en que se modificó por última vez la imagen del recurso. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.imaging/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.imaging/image/save) método como el segundo parámetro. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Obtiene un píxel de imagen. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Obtiene el ángulo de inclinación. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de inclinación al escanear. |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale)() | Transformación de una imagen a su representación en escala de grises |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock)(int, IGifBlock) | Agrega un nuevo bloque GIF. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Carga píxeles ARGB de 32 bits. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Carga píxeles ARGB de 64 bits. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Carga píxeles en formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Carga píxeles ARGB de 32 bits parcialmente por paquetes. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Carga píxeles parcialmente por paquetes. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Carga píxeles. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carga datos sin procesar. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) y[`Rotate`](../../aspose.imaging/rasterimage/rotate) métodos. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método utiliza!:GetSkewAngle y[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate) métodos. |
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks)() | Ordena los bloques GIF según la especificación GIF. Alguno[`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) puede eliminarse para un diseño GIF adecuado. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock)(IGifBlock) | Elimina el bloque GIF. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_1)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_2)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe)(int, int, ResizeType) | Cambia el tamaño de la imagen utilizando fotogramas completos para cada página GIF. Necesario para evitar la posible aparición de artefactos. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional)(int, int, ResizeType) | Realiza un cambio de tamaño proporcional en la imagen. El cambio de tamaño proporcional cambiará el tamaño de cada cuadro de acuerdo con la proporción de*newWidth*/ancho y*newHeight* /altura. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotar imagen alrededor del centro. |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate imagen alrededor del centro. |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea solo el marco activo. |
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
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime)(ushort) | Establece la duración de todos los cuadros en milisegundos. Cambiar este valor restablecerá el retraso para todos los cuadros. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Establece la paleta de la imagen. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Establece un píxel de imagen para la posición especificada. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Establece la resolución para este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Convierte la imagen ráster al mapa de bits. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |

### Ejemplos

Exportación de parte de la animación desde una imagen GIF según el intervalo de tiempo.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

Este ejemplo muestra cómo crear una imagen GIF y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un bloque de marco GIF de 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Rellena todo el bloque en rojo.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Cree una imagen GIF de varias páginas usando imágenes rasterizadas de una sola página.

```csharp
[C#]

static void Main(string[] args)
{
    // Cargar fotogramas
    var frames = LoadFrames("Animation frames").ToArray();

    // Crea una imagen GIF usando el primer cuadro
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Agrega marcos a la imagen GIF usando el método AddPage
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // Guardar imagen GIF
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### Ver también

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
