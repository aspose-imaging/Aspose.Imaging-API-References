---
title: ApngOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Las opciones de formato de archivo PNG animado
type: docs
weight: 9900
url: /es/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

Las opciones de formato de archivo PNG animado

```csharp
public class ApngOptions : PngOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ApngOptions](apngoptions)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | La profundidad de bits. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Obtiene o establece el tipo de color. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | El nivel de compresión de la imagen png en el rango de 0-9, donde 9 es la compresión máxima y 0 es el modo de almacenamiento. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime) { get; set; } | Obtiene o establece la duración del marco predeterminado. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | Obtiene o establece el tipo de filtro utilizado durante el proceso de guardado del archivo png. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays) { get; set; } | Obtiene o establece el número de veces que se repite la animación. 0 indica un bucle infinito. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive) { get; set; } | Obtiene o establece un valor que indica si este[`PngOptions`](../pngoptions) es progresivo. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| override [XmpData](../../aspose.imaging.imageoptions/pngoptions/xmpdata) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona esta instancia. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina la instancia actual. |

### Ejemplos

El siguiente ejemplo muestra cómo exportar el formato de archivo apng APNG desde otro formato de varias páginas no animadas.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Configuración de la duración del cuadro por defecto
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250ms
}
```

El siguiente ejemplo muestra cómo exportar al formato de archivo APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Exportar a animación APNG con ciclos de animación ilimitados por defecto
    image.Save("Animation1.webp.png", new ApngOptions());
    // Configuración de ciclos de animación
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 ciclos
}
```

El siguiente ejemplo muestra cómo crear una imagen APNG a partir de otra imagen ráster de una sola página.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 segundo
const int FrameDuration = 70; // 70ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // Es posible establecer el tiempo de cuadro predeterminado de la imagen allí: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Limpieza porque la imagen contiene un cuadro por defecto
        apngImage.RemoveAllFrames();

        // agrega el primer cuadro
        apngImage.AddFrame(sourceImage);

        // agregar marcos intermedios
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // agrega el último cuadro
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Ver también

* class [PngOptions](../pngoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
