---
title: DjvuImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Clase de documento Djvu
type: docs
weight: 2440
url: /es/aspose.imaging.fileformats.djvu/djvuimage/
---
## DjvuImage class

Clase de documento Djvu

```csharp
public sealed class DjvuImage : RasterCachedMultipageImage, INotifyPropertyChanged
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DjvuImage](djvuimage#constructor)(Stream) | Inicializa una nueva instancia del[`DjvuImage`](../djvuimage) clase. |
| [DjvuImage](djvuimage#constructor_1)(Stream, LoadOptions) | Inicializa una nueva instancia del[`DjvuImage`](../djvuimage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.djvu/djvuimage/activepage) { get; set; } | Obtiene o establece la página actualmente activa |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) contenedor. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [DjvuPages](../../aspose.imaging.fileformats.djvu/djvuimage/djvupages) { get; } | Obtiene las páginas del documento |
| override [FileFormat](../../aspose.imaging.fileformats.djvu/djvuimage/fileformat) { get; } | Obtiene un valor de formato de archivo |
| [FirstPage](../../aspose.imaging.fileformats.djvu/djvuimage/firstpage) { get; } | Obtiene la primera página del documento |
| override [HasAlpha](../../aspose.imaging.fileformats.djvu/djvuimage/hasalpha) { get; } | Obtiene el canal Tiene alfa. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Obtiene un valor que indica si la imagen tiene color transparente. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Obtiene la altura de la imagen. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| [Identifier](../../aspose.imaging.fileformats.djvu/djvuimage/identifier) { get; } | Obtiene el identificador único del documento |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Obtiene la opacidad de esta imagen. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Obtiene un valor que indica si los datos de la imagen se almacenan en caché actualmente. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| [LastPage](../../aspose.imaging.fileformats.djvu/djvuimage/lastpage) { get; } | Obtiene la última página del documento |
| [NextPage](../../aspose.imaging.fileformats.djvu/djvuimage/nextpage) { get; } | Obtiene la página siguiente del documento |
| override [PageCount](../../aspose.imaging.fileformats.djvu/djvuimage/pagecount) { get; } | Obtiene el número de páginas. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction) { get; set; } | Obtiene o establece la acción de exportación de la página. Tenga en cuenta que configurar este método liberará automáticamente los recursos de la página después de ejecutarlo. Se ejecutará justo antes de que se guarde cada página. |
| override [Pages](../../aspose.imaging.fileformats.djvu/djvuimage/pages) { get; } | Obtiene las páginas. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Obtiene o establece un valor que indica si los componentes de la imagen se deben premultiplicar. |
| [PreviousPage](../../aspose.imaging.fileformats.djvu/djvuimage/previouspage) { get; } | Obtiene la página anterior del documento |
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
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Obtiene el ancho de la imagen. |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | Obtiene o establece datos XMP del marco. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument#loaddocument)(Stream) | Carga el documento. |
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument#loaddocument_1)(Stream, LoadOptions) | Carga el documento. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.djvu/djvuimage/adjustbrightness)(int) | Ajuste de un*brightness* para imagen. |
| override [AdjustContrast](../../aspose.imaging.fileformats.djvu/djvuimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrastando |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma#adjustgamma)(float) | Corrección gamma de una imagen. |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma#adjustgamma_1)(float, float, float) | Corrección gamma de una imagen. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeBradley](../../aspose.imaging.fileformats.djvu/djvuimage/binarizebradley#binarizebradley_1)(double, int) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley usando el umbral de imagen integral |
| override [BinarizeFixed](../../aspose.imaging.fileformats.djvu/djvuimage/binarizefixed)(byte) | Binarización de una imagen con umbral predefinido |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu)() | Binarización de una imagen con umbral Otsu |
| override [CacheData](../../aspose.imaging.fileformats.djvu/djvuimage/cachedata)() | Guarda en caché los datos privados. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop#crop)(Rectangle) | Recortando la imagen. |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop#crop_1)(int, int, int, int) | Recortar imagen con turnos. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Realiza tramado en la imagen actual. |
| override [Dither](../../aspose.imaging.fileformats.djvu/djvuimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Realiza tramado en la imagen actual. |
| override [Filter](../../aspose.imaging.fileformats.djvu/djvuimage/filter)(Rectangle, FilterOptionsBase) | Filtra el rectángulo especificado. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Obtiene una imagen ARGB pixel de 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Obtiene la matriz de píxeles ARGB de 32 bits predeterminada. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Obtiene la matriz de píxeles predeterminada usando un cargador de píxeles parcial. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtiene la matriz de datos sin procesar predeterminada mediante el cargador de píxeles parciales. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Obtiene la fecha y la hora en que se modificó por última vez la imagen del recurso. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.imaging/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.imaging/image/save) método como el segundo parámetro. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Obtiene un píxel de imagen. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Obtiene el ángulo de inclinación. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de inclinación al escanear. |
| override [Grayscale](../../aspose.imaging.fileformats.djvu/djvuimage/grayscale)() | Transformación de una imagen a su representación en escala de grises |
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
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Lee toda la línea de escaneo por el índice de línea de escaneo especificado. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Reemplaza un color por otro con la diferencia permitida y conserva el valor alfa original para guardar bordes suaves. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para guardar bordes suaves. Nota: si lo usa en imágenes sin transparencia, todos los colores serán reemplazados por uno solo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize#resize_1)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize#resize_2)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotar imagen alrededor del centro. |
| override [Rotate](../../aspose.imaging.fileformats.djvu/djvuimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate imagen alrededor del centro. |
| override [RotateFlip](../../aspose.imaging.fileformats.djvu/djvuimage/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea solo el marco activo. |
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

Este ejemplo muestra cómo cargar una imagen DJVU desde un flujo de archivos.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivos.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // Guarde cada página como una imagen PNG individual.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // Generar un nombre de archivo basado en el número de página.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Ver también

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Djvu](../../aspose.imaging.fileformats.djvu)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
