---
title: EpsInterchangeImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Clase para formato de intercambio de PostScript encapsulado
type: docs
weight: 6570
url: /es/aspose.imaging.fileformats.eps/epsinterchangeimage/
---
## EpsInterchangeImage class

Clase para formato de intercambio de PostScript encapsulado

```csharp
public class EpsInterchangeImage : EpsImage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [BoundingBoxBottomLeft](../../aspose.imaging.fileformats.eps/epsimage/boundingboxbottomleft) { get; } | Obtiene la posición inferior izquierda del cuadro delimitador |
| [BoundingBoxString](../../aspose.imaging.fileformats.eps/epsimage/boundingboxstring) { get; } | Obtiene el valor de la cadena BoundingBox |
| [BoundingBoxTopRight](../../aspose.imaging.fileformats.eps/epsimage/boundingboxtopright) { get; } | Obtiene la posición superior derecha del cuadro delimitador |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) contenedor. |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate) { get; } | Obtiene el campo CreationDate |
| [CreationDateString](../../aspose.imaging.fileformats.eps/epsimage/creationdatestring) { get; } | Obtiene el valor de cadena del campo CreationDate |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator) { get; } | Obtiene el campo Creador |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| override [EpsType](../../aspose.imaging.fileformats.eps/epsinterchangeimage/epstype) { get; } | Obtiene el valor del subtipo EPS |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat) { get; } | Obtiene un valor de formato de archivo |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| override [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsinterchangeimage/hasrasterpreview) { get; } | Obtiene un valor que indica si esta instancia tiene una vista previa de ráster específica del formato |
| override [Height](../../aspose.imaging.fileformats.eps/epsimage/height) { get; } | Obtiene la altura de la imagen. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Obtiene la altura del objeto, en pulgadas. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached) { get; } | Obtiene un valor que indica si los datos del objeto se almacenan en caché actualmente y no se requiere lectura de datos. |
| [PageNumber](../../aspose.imaging.fileformats.eps/epsimage/pagenumber) { get; } | Obtiene el número de página |
| [PagesCount](../../aspose.imaging.fileformats.eps/epsimage/pagescount) { get; } | Obtiene el número de páginas |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| [PhotoshopThumbnail](../../aspose.imaging.fileformats.eps/epsimage/photoshopthumbnail) { get; } | Obtiene la vista previa en miniatura de Photoshop (si está presente en los datos EPS iniciales) |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion) { get; } | Obtiene la versión de PostScript field |
| [PreviewHeight](../../aspose.imaging.fileformats.eps/epsinterchangeimage/previewheight) { get; } | Obtiene la altura de la imagen de vista previa |
| [PreviewWidth](../../aspose.imaging.fileformats.eps/epsinterchangeimage/previewwidth) { get; } | Obtiene el ancho de la imagen de vista previa |
| [RasterPreview](../../aspose.imaging.fileformats.eps/epsinterchangeimage/rasterpreview) { get; } | Obtiene una vista previa de trama en blanco y negro (si está presente) o null |
| [Size](../../aspose.imaging/image/size) { get; } | Obtiene el tamaño de la imagen. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Obtiene el tamaño del objeto, en pulgadas. |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title) { get; } | Obtiene el campo Título |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Obtiene un valor que indica si se utiliza la paleta de imágenes. |
| override [Width](../../aspose.imaging.fileformats.eps/epsimage/width) { get; } | Obtiene el ancho de la imagen. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Obtiene el ancho del objeto, en pulgadas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata)() | No se puede usar el caché. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| [ConvertToBinary](../../aspose.imaging.fileformats.eps/epsinterchangeimage/converttobinary)() | Convierte esta instancia en[`EpsBinaryImage`](../epsbinaryimage) |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.eps/epsimage/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Obtiene las imágenes incrustadas. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.imaging/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.imaging/image/save) método como el segundo parámetro. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| override [RotateFlip](../../aspose.imaging.fileformats.eps/epsimage/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea la imagen. |
| [Save](../../aspose.imaging/image/save)() | Guarda los datos de la imagen en el flujo subyacente. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| override [Save](../../aspose.imaging/image/save)(string) | Guarda la imagen en la ubicación de archivo especificada. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette)(IColorPalette, bool) | Establece la paleta de la imagen. |
| [explicit operator](../../aspose.imaging.fileformats.eps/epsinterchangeimage/op_explicit) | Realiza una conversión explícita de[`EpsBinaryImage`](../epsbinaryimage) a[`EpsInterchangeImage`](../epsinterchangeimage) |

### Ver también

* class [EpsImage](../epsimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
