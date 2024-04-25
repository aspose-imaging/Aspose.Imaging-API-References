---
title: MetaImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Clase base para clases de metaobjetos
type: docs
weight: 6510
url: /es/aspose.imaging.fileformats.emf/metaimage/
---
## MetaImage class

Clase base para clases de metaobjetos

```csharp
public abstract class MetaImage : VectorImage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) contenedor. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Obtiene un valor de formato de archivo |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| override [Height](../../aspose.imaging/vectorimage/height) { get; } | Obtiene la altura de la imagen. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Obtiene la altura del objeto, en pulgadas. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Obtiene un valor que indica si los datos del objeto se almacenan en caché actualmente y no se requiere lectura de datos. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records) { get; set; } | Obtiene o establece los registros. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtiene el tamaño de la imagen. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Obtiene el tamaño del objeto, en pulgadas. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Obtiene un valor que indica si se utiliza la paleta de imágenes. |
| override [Width](../../aspose.imaging/vectorimage/width) { get; } | Obtiene el ancho de la imagen. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Obtiene el ancho del objeto, en pulgadas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el servidor subyacente.[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop#crop)(Rectangle) | Recorta el rectángulo especificado. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop#crop_1)(int, int, int, int) | Recortar imagen con turnos. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Obtiene las imágenes incrustadas. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | Devuelve la lista de fuentes que se usaron dentro del metarchivo pero no se encontraron. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.imaging/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.imaging/image/save) método como el segundo parámetro. |
| abstract [GetUsedFonts](../../aspose.imaging.fileformats.emf/metaimage/getusedfonts)() | Devuelve la lista de fuentes que se usaron dentro del metarchivo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| abstract [Resize](../../aspose.imaging/image/resize)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| abstract [Resize](../../aspose.imaging/image/resize)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| abstract [ResizeCanvas](../../aspose.imaging.fileformats.emf/metaimage/resizecanvas)(Rectangle) | Cambia el tamaño del lienzo. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea la imagen. |
| [Save](../../aspose.imaging/image/save)() | Guarda los datos de la imagen en el flujo subyacente. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| override [Save](../../aspose.imaging/image/save)(string) | Guarda la imagen en la ubicación de archivo especificada. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | Establece la paleta de la imagen. |

### Ver también

* class [VectorImage](../../aspose.imaging/vectorimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
