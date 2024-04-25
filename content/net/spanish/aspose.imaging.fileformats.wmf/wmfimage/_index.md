---
title: WmfImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La Imagen Wmf
type: docs
weight: 9280
url: /es/aspose.imaging.fileformats.wmf/wmfimage/
---
## WmfImage class

La Imagen Wmf

```csharp
public class WmfImage : MetaImage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WmfImage](wmfimage#constructor)() | Inicializa una nueva instancia del[`WmfImage`](../wmfimage) clase. |
| [WmfImage](wmfimage#constructor_1)(int, int) | Inicializa una nueva instancia del[`WmfImage`](../wmfimage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.wmf/wmfimage/bitsperpixel) { get; } | Obtiene el recuento de bits por píxel de la imagen. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) contenedor. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| override [FileFormat](../../aspose.imaging.fileformats.wmf/wmfimage/fileformat) { get; } | Obtiene un valor de formato de archivo |
| [FrameBounds](../../aspose.imaging.fileformats.wmf/wmfimage/framebounds) { get; } | Obtiene los límites del marco. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| override [Height](../../aspose.imaging.fileformats.wmf/wmfimage/height) { get; } | Obtiene la altura de la imagen. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Obtiene la altura del objeto, en pulgadas. |
| [Inch](../../aspose.imaging.fileformats.wmf/wmfimage/inch) { get; set; } | Obtiene o establece la pulgada. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| override [IsCached](../../aspose.imaging.fileformats.wmf/wmfimage/iscached) { get; } | Obtiene un valor que indica si los datos del objeto se almacenan en caché actualmente y no se requiere lectura de datos. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records) { get; set; } | Obtiene o establece los registros. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtiene el tamaño de la imagen. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Obtiene el tamaño del objeto, en pulgadas. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Obtiene un valor que indica si se utiliza la paleta de imágenes. |
| override [Width](../../aspose.imaging.fileformats.wmf/wmfimage/width) { get; } | Obtiene el ancho de la imagen. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Obtiene el ancho del objeto, en pulgadas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddRecord](../../aspose.imaging.fileformats.wmf/wmfimage/addrecord)(WmfObject) | Agrega el registro. |
| override [CacheData](../../aspose.imaging.fileformats.wmf/wmfimage/cachedata)() | Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el subyacente [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| override [Crop](../../aspose.imaging.fileformats.wmf/wmfimage/crop#crop)(Rectangle) | Recorta el rectángulo especificado. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop)(int, int, int, int) | Recortar imagen con turnos. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.wmf/wmfimage/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Obtiene las imágenes incrustadas. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | Devuelve la lista de fuentes que se usaron dentro del metarchivo pero no se encontraron. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.imaging/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.imaging/image/save) método como el segundo parámetro. |
| [GetPostScript](../../aspose.imaging.fileformats.wmf/wmfimage/getpostscript)() | Obtiene el script de publicación. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.wmf/wmfimage/getusedfonts)() | Devuelve la lista de fuentes que se usaron dentro del metarchivo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| override [Resize](../../aspose.imaging.fileformats.wmf/wmfimage/resize#resize_1)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.imaging.fileformats.wmf/wmfimage/resize#resize_2)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.wmf/wmfimage/resizecanvas)(Rectangle) | Cambia el tamaño del lienzo. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| override [RotateFlip](../../aspose.imaging.fileformats.wmf/wmfimage/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea la imagen. |
| [Save](../../aspose.imaging/image/save)() | Guarda los datos de la imagen en el flujo subyacente. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| override [Save](../../aspose.imaging/image/save)(string) | Guarda la imagen en la ubicación de archivo especificada. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| override [SetPalette](../../aspose.imaging.fileformats.wmf/wmfimage/setpalette)(IColorPalette, bool) | Establece la paleta de la imagen. |

### Ejemplos

El siguiente ejemplo muestra cómo convertir imágenes wmz a wmf fromat

```csharp
[C#]

string file = "example.wmz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

El siguiente ejemplo muestra cómo convertir imágenes wmf a wmz fromat

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

El siguiente ejemplo muestra cómo convertir imágenes comprimidas (*.emz,*.wmz, *.svgz) a raster fromat

```csharp
[C#]

string[] files = new[] {"example.emz", "example.wmz", "example.svgz"};
string baseFolder = System.IO.Path.Combine("D:","Compressed");
foreach (var file in files)
{
    string inputFile = System.IO.Path.Combine(baseFolder, file);
    string outFile = inputFile + ".png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Color.White, image.Width, image.Height });
        image.Save(outFile, new Aspose.Imaging.ImageOptions.PngOptions(){VectorRasterizationOptions = vectorRasterizationOptions});
    }
}
```

Este ejemplo muestra cómo cargar una imagen WMF desde un archivo y convertirla a SVG usando WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// El uso de Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // El texto se convertirá en formas.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // El color de fondo de la superficie de dibujo.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // El tamaño de la página.
    rasterizationOptions.PageSize = wmfImage.Size;

    // Si existe una emf incrustada, renderizar emf; de lo contrario renderizar wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### Ver también

* class [MetaImage](../../aspose.imaging.fileformats.emf/metaimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Wmf](../../aspose.imaging.fileformats.wmf)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
