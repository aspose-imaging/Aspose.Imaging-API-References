---
title: Image
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La imagen es la clase base para todo tipo de imágenes.
type: docs
weight: 9660
url: /es/aspose.imaging/image/
---
## Image class

La imagen es la clase base para todo tipo de imágenes.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../image) contenedor. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Obtiene un valor de formato de archivo |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | Obtiene la altura de la imagen. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Obtiene un valor que indica si los datos del objeto se almacenan en caché actualmente y no se requiere lectura de datos. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtiene el tamaño de la imagen. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Obtiene un valor que indica si se utiliza la paleta de imágenes. |
| abstract [Width](../../aspose.imaging/image/width) { get; } | Obtiene el ancho de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.imaging/image/create#create_1)(Image[]) | Crea una nueva imagen usando las imágenes especificadas como páginas |
| static [Create](../../aspose.imaging/image/create#create_2)(Image[], bool) | Crea una nueva imagen las imágenes especificadas como páginas. |
| static [Create](../../aspose.imaging/image/create#create)(ImageOptionsBase, int, int) | Crea una nueva imagen utilizando las opciones de creación especificadas. |
| static [Load](../../aspose.imaging/image/load#load)(Stream) | Carga una nueva imagen del flujo especificado. |
| static [Load](../../aspose.imaging/image/load#load_2)(string) | Carga una nueva imagen del archivo especificado. |
| static [Load](../../aspose.imaging/image/load#load_1)(Stream, LoadOptions) | Carga una nueva imagen del flujo especificado. |
| static [Load](../../aspose.imaging/image/load#load_3)(string, LoadOptions) | Carga una nueva imagen del archivo especificado. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el servidor subyacente.[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](./save) método como el segundo parámetro. |
| [Resize](../../aspose.imaging/image/resize#resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_1)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_2)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea la imagen. |
| [Save](../../aspose.imaging/image/save#save)() | Guarda los datos de la imagen en el flujo subyacente. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| override [Save](../../aspose.imaging/image/save#save_4)(string) | Guarda la imagen en la ubicación de archivo especificada. |
| [Save](../../aspose.imaging/image/save#save_2)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.imaging/image/save#save_5)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | Establece la paleta de la imagen. |
| static [CanLoad](../../aspose.imaging/image/canload#canload)(Stream) | Determina si la imagen se puede cargar desde el flujo especificado. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_2)(string) | Determina si la imagen se puede cargar desde la ruta de archivo especificada. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_1)(Stream, LoadOptions) | Determina si la imagen se puede cargar desde el flujo especificado y, opcionalmente, utilizando el*loadOptions* . |
| static [CanLoad](../../aspose.imaging/image/canload#canload_3)(string, LoadOptions) | Determina si la imagen se puede cargar desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat)(Stream) | Obtiene el formato de archivo. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat_1)(string) | Obtiene el formato de archivo. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight)(int, int, int) | Obtiene una altura proporcional. |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth)(int, int, int) | Obtiene un ancho proporcional. |

### Ejemplos

Determine si la paleta es utilizada por la imagen.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

Cambie el tamaño de la imagen usando un tipo de cambio de tamaño específico.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Este ejemplo crea un nuevo archivo de imagen en alguna ubicación del disco según lo especificado por la propiedad Source de la instancia de BmpOptions. Varias propiedades para la instancia de BmpOptions se establecen antes de crear la imagen real. Especialmente la propiedad Source, que se refiere a la ubicación real del disco en este caso.

```csharp
[C#]

//Cree una instancia de BmpOptions y configure sus diversas propiedades
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Cree una instancia de FileCreateSource y asígnela como Fuente para la instancia de BmpOptions
//El segundo parámetro booleano determina si el archivo a crear es temporal o no
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Cree una instancia de Image e inicialícela con una instancia de BmpOptions llamando al método Create
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //hacer un poco de procesamiento de imagen

    // guarda todos los cambios
    image.Save();
}
```

### Ver también

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
