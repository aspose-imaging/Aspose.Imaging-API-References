---
title: ResolutionSettings
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece la configuración de resolución.
type: docs
weight: 60
url: /es/net/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

Obtiene o establece la configuración de resolución.

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

### Ejemplos

El siguiente ejemplo carga una imagen BMP y la vuelve a guardar en BMP usando varias opciones de guardado.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Crear BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Use 8 bits por píxel para reducir el tamaño de la imagen de salida.
    saveOptions.BitsPerPixel = 8;

    // Establezca la paleta de colores de 8 bits más cercana que cubra el número máximo de píxeles de la imagen, de modo que una imagen paletizada
    // es casi indistinguible visualmente de uno no paletizado.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Guardar sin compresión.
    // También puede usar la compresión RLE-8 para reducir el tamaño de la imagen de salida.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Establezca la resolución horizontal y vertical en 96 ppp.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

El siguiente ejemplo carga una imagen BMP y la guarda en JPEG usando varias opciones de guardado.

```csharp
[C#]

string dir = "c:\\temp\\";

// Cargar una imagen BMP desde un archivo.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Haz algo de procesamiento de imágenes.

    // Use opciones adicionales para especificar los parámetros de imagen deseados.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // El número de bits por canal es 8.
    // Cuando se usa una paleta, el índice de color se almacena en los datos de la imagen en lugar del color en sí.
    saveOptions.BitsPerChannel = 8;

    // Establecer el tipo progresivo de compresión.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Establecer la calidad de la imagen. Es un valor entre 1 y 100.
    saveOptions.Quality = 100;

    // Establezca la resolución horizontal/vertical en 96 puntos por pulgada.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // Si la imagen de origen está coloreada, se convertirá a escala de grises.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Usa una paleta para reducir el tamaño de salida.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

El siguiente ejemplo crea una imagen BMP paletizada en escala de grises y luego la guarda en un archivo.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// Guardar en un archivo
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// Use 8 bits por píxel para reducir el tamaño de la imagen de salida.
createOptions.BitsPerPixel = 8;

// Configure la paleta de colores estándar de escala de grises de 8 bits que cubre todos los colores de escala de grises.
// Si la imagen procesada contiene solo colores en escala de grises, entonces su versión paletizada
// es visualmente indistinguible de uno no paletizado.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// Guardar sin compresión.
// También puede usar la compresión RLE-8 para reducir el tamaño de la imagen de salida.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// Establezca la resolución horizontal y vertical en 96 ppp.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// Cree una imagen BMP de 100 x 100 px y guárdela en un archivo.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // Rellena la imagen con un degradado en escala de grises
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

El siguiente ejemplo muestra cómo crear una imagen JPEG del tamaño especificado con los parámetros especificados.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea una imagen JPEG de 100x100 px.
// Use opciones adicionales para especificar los parámetros de imagen deseados.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// El número de bits por canal es 8, 8, 8 para los componentes Y, Cr, Cb en consecuencia.
createOptions.BitsPerChannel = 8;

// Establecer el tipo progresivo de compresión.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Establecer la calidad de la imagen. Es un valor entre 1 y 100.
createOptions.Quality = 100;

// Establezca la resolución horizontal/vertical en 96 puntos por pulgada.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// Esta es una opción estándar para imágenes JPEG.
// Dos componentes de croma (Cb y Cr) se pueden reducir en ancho de banda, submuestrear y comprimir.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Rellena la imagen con un degradado en escala de grises
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Guardar en un archivo.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### Ver también

* class [ResolutionSetting](../../resolutionsetting)
* class [ImageOptionsBase](../../imageoptionsbase)
* espacio de nombres [Aspose.Imaging](../../imageoptionsbase)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->