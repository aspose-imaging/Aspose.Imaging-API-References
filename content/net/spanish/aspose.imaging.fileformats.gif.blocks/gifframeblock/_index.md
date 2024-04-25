---
title: GifFrameBlock
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Bloque de marco gif.
type: docs
weight: 6630
url: /es/aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
## GifFrameBlock class

Bloque de marco gif.

```csharp
public sealed class GifFrameBlock : RasterCachedImage, IAnimationFrame, IGifBlock
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GifFrameBlock](gifframeblock#constructor)(RasterImage) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_3)(Stream) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_6)(string) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_9)(ushort, ushort) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_1)(RasterImage, ushort, ushort) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_4)(Stream, ushort, ushort) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_7)(string, ushort, ushort) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_10)(ushort, ushort, ushort, ushort) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_2)(RasterImage, ushort, ushort, bool, bool, byte) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_5)(Stream, ushort, ushort, bool, bool, byte) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_8)(string, ushort, ushort, bool, bool, byte) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |
| [GifFrameBlock](gifframeblock#constructor_11)(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) | Inicializa una nueva instancia del[`GifFrameBlock`](../gifframeblock) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) contenedor. |
| [ControlBlock](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/controlblock) { get; } | Obtiene el bloque de control de gráficos asociado a este bloque. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [DisposalMethod](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/disposalmethod) { get; } | Obtiene el método de eliminación. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| override [FileFormat](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/fileformat) { get; } | Obtiene un valor de formato de archivo |
| [Flags](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/flags) { get; set; } | Obtiene o establece las banderas. |
| [FrameLeft](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/frameleft) { get; } | Obtiene la izquierda. |
| [FrameTime](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/frametime) { get; set; } | Obtiene o establece la duración. |
| [FrameTop](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/frametop) { get; } | Convierte a p. |
| [GifFrameBitsPerPixel](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframebitsperpixel) { get; set; } | Obtiene o establece los bits de cuadro GIF por píxel. |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha) { get; } | Obtiene un valor que indica si esta instancia tiene alfa. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/hastransparentcolor) { get; set; } | Obtiene un valor que indica si el bloque de marco tiene un color transparente. |
| override [Height](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/height) { get; } | Obtiene la altura de la imagen. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Obtiene la opacidad de esta imagen. |
| [Interlaced](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/interlaced) { get; set; } | Obtiene o establece un valor que indica si este[`GifFrameBlock`](../gifframeblock) está entrelazado. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Obtiene un valor que indica si los datos de la imagen se almacenan en caché actualmente. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/isinterlaced) { get; } | Obtiene un valor que indica si esta instancia de imagen está entrelazada. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/ispalettesorted) { get; set; } | Obtiene o establece un valor que indica si la paleta de colores está ordenada. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [Left](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/left) { get; set; } | Obtiene o establece la ubicación de la imagen izquierda. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Obtiene o establece un valor que indica si los componentes de la imagen se deben premultiplicar. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Obtiene o establece el convertidor de color personalizado |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Obtiene el formato de datos sin procesar. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Obtiene la configuración actual de datos sin procesar. Tenga en cuenta que al usar esta configuración, los datos se cargan sin conversión. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Obtiene o establece el índice alternativo que se utilizará cuando el índice de la paleta esté fuera de los límites |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Obtiene o establece el convertidor de color indexado |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Obtiene el tamaño de línea sin formato en bytes. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtiene el tamaño de la imagen. |
| [Top](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/top) { get; set; } | Obtiene o establece la ubicación de la imagen superior. |
| override [TransparentColor](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/transparentcolor) { get; set; } | Obtiene el color transparente del bloque del marco. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Obtiene o establece un valor que indica si se deben actualizar los metadatos XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Obtiene un valor que indica si se utiliza la paleta de imágenes. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/width) { get; } | Obtiene el ancho de la imagen. |
| virtual [XmpData](../../aspose.imaging/rasterimage/xmpdata) { get; set; } | Obtiene o establece los metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/adjustbrightness)(int) | Ajuste de un brillo para la imagen. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Contraste de imagen |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Corrección gamma de una imagen. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Corrección gamma de una imagen. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Binarización de una imagen con umbral predefinido |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Binarización de una imagen con umbral Otsu |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el servidor subyacente.[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| override [Crop](../../aspose.imaging/rastercachedimage/crop)(Rectangle) | Recortando la imagen. |
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
| [GetFullFrame](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/getfullframe)() | Obtiene el fotograma completo. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Obtiene la fecha y la hora en que se modificó por última vez la imagen del recurso. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.imaging/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.imaging/image/save) método como el segundo parámetro. |
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
| override [ReplaceColor](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/replacecolor#replacecolor_1)(int, byte, int) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/replacenontransparentcolors#replacenontransparentcolors_1)(int) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotar imagen alrededor del centro. |
| override [Rotate](../../aspose.imaging/rastercachedimage/rotate)(float, bool, Color) | Rotar imagen alrededor del centro. |
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
| static [CreateFlags](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/createflags)(IColorPalette, bool, bool) | Crea las banderas. |
| static [GetColorPalette](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/getcolorpalette)(IColorPalette, IColorPalette) | Obtiene la paleta de colores asociada. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [ExtensionLabel](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/extensionlabel) | Etiqueta de extensión de bloque. |
| const [ImageDescriptorSize](../../aspose.imaging.fileformats.gif.blocks/gifframeblock/imagedescriptorsize) | El tamaño del descriptor de la imagen. |

### Ver también

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* interface [IAnimationFrame](../../aspose.imaging/ianimationframe)
* interface [IGifBlock](../../aspose.imaging.fileformats.gif/igifblock)
* espacio de nombres [Aspose.Imaging.FileFormats.Gif.Blocks](../../aspose.imaging.fileformats.gif.blocks)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
