---
title: CdrImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La imagen Cdr.
type: docs
weight: 1420
url: /es/aspose.imaging.fileformats.cdr/cdrimage/
---
## CdrImage class

La imagen Cdr.

```csharp
public class CdrImage : VectorMultipageImage, ICdrImage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CdrImage](cdrimage)(Stream, LoadOptions) | Inicializa una nueva instancia del[`CdrImage`](../cdrimage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.cdr/cdrimage/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [CdrDocument](../../aspose.imaging.fileformats.cdr/cdrimage/cdrdocument) { get; } | Obtiene o establece el documento CDR. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) contenedor. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| override [FileFormat](../../aspose.imaging.fileformats.cdr/cdrimage/fileformat) { get; } | Obtiene un valor de formato de archivo |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| override [Height](../../aspose.imaging.fileformats.cdr/cdrimage/height) { get; } | Obtiene la altura de la imagen. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Obtiene la altura del objeto, en pulgadas. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| override [IsCached](../../aspose.imaging.fileformats.cdr/cdrimage/iscached) { get; } | Obtiene un valor que indica si los datos del objeto se almacenan en caché actualmente y no se requiere lectura de datos. |
| override [PageCount](../../aspose.imaging.fileformats.cdr/cdrimage/pagecount) { get; } | Obtiene o establece el número de páginas. |
| override [PageExportingAction](../../aspose.imaging.fileformats.cdr/cdrimage/pageexportingaction) { get; set; } | Obtiene o establece la acción de exportación de la página. Tenga en cuenta que configurar este método liberará automáticamente los recursos de la página después de ejecutarlo. Se ejecutará justo antes de que se guarde cada página. |
| override [Pages](../../aspose.imaging.fileformats.cdr/cdrimage/pages) { get; } | Obtiene las páginas. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtiene el tamaño de la imagen. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Obtiene el tamaño del objeto, en pulgadas. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Obtiene un valor que indica si se utiliza la paleta de imágenes. |
| override [Width](../../aspose.imaging.fileformats.cdr/cdrimage/width) { get; } | Obtiene el ancho de la imagen. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Obtiene el ancho del objeto, en pulgadas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.cdr/cdrimage/cachedata)() | Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el subyacente [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.cdr/cdrimage/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | Obtiene las imágenes incrustadas. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.imaging/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.imaging/image/save) método como el segundo parámetro. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| override [Resize](../../aspose.imaging.fileformats.cdr/cdrimage/resize#resize_1)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.imaging.fileformats.cdr/cdrimage/resize#resize_2)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| override [RotateFlip](../../aspose.imaging.fileformats.cdr/cdrimage/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea la imagen. |
| [Save](../../aspose.imaging/image/save)() | Guarda los datos de la imagen en el flujo subyacente. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| override [Save](../../aspose.imaging/image/save)(string) | Guarda la imagen en la ubicación de archivo especificada. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| override [SetPalette](../../aspose.imaging.fileformats.cdr/cdrimage/setpalette)(IColorPalette, bool) | Establece la paleta de la imagen. |

### Ejemplos

El siguiente ejemplo muestra cómo almacenar en caché todas las páginas de una imagen CDR.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carga una imagen desde un archivo CDR.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // Esta llamada almacena en caché solo la página predeterminada.
    image.CacheData();

    // Almacenar en caché todas las páginas para que no se realice ninguna carga de datos adicional desde el flujo de datos subyacente.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### Ver también

* class [Image](../../aspose.imaging/image)
* interface [ICdrImage](../icdrimage)
* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Cdr](../../aspose.imaging.fileformats.cdr)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
