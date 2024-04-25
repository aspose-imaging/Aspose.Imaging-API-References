---
title: ColorType
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el tipo de color.
type: docs
weight: 30
url: /es/aspose.imaging.imageoptions/pngoptions/colortype/
---
## PngOptions.ColorType property

Obtiene o establece el tipo de color.

```csharp
public PngColorType ColorType { get; set; }
```

### El valor de la propiedad

El tipo de color.

### Ejemplos

El siguiente ejemplo muestra cómo comprimir una imagen PNG, usando color indexado con la paleta de mejor ajuste

```csharp
[C#]

// Carga la imagen png        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Usar tipo de color indexado
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Usar compresión máxima
         CompressionLevel = 9,
      // Obtenga la paleta de colores de 8 bits más cercana que cubra tantos píxeles como sea posible, de modo que una imagen paletizada
         // es casi indistinguible visualmente de uno no paletizado.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // El tamaño del archivo de salida debe reducirse significativamente
```

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

* enum [PngColorType](../../../aspose.imaging.fileformats.png/pngcolortype)
* class [PngOptions](../../pngoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../pngoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
