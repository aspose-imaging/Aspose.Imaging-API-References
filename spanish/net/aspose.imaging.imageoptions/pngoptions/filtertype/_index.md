---
title: FilterType
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el tipo de filtro utilizado durante el proceso de guardado del archivo png.
type: docs
weight: 50
url: /es/net/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

Obtiene o establece el tipo de filtro utilizado durante el proceso de guardado del archivo png.

```csharp
public PngFilterType FilterType { get; set; }
```

### Ejemplos

Este ejemplo muestra cómo crear una imagen PNG con las opciones especificadas, rellenarla con colores degradados lineales y guardarla en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// El número de bits por canal de color
createOptions.BitDepth = 8;

// Cada píxel es un triple (rojo, verde, azul) seguido del componente alfa.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// El nivel máximo de compresión.
createOptions.CompressionLevel = 9;

// El uso de filtros permite comprimir imágenes tonales continuas de manera más efectiva.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Usar carga progresiva
createOptions.Progressive = true;

// Crea una imagen PNG con parámetros personalizados.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Rellena la imagen con un degradado semitransparente.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Guardar en un archivo.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

El siguiente ejemplo muestra cómo los diferentes tipos de filtros afectan el tamaño de la imagen PNG de salida.

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // Establecer un tipo de filtro
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

//La salida puede verse así:
//El tipo de filtro es Ninguno, el tamaño de la imagen de salida es 116845 bytes.
//El tipo de filtro es Up, el tamaño de la imagen de salida es 86360 bytes.
//El tipo de filtro es Sub, el tamaño de la imagen de salida es 94907 bytes.
//El tipo de filtro es Paeth, el tamaño de la imagen de salida es 86403 bytes.
//El tipo de filtro es Promedio, el tamaño de la imagen de salida es 89956 bytes.
//El tipo de filtro es Adaptativo, el tamaño de la imagen de salida es de 97248 bytes.
```

El siguiente ejemplo muestra cómo guardar una imagen en formato PNG usando varias opciones.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
// También puede cargar una imagen de cualquier formato compatible desde un archivo o una transmisión.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Rellena la imagen con el degradado azul transparente.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // Carga progresiva.
    saveOptions.Progressive = true;

    // Establezca la resolución horizontal y vertical en 96 píxeles por pulgada.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // Cada píxel es un triple (rojo, verde, azul) seguido de alfa.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // Establecer el nivel máximo de compresión.
    saveOptions.CompressionLevel = 9;

    // Esta es la mejor compresión, pero el tiempo de ejecución más lento.
    // El filtrado adaptativo significa que el proceso de guardado elegirá el filtro más adecuado para cada fila de datos.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // El número de bits por canal.
    saveOptions.BitDepth = 8;

    // Guardar en un archivo.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### Ver también

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype)
* class [PngOptions](../../pngoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../pngoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
