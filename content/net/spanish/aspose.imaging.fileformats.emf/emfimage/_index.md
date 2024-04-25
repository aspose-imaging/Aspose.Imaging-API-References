---
title: EmfImage
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Imagen de formato de archivo EMF.
type: docs
weight: 4670
url: /es/aspose.imaging.fileformats.emf/emfimage/
---
## EmfImage class

Imagen de formato de archivo EMF.

```csharp
public sealed class EmfImage : MetaImage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfImage](emfimage#constructor)() | Inicializa una nueva instancia del[`EmfImage`](../emfimage) clase. |
| [EmfImage](emfimage#constructor_1)(int, int) | Inicializa una nueva instancia del[`EmfImage`](../emfimage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Obtiene o establece un valor que indica si la paleta se ajusta automáticamente. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Obtiene o establece un valor para el color de fondo. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.emf/emfimage/bitsperpixel) { get; } | Obtiene el conteo de bits por píxel de la imagen. Este parámetro no es aplicable a imágenes vectoriales |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Obtiene los límites de la imagen. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Container](../../aspose.imaging/image/container) { get; } | Obtiene el[`Image`](../../aspose.imaging/image) contenedor. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| override [FileFormat](../../aspose.imaging.fileformats.emf/emfimage/fileformat) { get; } | Obtiene un valor de formato de archivo |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| [Header](../../aspose.imaging.fileformats.emf/emfimage/header) { get; set; } | Obtiene o establece el registro de cabecera |
| override [Height](../../aspose.imaging.fileformats.emf/emfimage/height) { get; } | Obtiene la altura de la imagen. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Obtiene la altura del objeto, en pulgadas. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Obtiene o establece el monitor de interrupción. |
| override [IsCached](../../aspose.imaging.fileformats.emf/emfimage/iscached) { get; } | Obtiene un valor que indica si los datos del objeto se almacenan en caché actualmente y no se requiere lectura de datos. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| override [Records](../../aspose.imaging.fileformats.emf/emfimage/records) { get; set; } | Obtiene o establece los registros. |
| [Size](../../aspose.imaging/image/size) { get; } | Obtiene el tamaño de la imagen. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Obtiene el tamaño del objeto, en pulgadas. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Obtiene un valor que indica si se utiliza la paleta de imágenes. |
| override [Width](../../aspose.imaging.fileformats.emf/emfimage/width) { get; } | Obtiene el ancho de la imagen. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Obtiene el ancho del objeto, en pulgadas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.emf/emfimage/cachedata)() | Almacena en caché los datos y garantiza que no se realizará ninguna carga de datos adicional desde el servidor subyacente.[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina si la imagen se puede guardar en el formato de archivo especificado representado por las opciones de guardado pasadas. |
| override [Crop](../../aspose.imaging.fileformats.emf/emfimage/crop#crop)(Rectangle) | Recorta el rectángulo especificado. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop)(int, int, int, int) | Recortar imagen con turnos. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.emf/emfimage/getdefaultoptions)(object[]) | Obtiene las opciones predeterminadas. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Obtiene las imágenes incrustadas. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | Devuelve la lista de fuentes que se usaron dentro del metarchivo pero no se encontraron. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener sin cambios la profundidad de bits y otros parámetros de la imagen original. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego guardarlo usando the [`Save`](../../aspose.imaging/datastreamsupporter/save) se producirá la imagen PNG de salida con 8 bits por píxel.[`Save`](../../aspose.imaging/image/save) método como el segundo parámetro. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.emf/emfimage/getusedfonts)() | Devuelve la lista de fuentes que se usaron dentro del metarchivo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Cambia el tamaño de la imagen. El valor por defectoNearestNeighbourResample se usa. |
| override [Resize](../../aspose.imaging.fileformats.emf/emfimage/resize#resize_1)(int, int, ImageResizeSettings) | Cambia el tamaño de la imagen. |
| override [Resize](../../aspose.imaging.fileformats.emf/emfimage/resize#resize_2)(int, int, ResizeType) | Cambia el tamaño de la imagen. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.emf/emfimage/resizecanvas)(Rectangle) | Cambia el tamaño del lienzo. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Cambia el tamaño de la altura proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Cambia el tamaño de la altura proporcionalmente. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Cambia el tamaño de la altura proporcionalmente. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Cambia el tamaño del ancho proporcionalmente. El valor por defectoNearestNeighbourResample se usa. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Cambia el tamaño del ancho proporcionalmente. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Cambia el tamaño del ancho proporcionalmente. |
| override [RotateFlip](../../aspose.imaging.fileformats.emf/emfimage/rotateflip)(RotateFlipType) | Gira, voltea o gira y voltea la imagen. |
| [Save](../../aspose.imaging/image/save)() | Guarda los datos de la imagen en el flujo subyacente. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| override [Save](../../aspose.imaging/image/save)(string) | Guarda la imagen en la ubicación de archivo especificada. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| override [SetPalette](../../aspose.imaging.fileformats.emf/emfimage/setpalette)(IColorPalette, bool) | Establece la paleta de la imagen. |

### Ejemplos

El siguiente ejemplo muestra cómo convertir imágenes emz a emf fromat

```csharp
[C#]

string file = "example.emz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions {PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

El siguiente ejemplo muestra cómo convertir imágenes emf a emz fromat

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
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

Este ejemplo muestra cómo cargar una imagen EMF desde un archivo y convertirla a SVG usando EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// El uso de Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // El texto se convertirá en formas.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // El color de fondo de la superficie de dibujo.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // El tamaño de la página.
    rasterizationOptions.PageSize = emfImage.Size;

    // Si existe una emf incrustada, renderizar emf; de lo contrario renderizar wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // Establecer el margen horizontal
    rasterizationOptions.BorderX = 50;

    // Establecer el margen vertical
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### Ver también

* class [MetaImage](../metaimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
