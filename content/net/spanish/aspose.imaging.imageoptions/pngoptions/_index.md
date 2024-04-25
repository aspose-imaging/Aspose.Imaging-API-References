---
title: PngOptions
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Las opciones de creación de formato de archivo png.
type: docs
weight: 10120
url: /es/aspose.imaging.imageoptions/pngoptions/
---
## PngOptions class

Las opciones de creación de formato de archivo png.

```csharp
public class PngOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PngOptions](pngoptions#constructor)() | Inicializa una nueva instancia del[`PngOptions`](../pngoptions) clase. |
| [PngOptions](pngoptions#constructor_1)(PngOptions) | Inicializa una nueva instancia del[`PngOptions`](../pngoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | La profundidad de bits. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Obtiene o establece el tipo de color. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | El nivel de compresión de la imagen png en el rango de 0-9, donde 9 es la compresión máxima y 0 es el modo de almacenamiento. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | Obtiene o establece el tipo de filtro utilizado durante el proceso de guardado del archivo png. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
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

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.imaging.imageoptions/pngoptions/defaultcompressionlevel) | El nivel de compresión predeterminado. |

### Ejemplos

Este ejemplo demuestra el uso de diferentes clases del espacio de nombres SaveOptions con fines de exportación. Una imagen de tipo Gif se carga en una instancia de Imagen y luego se exporta a varios formatos.

```csharp
[C#]

string dir = "c:\\temp\\";

//Cargar una imagen existente (de tipo Gif) en una instancia de la clase Imagen
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Exportar a formato de archivo BMP utilizando las opciones predeterminadas
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //Exportar a formato de archivo JPEG usando las opciones predeterminadas
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //Exportar a formato de archivo PNG usando las opciones predeterminadas
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //Exportar a formato de archivo TIFF usando las opciones predeterminadas
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

El siguiente ejemplo muestra cómo convertir una imagen vectorial de varias páginas a formato PNG de manera general sin hacer referencia a un tipo de imagen en particular.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.png");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportar solo las dos primeras páginas. De hecho, solo se rasterizará una página porque PNG no es un formato de varias páginas.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

Este ejemplo usa la clase Graphics para crear formas primitivas en la superficie de la imagen. Para demostrar la operación, el ejemplo crea una nueva imagen en formato PNG y dibuja formas primitivas en la superficie de la imagen utilizando los métodos de dibujo expuestos por la clase Graphics.

```csharp
[C#]

//Crea una instancia de FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Cree una instancia de PngOptions y configure sus diversas propiedades
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Establecer la fuente para PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crear una instancia de Imagen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Crear e inicializar una instancia de la clase Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Borrar superficie gráfica
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        // Dibuje un Arco especificando el objeto Pluma que tiene color Negro, 
        //un rectángulo que rodea el arco, el ángulo de inicio y el ángulo de barrido
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Dibuje un Bézier especificando el objeto Pen que tiene color azul y puntos de coordenadas.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Dibuje una curva especificando el objeto Pen que tiene color verde y una matriz de puntos
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Dibuja una Elipse usando el objeto Pluma y un Rectángulo circundante
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Dibuja una línea 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Dibujar un segmento circular
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Dibuje un polígono especificando el objeto Pen que tiene color rojo y una matriz de puntos
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Dibujar un Rectángulo
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Crear un objeto SolidBrush y establecer sus diversas propiedades
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Dibuje una cadena usando el objeto SolidBrush y la fuente, en un punto específico
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // guarda todos los cambios.
        image.Save();
    }
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
